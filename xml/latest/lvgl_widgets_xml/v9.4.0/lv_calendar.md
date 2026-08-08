```xml title="lvgl_widgets_xml/v9.4.0/lv_calendar.xml" source="https://github.com/lvgl/lvgl_pro/blob/3514c1eb6b7075d42b1ef8bd36931a525c3d56f3/lvgl_widgets_xml/v9.4.0/lv_calendar.xml"
<!--
Example
<lv_calendar src="img1 img2" duration="300" repeat_count="3"/>
-->

<widget>
    <api>
        <prop name="today_year" type="int" help="Mark today’s year in the calendar"/>
        <prop name="today_month" type="int" help="Mark today’s month in the calendar"/>
        <prop name="today_day" type="int" help="Mark today’s day in the calendar"/>

        <prop name="shown_year" type="int" help="Show this year in the calendar"/>
        <prop name="shown_month" type="int" help="Show this month in the calendar"/>

        <element name="header_arrow" access="add" help="Add arrow buttons for navigating months"/>
        <element name="header_dropdown" access="add" help="Add a dropdown for selecting months or years"/>
    </api>
</widget>
```
