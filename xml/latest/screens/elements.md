```xml title="examples/screens/elements.xml" source="https://github.com/lvgl/lvgl/blob/d8e8c86508ddcabc4bf27676b63fa2ad0a7626fb/examples/screens/elements.xml"
<screen>
	<styles>
		<style name="style_light" bg_color="#accent2_50_light" />
		<style name="style_dark" bg_color="#accent2_50_dark" />
	</styles>
	<view flex_flow="column">
		<bind_style subject="dark_theme" name="style_light" ref_value="0" />
		<bind_style subject="dark_theme" name="style_dark" ref_value="1" />

		<row width="100%" style_flex_cross_place="center" style_pad_all="#unit_md">
			<bind_style subject="dark_theme" name="style_light" ref_value="0" />
			<bind_style subject="dark_theme" name="style_dark" ref_value="1" />
			<theme_switcher flex_grow="1" />
			<button label="Play Animation" width="content">
				<play_timeline_event target="alarm_0" timeline="open" />
			</button>
		</row>

		<div
			flex_grow="1"
			scroll_snap_y="center"
			scroll_one="true"
			style_flex_track_place="center"
			style_pad_row="#unit_xl"
		>
			<alarm name="alarm_0" />
			<thermostat />
			<move_goal />
			<weather />
			<light_temperature />
			<music_player />
			<speaker_volume />
		</div>
	</view>
</screen>
```
