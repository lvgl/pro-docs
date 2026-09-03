```xml title="tutorials/screens/hello_world/screen_hello_world.xml" source="https://github.com/lvgl/lvgl_pro/blob/6d04ae8c667ee14d83198e659f3f199a1cc99fec/tutorials/screens/hello_world/screen_hello_world.xml"
<!-- The simplest screen: a background style, a button and a label. Start here. -->
<screen>
	<styles>
		<style name="style_main" bg_color="0x00688a" />
	</styles>

	<view>
		<style name="style_main" />

		<lv_button align="center" style_bg_color="0x111">
			<lv_label text="Hello world" style_text_font="montserrat_16_bin_file" />
		</lv_button>
	</view>
</screen>
```
