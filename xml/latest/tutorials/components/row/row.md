```xml title="tutorials/components/row/row.xml" source="https://github.com/lvgl/lvgl_pro/blob/9bccbd4302cf1f425d2a9790d8b6133170e81650/tutorials/components/row/row.xml"
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
