```xml title="lvgl_widgets_xml/v9.5.0/lv_line.xml" source="https://github.com/lvgl/lvgl_pro/blob/3514c1eb6b7075d42b1ef8bd36931a525c3d56f3/lvgl_widgets_xml/v9.5.0/lv_line.xml"
<!--
Example
<lv_line points="(10 20) (60 40) (20, 60)"/>
-->

<widget>
    <api>
        <prop name="y_invert" type="bool" help="If true the y=0 of points will be at the bottom of the widget" />
        <prop name="points" type="precise_points[count]" help="Set the points of the line. E.g. (10 20) (30 40)"/>

        <parts>
            <part name="main" help="Style the line: `line_width`, `line_color`, `line_opa`, `line_rounded` and `line_dash_width`/`line_dash_gap`. Background can be added too."/>
        </parts>
    </api>
</widget>
```
