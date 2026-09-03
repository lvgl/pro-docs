```xml title="tutorials/screens/new_component/screen_components.xml" source="https://github.com/lvgl/lvgl_pro/blob/6d04ae8c667ee14d83198e659f3f199a1cc99fec/tutorials/screens/new_component/screen_components.xml"
<!-- Use all our components to create a screen with a column layout -->
<screen>
	<view flex_flow="column" style_pad_all="#unit_small" style_flex_cross_place="center">
		<section text="Normal buttons" />
		<button_normal />
		<button_normal label_text="Custom text" />
		<button_normal label_text="Full width" width="100%" />

		<section text="Warning buttons" />
		<button_warning />
		<button_warning label_text="Upps!" />
	</view>
</screen>
```
