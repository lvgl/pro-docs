```xml title="tutorials/screens/hello_world/screen_hello_world.xml" source="https://github.com/lvgl/lvgl_pro/blob/0cf032b483962f1d7111da38d18218f06dd78ea0/tutorials/screens/hello_world/screen_hello_world.xml"
<!-- The simplest screen: a background style, a button and a label. Start here. -->
<screen>
	<styles>
		<style name="style_main" bg_color="0x00688a" />
	</styles>

	<view>
		<style name="style_main" />

		<lv_button align="center" style_bg_color="0x111">
			<lv_label
				text="Hello world"
				style_text_font="montserrat_16_bin_file"
			/>
		</lv_button>
	</view>
</screen>
```
