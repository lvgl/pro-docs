```xml title="templates/basic/components/images/image/image.xml" source="https://github.com/lvgl/lvgl_pro/blob/e56c9b98c7af2f263a49f8b0fe5756d8aee2ff5a/templates/basic/components/images/image/image.xml"
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
