```xml title="tutorials/screens/data_bindings/screen_data_bindings.xml" source="https://github.com/lvgl/lvgl_pro/blob/4d7ba569dca8c4f02e925c92a83dad5beedb3ad9/tutorials/screens/data_bindings/screen_data_bindings.xml"
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
