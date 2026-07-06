```xml title="examples/components/basic/div/div.xml" source="https://github.com/lvgl/lvgl/blob/3921646e3d7504cf84c88c4328c2b5126b7718ea/examples/components/basic/div/div.xml"
<!-- Mimic the behaviour of a HTML <div>. 100% width, 
     content height, fully transparent, flex colum layout -->
<component>
	<styles>
		<style name="style_main" width="100%" height="content" layout="flex" flex_flow="column" />
	</styles>
	<view>
		<remove_style />
		<style name="style_main" />
	</view>
</component>
```
