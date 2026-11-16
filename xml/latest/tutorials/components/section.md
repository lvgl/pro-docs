```xml title="tutorials/components/section.xml" source="https://github.com/lvgl/lvgl_pro/blob/0db8cf78c5106b4829538771f6cb5d4288506cf2/tutorials/components/section.xml"
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
