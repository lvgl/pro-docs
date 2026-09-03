```xml title="templates/basic/components/images/image/image.xml" source="https://github.com/lvgl/lvgl_pro/blob/6d04ae8c667ee14d83198e659f3f199a1cc99fec/templates/basic/components/images/image/image.xml"
<component>
	<previews>
		<preview name="default" width="120" height="120" />
	</previews>

	<api>
		<prop name="src" type="image" default="NULL" help="Image source to display" />
	</api>

	<!-- Plain image. Set only its source; the size follows the image. -->
	<view extends="lv_image" src="$src" />
</component>
```
