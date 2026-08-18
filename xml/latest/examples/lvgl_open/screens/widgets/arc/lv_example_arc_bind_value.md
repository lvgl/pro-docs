```xml title="examples/lvgl_open/screens/widgets/arc/lv_example_arc_bind_value.xml" source="https://github.com/lvgl/lvgl_pro/blob/c4a99074ccc701fd983c2e1e0b01b1ba7645abe7/examples/lvgl_open/screens/widgets/arc/lv_example_arc_bind_value.xml"
<screen>
	<animations>
		<timeline name="t1">
			<animation prop="translate_x" start="-200" end="0" target="arc" duration="1000" />
		</timeline>
	</animations>
	<consts>
		<int name="base" value="80" />
	</consts>
	<view
		flex_flow="column"
		style_flex_main_place="center"
		style_flex_cross_place="center"
		style_flex_track_place="center"
		style_pad_row="16"
	>
		<lv_arc
			name="arc"
			bind_value="subject_value"
			clickable="false"
			style_bg_opa-knob="0%"
			hidden="{10 * (2 + base)}"
			x="10"
			y="20"
			height="130"
		>
			<bind_flag_if_gt flag="hidden" subject="subject_value" ref_value="60" />
			<lv_label align="center" text="{'' . base}" />
		</lv_arc>

		<lv_slider name="slider" width="220" bind_value="subject_value" y="200" />
	</view>
</screen>
```
