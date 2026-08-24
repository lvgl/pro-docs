```xml title="tutorials/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/b50910a3acc7ed2355e2e41eabaca2630a9e383d/tutorials/project.xml"
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
