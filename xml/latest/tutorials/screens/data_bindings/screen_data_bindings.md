```xml title="tutorials/screens/data_bindings/screen_data_bindings.xml" source="https://github.com/lvgl/lvgl_pro/blob/6a64e6a851619119c359a5ae0ca6e8091732a70c/tutorials/screens/data_bindings/screen_data_bindings.xml"
<screen>
	<view flex_flow="column" style_flex_track_place="center">
		<!-- Just the components with the simple API
		     Also check the Subject panel under the preview. -->
		<sliderbox
			subject="subject_max_current"
			title="Max. current"
			unit="mA"
		/>
		<sliderbox subject="subject_timeout" title="Timeout" unit="ms" />
		<sliderbox subject="subject_volume" title="Volume" unit="%" />
	</view>
</screen>
```
