```xml title="templates/basic/components/images/image/image.xml" source="https://github.com/lvgl/lvgl_pro/blob/18e1933b22cf7c1855a2e4dd6768cbc8bc703134/templates/basic/components/images/image/image.xml"
<component>
	<previews>
		<preview name="default" width="120" height="120" />
	</previews>

	<api>
		<prop name="src" type="image" default="NULL" help="Image source to display" />
	</api>

	<!-- Plain image. Set only its source; the size follows the image. -->
	<view extends="lv_image" src="{src}" />
</component>
```
