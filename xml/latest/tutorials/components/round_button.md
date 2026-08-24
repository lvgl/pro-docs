```xml title="tutorials/components/round_button.xml" source="https://github.com/lvgl/lvgl_pro/blob/b50910a3acc7ed2355e2e41eabaca2630a9e383d/tutorials/components/round_button.xml"
<!-- A small round button that increments a subject on press and long-press repeat. -->
<component>
	<api>
		<prop name="text" type="string" default="?" />
		<prop name="subject" type="subject" default="" />
		<prop name="step" type="int" default="1" />
	</api>

	<consts>
		<int name="size" value="36" />
	</consts>

	<view extends="lv_button" width="#size" height="#size" style_radius="#size" ext_click_area="8">
		<lv_label text="$text" align="center" />

		<subject_increment_event subject="$subject" step="$step" trigger="pressed" />
		<subject_increment_event subject="$subject" step="$step" trigger="long_pressed_repeat" />
	</view>
</component>
```
