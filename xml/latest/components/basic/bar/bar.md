```xml title="examples/components/basic/bar/bar.xml" source="https://github.com/lvgl/lvgl/blob/d8e8c86508ddcabc4bf27676b63fa2ad0a7626fb/examples/components/basic/bar/bar.xml"
<component>
	<previews>
		<preview style_pad_all="20" />
	</previews>

	<styles>
		<style name="style_main" bg_color="#surface_primary_light" bg_opa="#opa_muted" radius="20" height="#unit_sm" />
		<style name="style_indicator" bg_color="#surface_primary_light" bg_opa="100%" radius="20" />
		<style name="style_dark" bg_color="#surface_primary_dark" />
	</styles>

	<view extends="lv_bar">
		<remove_style_all />
		<style name="style_main" />
		<style name="style_indicator" selector="indicator" />
		<bind_style subject="dark_theme" ref_value="1" name="style_dark" />
		<bind_style subject="dark_theme" ref_value="1" name="style_dark" selector="indicator" />
	</view>
</component>
```
