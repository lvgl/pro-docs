```xml title="examples/lvgl_pro/screens/lv_example_imagebutton.xml" source="https://github.com/lvgl/lvgl_pro/blob/4d05fc79f26b1a8daf2c0134018f3d07c6f19286/examples/lvgl_pro/screens/lv_example_imagebutton.xml"
<!--
 @title Image button
 @brief A button drawn from per-state images instead of a styled rectangle.

 `<lv_imagebutton-src_left>`, `-src_mid` and `-src_right` set the image for
 a given `state`. The middle image is tiled to fill the width, so left and
 right act as fixed end-caps. Here the released and pressed states use the
 same source to keep the example self-contained.
-->
<screen>
	<styles>
		<style name="style_pressed" transform_width="10" image_recolor="0x000" image_recolor_opa="20%" />
	</styles>
	<view>
		<lv_imagebutton width="160" align="center">
			<style name="style_pressed" selector="pressed" />
			<lv_imagebutton-src_left state="released" src="imgbtn_left" />
			<lv_imagebutton-src_mid state="released" src="imgbtn_mid" />
			<lv_imagebutton-src_right state="released" src="imgbtn_right" />

			<lv_label align="center" text="Press" style_text_color="0xffffff" y="-3" />
		</lv_imagebutton>
	</view>
</screen>
```
