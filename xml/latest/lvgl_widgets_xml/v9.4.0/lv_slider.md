```xml title="lvgl_widgets_xml/v9.4.0/lv_slider.xml" source="https://github.com/lvgl/lvgl_pro/blob/3514c1eb6b7075d42b1ef8bd36931a525c3d56f3/lvgl_widgets_xml/v9.4.0/lv_slider.xml"
<!--
Example
<lv_slider mode="range" value="30"/>
 -->

<widget>
    <api>
        <enumdef name="lv_slider_mode" help="How the slider behaves">
            <enum name="normal" help="One knob, grows left to right"/>
            <enum name="range" help="Two knobs, select a range"/>
            <enum name="symmetrical" help="Indicator grows from zero"/>
        </enumdef>

        <prop name="min_value" type="int" help="Set minimum value"/>
        <prop name="max_value" type="int" help="Set maximum value"/>

        <prop name="value" help="Set current value">
            <param name="value" type="int" help="Current value"/>
            <param name="anim" type="bool" default="false" help="Animate update (reference as `value-anim`)"/>
        </prop>

        <prop name="start_value" help="Set start value in range mode">
            <param name="start_value" type="int" help="Start value"/>
            <param name="anim" type="bool" default="false" help="Animate update (reference as `start_value-anim`)"/>
        </prop>

        <prop name="mode" type="enum:lv_slider_mode" help="Set slider mode"/>
        <prop name="bind_value" type="subject" help="Bind value to subject"/>
    </api>
</widget>
```
