```xml title="tutorials/screens/data_bindings/screen_data_bindings.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/tutorials/screens/data_bindings/screen_data_bindings.xml"
<screen>
	<view flex_flow="column" style_flex_track_place="center">
		<!-- Just the components with the simple API
		     Also check the Subject panel under the preview. -->
		<sliderbox subject="subject_max_current" title="Max. current" unit="%d mA" />
		<sliderbox subject="subject_timeout" title="Timeout" unit="%d ms" />
		<sliderbox subject="subject_volume" title="Volume" unit="%d%%" />
	</view>
</screen>
```
