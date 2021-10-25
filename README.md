aero-hockey-unity


> Add to your git/config file to reduce merge conflicts
```
[merge "unityyamlmerge"]
	name = Unity SmartMerge (UnityYamlMerge)
	driver = \"{Unity path}/Editor/Data/Tools/UnityYAMLMerge.exe\" merge -h -p --force --fallback none %O %B %A %A
	recursive = binary
```