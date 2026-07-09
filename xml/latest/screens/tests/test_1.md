```xml title="examples/screens/tests/test_1.xml" source="https://github.com/lvgl/lvgl/blob/d8e8c86508ddcabc4bf27676b63fa2ad0a7626fb/examples/screens/tests/test_1.xml"
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
