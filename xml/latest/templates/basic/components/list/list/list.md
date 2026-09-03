```xml title="templates/basic/components/list/list/list.xml" source="https://github.com/lvgl/lvgl_pro/blob/6d04ae8c667ee14d83198e659f3f199a1cc99fec/templates/basic/components/list/list/list.xml"
<component>
	<previews>
		<preview name="default" width="320" />
	</previews>

	<api>
		<prop name="pad" type="int" default="0" help="Inner padding around the rows (0 keeps rows full-width)" />
		<prop
			name="grow"
			type="int"
			default="0"
			help="flex_grow when placed in a flex row/column; NULL = natural size"
		/>
	</api>

	<!-- A panel that stacks list rows in a column. pad defaults to 0 so rows
	     and dividers span full width (each row brings its own padding).
	     Drop list_section / list_item / list_separator children in. -->
	<view extends="panel" pad="$pad" gap="0" grow="$grow" width="200" />
</component>
```
