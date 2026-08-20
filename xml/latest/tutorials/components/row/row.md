```xml title="tutorials/components/row/row.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/tutorials/components/row/row.xml"
<!-- Just place the children next to each other.
     The container's size will be according to the content -->
<component>
	<styles>
		<style name="style_base" width="content" height="content" layout="flex" flex_flow="row" />
	</styles>
	<view>
		<remove_style_all />
		<style name="style_base" />
	</view>
</component>
```
