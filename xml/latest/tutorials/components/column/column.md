```xml title="tutorials/components/column/column.xml" source="https://github.com/lvgl/lvgl_pro/blob/4df91fdef99e5c2f1a8af7bada6de3e7680aef6d/tutorials/components/column/column.xml"
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
