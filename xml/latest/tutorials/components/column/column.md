```xml title="tutorials/components/column/column.xml" source="https://github.com/lvgl/lvgl_pro/blob/6a64e6a851619119c359a5ae0ca6e8091732a70c/tutorials/components/column/column.xml"
<!-- Just place the children below each other.
     The container's size will be according to the content -->
<component>
	<styles>
		<style
			name="style_base"
			width="content"
			height="content"
			layout="flex"
			flex_flow="column"
		/>
	</styles>
	<view>
		<remove_style_all />
		<style name="style_base" />
	</view>
</component>
```
