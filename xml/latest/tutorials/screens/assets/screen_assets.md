```xml title="tutorials/screens/assets/screen_assets.xml" source="https://github.com/lvgl/lvgl_pro/blob/91553dccc827bdbb5d49302579f6a8df95e2db84/tutorials/screens/assets/screen_assets.xml"
<!-- Check out globals.xml for the font and image definitions -->
<screen>
	<view flex_flow="column" style_pad_all="8">
		<lv_label text="I'm from a C array: °" style_text_font="montserrat_14_c_array" />
		<lv_label text="I'm from a bin file: °" style_text_font="montserrat_16_bin_file" />
		<lv_label text="I'm TinyTTF from data: Schöne" style_text_font="montserrat_18_tiny_ttf_data" />
		<lv_label text="I'm TinyTTF from file: Schöne" style_text_font="montserrat_20_tiny_ttf_file" />

		<lv_obj width="100%" height="content" flex_flow="row">
			<lv_image src="flower_data" />
			<lv_image src="flower_file" />
		</lv_obj>
	</view>
</screen>
```
