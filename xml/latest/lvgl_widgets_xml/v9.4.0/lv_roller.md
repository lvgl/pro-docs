```xml title="lvgl_widgets_xml/v9.4.0/lv_roller.xml" source="https://github.com/lvgl/lvgl_pro/blob/4d05fc79f26b1a8daf2c0134018f3d07c6f19286/lvgl_widgets_xml/v9.4.0/lv_roller.xml"
<!--
Example
<lv_roller options="'a\nb\nc\nd' infinite" selected="2 true" visible_row_count="3"/>
 -->

<widget>
    <api>
        <enumdef name="lv_roller_mode" help="How the roller scrolls">
            <enum name="normal" help="Stop at first and last option"/>
            <enum name="infinite" help="Scroll endlessly in a loop"/>
        </enumdef>

        <prop name="options" help="Set the roller options">
            <param name="options" type="string" help="Options as a newline (`\n`) separated string"/>
            <param name="mode" type="enum:lv_roller_mode" default="normal" help="Set the roller mode (reference as `options-mode`)"/>
        </prop>

        <prop name="selected" help="Set the selected option">
            <param name="selected" type="int" help="Index of the selected option (0-based)"/>
            <param name="animated" type="bool" default="false" help="Animate the selection (reference as `selected-animated`)"/>
        </prop>

        <prop name="visible_row_count" type="int" help="Show this many rows at once"/>
        <prop name="bind_value" type="subject" help="Bind the selected option to a subject"/>
    </api>
</widget>
```
