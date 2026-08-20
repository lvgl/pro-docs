```xml title="tutorials/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/tutorials/project.xml"
<project name="tutorials" lvgl_version="9.5.0" theme="default">
	<targets>
		<target name="target1">
			<display width="480" height="320" />
			<memory name="int_ram" size="1MB" />
			<memory name="int_flash" size="2MB" bandwidth="100MB/s" />
		</target>
	</targets>
</project>
```
