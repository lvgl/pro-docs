```xml title="lvgl_widgets_xml/v9.4.0/lv_spinbox.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/lvgl_widgets_xml/v9.4.0/lv_spinbox.xml"
<!--
Example
<lv_spinbox digit_count="5" dec_point_pos="3" value="12345"/>
 -->

<widget>
	<api>
        <prop name="value" type="int"/>
        <prop name="rollover" type="bool"/>
        <prop name="digit_count" type="int"/>
        <prop name="dec_point_pos" type="int"/>
        <prop name="min_value" type="int"/>
        <prop name="max_value" type="int"/>
        <prop name="step" type="int"/>
        <prop name="bind_value" type="subject" help="Connect a subject to the spinbox's value"/>
	</api>
</widget>
```
