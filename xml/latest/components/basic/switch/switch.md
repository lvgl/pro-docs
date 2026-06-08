```xml title="examples/components/basic/switch/switch.xml" source="https://github.com/lvgl/lvgl/blob/c7f14db4472da8ca3d086ab82e66073a696a96e4/examples/components/basic/switch/switch.xml"
<component>
	<styles>
		<style name="switch_knob" pad_all="-4" shadow_opa="0" />
		<style name="switch_knob_light" bg_color="#bg_primary_light" />
		<style name="switch_knob_dark" bg_color="#bg_primary_dark" />
		<style name="switch_main_light" bg_color="#surface_primary_light" bg_opa="24" />
		<style name="switch_main_dark" bg_color="#surface_primary_dark" bg_opa="24" />
		<style name="switch_indicator_light" bg_color="#surface_primary_light" />
		<style name="switch_indicator_dark" bg_color="#surface_primary_dark" />
	</styles>
	<view extends="lv_switch" width="48" height="32">
		<style name="switch_knob" selector="knob" />
		<style name="switch_knob_light" selector="knob" />
		<style name="switch_main_light" selector="main" />
		<style name="switch_indicator_light" selector="indicator|checked" />
		<bind_style subject="dark_theme" ref_value="1" name="switch_knob_dark" selector="knob" />
		<bind_style subject="dark_theme" ref_value="1" name="switch_main_dark" selector="main" />
		<bind_style subject="dark_theme" ref_value="1" name="switch_indicator_dark" selector="indicator|checked" />
	</view>
</component>
```
