```xml title="lvgl_widgets_xml/v9.4.0/lv_textarea.xml" source="https://github.com/lvgl/lvgl_pro/blob/9bccbd4302cf1f425d2a9790d8b6133170e81650/lvgl_widgets_xml/v9.4.0/lv_textarea.xml"
<!--
Example
<lv_textarea text="Hello"/>
-->

<widget>
    <api>
        <prop name="text" type="string" help="Set textarea text"/>
        <prop name="placeholder_text" type="string" help="Set placeholder text"/>
        <prop name="one_line" type="bool" help="Enable single-line mode"/>
        <prop name="password_mode" type="bool" help="Enable password masking"/>
        <prop name="password_show_time" type="int" help="Set delay to show typed chars (ms)"/>
        <prop name="text_selection" type="bool" help="Enable text selection"/>
        <prop name="cursor_pos" type="int" help="Set cursor position (0-based)"/>
    </api>
</widget>
```
