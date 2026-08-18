```xml title="templates/basic/components/list/list_separator/list_separator.xml" source="https://github.com/lvgl/lvgl_pro/blob/c4a99074ccc701fd983c2e1e0b01b1ba7645abe7/templates/basic/components/list/list_separator/list_separator.xml"
<component>
	<previews>
		<preview name="default" width="320" height="20" />
	</previews>

	<styles>
		<style name="style_list_separator" bg_color="#color_track" bg_opa="25%" />
	</styles>

	<!-- A 1px full-width divider line. No API — drop it between rows wherever
	     you want a visual break. Extends the theme-free container, so its style
	     and height apply after remove_style_all and stick. -->
	<view extends="container" width="100%" height="1">
		<style name="style_list_separator" />
	</view>
</component>
```
