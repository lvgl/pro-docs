```xml title="examples/lvgl_open/screens/widgets/image/lv_example_image_src.xml" source="https://github.com/lvgl/lvgl_pro/blob/c4a99074ccc701fd983c2e1e0b01b1ba7645abe7/examples/lvgl_open/screens/widgets/image/lv_example_image_src.xml"
<!--
 @title Image source
 @brief Display an image registered globally for the project.

 `lv_image` paints whatever is set as its `src`.
 In C the image can be a file or a C array.
 In XML the source needs to b set in globals.xml.-->
<screen>
	<view>
		<!-- 💡 Register another image in `globals.xml` and swap `src` to its name to see a different bitmap. -->
		<lv_image name="image" src="img_example_lvgl_logo" align="center" />
	</view>
</screen>
```
