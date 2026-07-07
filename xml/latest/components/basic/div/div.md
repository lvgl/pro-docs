```xml title="examples/components/basic/div/div.xml" source="https://github.com/lvgl/lvgl/blob/b3409b2e321d5c66af2223e693fe190f8fad7e38/examples/components/basic/div/div.xml"
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
