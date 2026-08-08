```xml title="examples/lvgl_pro/screens/lv_example_image.xml" source="https://github.com/lvgl/lvgl_pro/blob/4d05fc79f26b1a8daf2c0134018f3d07c6f19286/examples/lvgl_pro/screens/lv_example_image.xml"
<!--
 @title Image
 @brief The same source shown plain, rotated + scaled, and recoloured.

 `src` points at a registered image. The second copy sets `rotation` (in
 0.1° steps) with `scale_x`/`scale_y` (256 = 100 %) around a centred pivot.
 The third uses the `image_recolor` style properties to tint the pixels.
-->
<screen>
	<styles>
		<style name="style_tint" image_recolor="0x3b82f6" image_recolor_opa="80%" />
	</styles>

	<view
		style_pad_all="0"
		flex_flow="row"
		style_flex_main_place="space_evenly"
		style_flex_cross_place="center"
		style_flex_track_place="center"
	>
		<lv_image src="img_logo" />

		<lv_image src="img_logo" rotation="300" scale_x="580" scale_y="180" />

		<lv_image src="img_logo">
			<style name="style_tint" />
		</lv_image>
	</view>
</screen>
```
