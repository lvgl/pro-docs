```xml title="tutorials/components/section.xml" source="https://github.com/lvgl/lvgl_pro/blob/c4a99074ccc701fd983c2e1e0b01b1ba7645abe7/tutorials/components/section.xml"
<!-- A simple label like component that acts as an lv_label but has some custom styles
     For the sake of simplicity inline styles were used instead of a <style> tag -->
<component>
	<view
		extends="lv_label"
		style_width="100%"
		style_text_align="center"
		style_border_side="bottom"
		style_border_width="1"
		style_margin_top="12"
	/>
</component>
```
