```xml title="tutorials/components/section.xml" source="https://github.com/lvgl/lvgl_pro/blob/3514c1eb6b7075d42b1ef8bd36931a525c3d56f3/tutorials/components/section.xml"
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
