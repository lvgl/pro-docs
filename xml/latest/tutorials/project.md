```xml title="tutorials/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/6d04ae8c667ee14d83198e659f3f199a1cc99fec/tutorials/project.xml"
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
