## AppConduit

> `/System/Library/PrivateFrameworks/AppConduit.framework/AppConduit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e01c` | `0x1e4e8` | **`+0x4cc`** |
| `__TEXT.__cstring` | `0x633e` | `0x63da` | **`+0x9c`** |
| `__TEXT.__objc_methlist` | `0x14a4` | `0x14c4` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xfe0` | `0xff0` | **`+0x10`** |

### Other Changes

```diff

-408.0.0.0.0
+408.2.1.0.0

-  Functions: 571
-  Symbols:   1103
-  CStrings:  541
+  Functions: 573
+  Symbols:   1106
+  CStrings:  543
Symbols:
+ +[ACXApplication _URLOfFirstItemWithExtension:inDirectory:]
+ +[ACXApplication _URLsOfExtensionsInBundleURL:mayNotExist:]
+ +[ACXApplication _architectureSlicesForWatchKitAppURL:infoPlist:isPlaceholder:pluginInfoPlists:]
+ +[ACXApplication _infoPlistForPluginBundle:]
+ +[ACXApplication _mostCurrentWKAppURLInCompanionAppRecord:isPlaceholder:]
+ +[ACXApplication _parseArchitectureSlicesForWatchKitAppExecutableURL:]
+ +[ACXApplication architectureSlicesForCompanionAppRecord:]
+ GCC_except_table22
+ ___44+[ACXApplication _infoPlistForPluginBundle:]_block_invoke
+ ___70+[ACXApplication _parseArchitectureSlicesForWatchKitAppExecutableURL:]_block_invoke
+ _objc_retain_x27
- -[ACXApplication _URLOfFirstItemWithExtension:inDirectory:]
- -[ACXApplication _URLsOfExtensionsInBundleURL:mayNotExist:]
- -[ACXApplication _infoPlistForPluginBundle:]
- -[ACXApplication _mostCurrentWKAppURLInCompanionAppRecord:isPlaceholder:]
- -[ACXApplication _parseArchitectureSlicesForWatchKitAppExecutableURL:]
- GCC_except_table19
- ___44-[ACXApplication _infoPlistForPluginBundle:]_block_invoke
- ___70-[ACXApplication _parseArchitectureSlicesForWatchKitAppExecutableURL:]_block_invoke
CStrings:
+ "+[ACXApplication _URLsOfExtensionsInBundleURL:mayNotExist:]"
+ "+[ACXApplication _architectureSlicesForWatchKitAppURL:infoPlist:isPlaceholder:pluginInfoPlists:]"
+ "+[ACXApplication _infoPlistForPluginBundle:]"
+ "+[ACXApplication _mostCurrentWKAppURLInCompanionAppRecord:isPlaceholder:]"
+ "+[ACXApplication _parseArchitectureSlicesForWatchKitAppExecutableURL:]"
+ "+[ACXApplication _parseArchitectureSlicesForWatchKitAppExecutableURL:]_block_invoke"
+ "+[ACXApplication architectureSlicesForCompanionAppRecord:]"
- "-[ACXApplication _URLsOfExtensionsInBundleURL:mayNotExist:]"
- "-[ACXApplication _infoPlistForPluginBundle:]"
- "-[ACXApplication _mostCurrentWKAppURLInCompanionAppRecord:isPlaceholder:]"
- "-[ACXApplication _parseArchitectureSlicesForWatchKitAppExecutableURL:]"
- "-[ACXApplication _parseArchitectureSlicesForWatchKitAppExecutableURL:]_block_invoke"
```
