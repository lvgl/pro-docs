```xml title="tutorials/screens/data_bindings/screen_data_bindings.xml" source="https://github.com/lvgl/lvgl_pro/blob/0db8cf78c5106b4829538771f6cb5d4288506cf2/tutorials/screens/data_bindings/screen_data_bindings.xml"
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
