## ProgressUI

> `/System/Library/PrivateFrameworks/ProgressUI.framework/ProgressUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x325c` | `0x3470` | **`+0x214`** |
| `__TEXT.__cstring` | `0x99e` | `0xa53` | **`+0xb5`** |
| `__AUTH_CONST.__cfstring` | `0x640` | `0x6a0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x41c` | `0x434` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x448` | `0x458` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 58
-  Symbols:   274
-  CStrings:  88
+  Functions: 60
+  Symbols:   284
+  CStrings:  92
Symbols:
+ -[PUIProgressWindow _copyDisplayBootRotationNumberFromIORegistry]
+ -[PUIProgressWindow _isV68Device]
+ GCC_except_table20
+ _CFDataGetBytePtr
+ _CFDataGetLength
+ _CFDataGetTypeID
+ _CFGetTypeID
+ _IOObjectRelease
+ _IORegistryEntryCreateCFProperty
+ _IORegistryEntryFromPath
+ _kIOMainPortDefault
- GCC_except_table18
CStrings:
+ "IODeviceTree:/product/display1"
+ "PUIProgressWindow ignoring unrecognized IORegistry boot rotation %@"
+ "PUIProgressWindow using IORegistry display boot rotation %@"
+ "display-boot-rotation"
```
