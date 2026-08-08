```xml title="tutorials/components/section.xml" source="https://github.com/lvgl/lvgl_pro/blob/4d05fc79f26b1a8daf2c0134018f3d07c6f19286/tutorials/components/section.xml"
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
