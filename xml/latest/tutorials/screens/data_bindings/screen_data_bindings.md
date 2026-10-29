```xml title="tutorials/screens/data_bindings/screen_data_bindings.xml" source="https://github.com/lvgl/lvgl_pro/blob/521c6cf8b209faecc21d3ffcf59fede7cb5d01c2/tutorials/screens/data_bindings/screen_data_bindings.xml"
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
