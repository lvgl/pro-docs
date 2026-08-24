```xml title="templates/basic/components/typography/text/text.xml" source="https://github.com/lvgl/lvgl_pro/blob/b50910a3acc7ed2355e2e41eabaca2630a9e383d/templates/basic/components/typography/text/text.xml"
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
