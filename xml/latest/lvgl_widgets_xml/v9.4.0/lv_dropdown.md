```xml title="lvgl_widgets_xml/v9.4.0/lv_dropdown.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/lvgl_widgets_xml/v9.4.0/lv_dropdown.xml"
<!--
Example
<lv_dropdown options="option1\noption2" dir="left">
    <lv_dropdown-list style="red"/>
</lv_dropdown>
-->

<widget>
    <api>
        <prop name="text" type="string" help="Set text displayed instead of the selected option label"/>
        <prop name="options" type="string" help="Set options as a newline (`\n`) separated string"/>
        <prop name="selected" type="int" help="Select an option by index (0-based)"/>
        <prop name="symbol" type="string" help="Set a symbol shown next to the dropdown"/>
        <prop name="bind_value" type="subject" help="Bind the selected option index to a subject"/>

        <element name="list" access="get" type="lv_obj" help="The dropdown list object for styling or customization"/>
    </api>
</widget>
```
