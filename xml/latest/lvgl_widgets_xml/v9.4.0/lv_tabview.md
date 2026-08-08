```xml title="lvgl_widgets_xml/v9.4.0/lv_tabview.xml" source="https://github.com/lvgl/lvgl_pro/blob/3514c1eb6b7075d42b1ef8bd36931a525c3d56f3/lvgl_widgets_xml/v9.4.0/lv_tabview.xml"
<!--
Example
<lv_tabview active="3">
    <lv_tabview-tab text="First">
        <lv_button/>
    </lv_tabview-tab>
</lv_tabview>
 -->

<widget>
    <api>
        <prop name="active" type="int" help="Set active tab index (0-based)"/>
        <prop name="tab_bar_position" type="enum:lv_dir" help="Set tab bar position (top, bottom, left, right)"/>

        <element name="tab_bar" type="lv_obj" access="get" help="Get the tab bar object"/>

        <element name="tab" type="lv_obj" access="add" help="Add a tab with content">
            <arg name="text" type="string" help="Set tab button text"/>
        </element>

        <element name="tab_button" type="lv_obj" access="get" help="Get a specific tab button">
            <arg name="index" type="int" help="Tab index (0-based)"/>
        </element>
    </api>
</widget>
```
