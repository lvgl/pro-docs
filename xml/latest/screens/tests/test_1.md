```xml title="examples/screens/tests/test_1.xml" source="https://github.com/lvgl/lvgl/blob/7785e89ec4cef12ae82b026aa653c580dd7a2d2a/examples/screens/tests/test_1.xml"
<test>
	<view extends="elements" />
	<steps>
		<subject_set subject="dark_theme" value="0" />
		<subject_set subject="thermostat_temp" value="20" />
		<subject_set subject="room_temp" value="22" />

		<screenshot_compare path="start.png" />

		<move_to x="10" y="300" />
		<press />
		<wait ms="100" />
		<move_to x="10" y="200" />
		<wait ms="100" />
		<release />
		<wait ms="500" />
		<screenshot_compare path="show_move_goal.png" />
	</steps>
</test>
```
