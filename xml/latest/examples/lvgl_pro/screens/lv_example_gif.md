```xml title="examples/lvgl_pro/screens/lv_example_gif.xml" source="https://github.com/lvgl/lvgl_pro/blob/b50910a3acc7ed2355e2e41eabaca2630a9e383d/examples/lvgl_pro/screens/lv_example_gif.xml"
<!--
 @title GIF
 @brief An animated GIF, embedded as a raw C array.

 `src` names an image from `globals.xml`, registered there with
 `color_format="raw"`, so the export embeds the GIF file itself instead of
 converting it. `loop_count` sets how many times it repeats; leave it unset to
 use the count stored in the GIF.
-->
<screen>
	<view>
		<lv_gif src="img_bulb" loop_count="10" align="center"/>
	</view>
</screen>
```
