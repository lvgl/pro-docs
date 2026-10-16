```xml title="tutorials/screens/new_component/screen_components.xml" source="https://github.com/lvgl/lvgl_pro/blob/0ac641547f16b87445de3e2c998c17b340844964/tutorials/screens/new_component/screen_components.xml"
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
