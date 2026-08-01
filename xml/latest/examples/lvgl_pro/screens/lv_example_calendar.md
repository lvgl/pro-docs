```xml title="examples/lvgl_pro/screens/lv_example_calendar.xml" source="https://github.com/lvgl/lvgl_pro/blob/64ebc7a7b6db60ed63db7ca4dae1573c702c882a/examples/lvgl_pro/screens/lv_example_calendar.xml"
<!--
 @title Calendar
 @brief A month view with today highlighted and a dropdown month picker.

 `shown_year`/`shown_month` choose the visible month and
 `today_year`/`today_month`/`today_day` highlight the current date. The
 `<lv_calendar-header_dropdown>` element adds dropdowns for jumping to
 another month or year.
-->
<screen>
	<styles>
		<style name="style_cal" bg_color="0x0f172a" bg_opa="100%" text_color="0xe2e8f0" radius="8" />
	</styles>

	<view>
		<!-- 💡 Use the header dropdowns to change month or year. -->
		<lv_calendar
			width="260"
			height="280"
			shown_year="2026"
			shown_month="5"
			align="center"
			today_year="2026"
			today_month="5"
			today_day="17"
		>
			<style name="style_cal" />
			<lv_calendar-header_dropdown />
		</lv_calendar>
	</view>
</screen>
```
