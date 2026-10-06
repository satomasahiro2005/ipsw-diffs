## healthd

> `/System/Library/Frameworks/HealthKit.framework/healthd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x310` | `0x360` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x112` | `0x146` | **`+0x34`** |
| `__TEXT.__objc_stubs` | `0x1a0` | `0x1c0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x30` | `0x38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Symbols:   27
-  CStrings:  21
+  Symbols:   28
+  CStrings:  22
Symbols:
+ _OBJC_CLASS_$_NSNotificationCenter
Functions:
~ sub_100000918 : 696 -> 776
CStrings:
+ "defaultCenter"
+ "initWithContainerDirectoryPath:notificationCenter:"
+ "initWithHealthDirectoryPath:medicalIDDirectoryPath:notificationCenter:"
- "initWithContainerDirectoryPath:"
- "initWithHealthDirectoryPath:medicalIDDirectoryPath:"
```
