```xml title="tutorials/components/round_button.xml" source="https://github.com/lvgl/lvgl_pro/blob/0cf032b483962f1d7111da38d18218f06dd78ea0/tutorials/components/round_button.xml"
<!-- A small round button that increments a subject on press and long-press repeat. -->
<component>
	<api>
		<prop name="text" type="string" default="?" />
		<prop name="subject" type="subject" />
		<prop name="step" type="int" default="1" />
	</api>

	<consts>
		<int name="size" value="36" />
	</consts>

	<view
		extends="lv_button"
		width="{size}"
		height="{size}"
		style_radius="{size / 2}"
		ext_click_area="8"
	>
		<lv_label text="{text}" align="center" />

		<set_subject_event
			subject="{subject}"
			value="{subject + step}"
			trigger="pressed"
		/>
		<set_subject_event
			subject="{subject}"
			value="{subject + step}"
			trigger="long_pressed_repeat"
		/>
	</view>
</component>
```
