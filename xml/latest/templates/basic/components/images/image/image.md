```xml title="templates/basic/components/images/image/image.xml" source="https://github.com/lvgl/lvgl_pro/blob/2b291f2ba054540cc7f4397e419866f9e1f5a84f/templates/basic/components/images/image/image.xml"
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
