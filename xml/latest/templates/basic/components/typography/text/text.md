```xml title="templates/basic/components/typography/text/text.xml" source="https://github.com/lvgl/lvgl_pro/blob/64ebc7a7b6db60ed63db7ca4dae1573c702c882a/templates/basic/components/typography/text/text.xml"
<component>
	<api>
		<prop name="text" type="string" default="Body text" help="The paragraph / body text" />
	</api>

	<styles>
		<style name="style_text" text_font="font_body" />
	</styles>

	<!-- Body copy. Text color is inherited.
	     Give it a width to make it wrap: <text text="..." width="100%" /> -->
	<view extends="lv_label" text="$text" long_mode="wrap">
		<style name="style_text" />
	</view>
</component>
```
