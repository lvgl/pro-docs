```xml title="templates/basic/components/images/image/image.xml" source="https://github.com/lvgl/lvgl_pro/blob/c4a99074ccc701fd983c2e1e0b01b1ba7645abe7/templates/basic/components/images/image/image.xml"
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
