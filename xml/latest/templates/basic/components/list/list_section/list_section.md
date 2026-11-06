```xml title="templates/basic/components/list/list_section/list_section.xml" source="https://github.com/lvgl/lvgl_pro/blob/53167c734579376c91628025f7806b34b521508c/templates/basic/components/list/list_section/list_section.xml"
<component>
	<previews>
		<preview name="default" width="320" />
	</previews>

	<api>
		<prop name="text" type="string" default="Section" help="Section header text" />
	</api>

	<styles>
		<style
			name="style_list_section"
			text_font="font_body"
			text_opa="50%"
			pad_hor="{space_md}"
			pad_top="{space_md}"
			pad_bottom="{space_xs}"
		/>
	</styles>

	<!-- A small, muted section header to group rows in a list. It is a plain
	     label (inherits the theme text color, then dims it via opacity) with
	     padding so it lines up with the rows above/below. -->
	<view extends="lv_label" text="{text}" width="100%">
		<style name="style_list_section" />
	</view>
</component>
```
