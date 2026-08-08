```xml title="lvgl_widgets_xml/v9.5.0/lv_spinner.xml" source="https://github.com/lvgl/lvgl_pro/blob/4d05fc79f26b1a8daf2c0134018f3d07c6f19286/lvgl_widgets_xml/v9.5.0/lv_spinner.xml"
<!--
Example
<lv_spinner anim_duration="1500" arc_sweep="90"/>
 -->

<widget>
    <api>
        <prop name="anim_duration" type="int" help="Set the animation time of the spinner."/>
        <prop name="arc_sweep" type="int" help="Set the animation arc length of the spinner. The animation is suited to values between 180 and 360."/>

        <parts>
            <part name="main" help="The background arc (extends lv_arc): `arc_color`, `arc_width`, `arc_opa`, `arc_rounded`."/>
            <part name="indicator" help="The spinning arc that animates around: the arc_* properties."/>
        </parts>
    </api>
</widget>
```
