```xml title="templates/basic/components/layout/base_box/base_box.xml" source="https://github.com/lvgl/lvgl_pro/blob/9bccbd4302cf1f425d2a9790d8b6133170e81650/templates/basic/components/layout/base_box/base_box.xml"
<component>
	<!-- INTERNAL — use `container`/`panel` instead. The one place
	     <remove_style_all/> runs, so the screen's bound text_color can
	     inherit down. Kept separate so extenders' locals apply AFTER the
	     wipe (same-view locals would be erased by it). -->
	<styles>
		<!-- Transparent + flex; hugs content until a size is set. -->
		<style name="style_base_box" width="content" height="content" layout="flex" flex_flow="column" />
	</styles>

	<view extends="lv_obj">
		<remove_style_all />
		<style name="style_base_box" />
		<style name="style_scrollbar" selector="scrollbar" />
	</view>
</component>
```
