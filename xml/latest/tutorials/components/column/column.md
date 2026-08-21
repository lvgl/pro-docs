```xml title="tutorials/components/column/column.xml" source="https://github.com/lvgl/lvgl_pro/blob/91553dccc827bdbb5d49302579f6a8df95e2db84/tutorials/components/column/column.xml"
<!-- Just place the children below each other.
     The container's size will be according to the content -->
<component>
	<styles>
		<style name="style_base" width="content" height="content" layout="flex" flex_flow="column" />
	</styles>
	<view>
		<remove_style_all />
		<style name="style_base" />
	</view>
</component>
```
