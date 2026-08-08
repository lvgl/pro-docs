```xml title="lvgl_widgets_xml/v9.4.0/lv_spangroup.xml" source="https://github.com/lvgl/lvgl_pro/blob/3514c1eb6b7075d42b1ef8bd36931a525c3d56f3/lvgl_widgets_xml/v9.4.0/lv_spangroup.xml"
<!--
Example
<lv_spangroup width="300" height="content">
    <lv_spangroup-span text="hello " style="red"/>
    <lv_spangroup-span text="world" style="blue"/>
</lv_spangroup>
-->

<widget>
    <api>
        <enumdef name="lv_span_overflow" help="How to handle overflowing text">
            <enum name="clip" help="Clip at boundary"/>
            <enum name="ellipsis" help="Replace overflowing words with ..."/>
        </enumdef>

        <prop name="overflow" type="enum:lv_span_overflow" help="Set overflow mode"/>
        <prop name="max_lines" type="int" help="Set max lines"/>
        <prop name="indent" type="int" help="Set first line indent (px)"/>

        <element name="span" type="lv_span" access="add" help="Add a styled text span">
            <prop name="text" type="string" help="Set span text"/>
            <prop name="style" type="style" help="Set span style"/>
            <prop name="bind_text" help="Bind text to a subject">
                <param name="bind_text" type="subject" help="Subject that provides text"/>
                <param name="fmt" type="string" default="NULL" help="Format string (printf style)"/>
            </prop>
        </element>
    </api>
</widget>
```
