```xml title="examples/lvgl_open/screens/widgets/keyboard/lv_example_keyboard_popovers.xml" source="https://github.com/lvgl/lvgl_pro/blob/9bccbd4302cf1f425d2a9790d8b6133170e81650/examples/lvgl_open/screens/widgets/keyboard/lv_example_keyboard_popovers.xml"
<!--
 @title Keyboard pop-overs
 @brief Enlarged preview balloons appear above the pressed key while held.

 With `popovers="true"` LVGL renders a larger preview of the active key
 above the keyboard while it's pressed, the same way mobile OS keyboards do.
 The preview only renders for keys that produce a symbol (so space and
 modifier keys stay quiet). Pop-overs in the top row can extend outside the
 keyboard's bounds — leave free space above it (here the textarea provides
 that headroom).
-->
<screen>
	<view>
		<!-- 💡 Hold any letter key and watch the magnified pop-over appear above. -->
		<lv_textarea
			name="textarea"
			align="top_mid"
			y="10"
			width="90%"
			one_line="true"
			placeholder_text="Press and hold a key"
		/>

		<lv_keyboard name="keyboard" align="bottom_mid" width="100%" height="60%" mode="text_lower" popovers="true" />
	</view>
</screen>
```
