```xml title="tutorials/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/521c6cf8b209faecc21d3ffcf59fede7cb5d01c2/tutorials/project.xml"
<project name="tutorials" lvgl_version="9.6.0" theme="default">
	<targets>
		<target name="target1">
			<display width="480" height="320" />
			<memory name="int_ram" size="1MB" />
			<memory name="int_flash" size="2MB" bandwidth="100MB/s" />
		</target>
	</targets>
</project>
```
