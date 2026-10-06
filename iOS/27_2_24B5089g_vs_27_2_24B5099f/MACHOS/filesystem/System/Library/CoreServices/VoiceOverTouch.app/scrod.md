## scrod

> `/System/Library/CoreServices/VoiceOverTouch.app/scrod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbc94` | `0xbecc` | **`+0x238`** |
| `__TEXT.__objc_methname` | `0x1c0a` | `0x1c6e` | **`+0x64`** |
| `__TEXT.__objc_stubs` | `0x1a20` | `0x1a80` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x310` | `0x330` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x8b8` | `0x8d0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x858` | `0x868` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x3d9` | `0x3e7` | **`+0xe`** |
| `__TEXT.__unwind_info` | `0x318` | `0x320` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-330.1.1.0.0
+330.1.2.0.0

-  Functions: 160
-  Symbols:   225
-  CStrings:  524
+  Functions: 161
+  Symbols:   229
+  CStrings:  528
Symbols:
+ OBJC_IVAR_$_SCROBrailleDisplay._driverModelIdentifierForAnalytics
+ OBJC_IVAR_$_SCROBrailleDisplay._driverModelIdentifierForPlist
+ _kSCROBrailleDisplayModelIdentifierForAnalytics
+ _kSCROBrailleDisplayModelIdentifierForPlist
CStrings:
+ "_setCachedModelIdentifierForPlist:forAnalytics:"
+ "modelIdentifierForAnalytics"
+ "modelIdentifierForPlist"
+ "v32@0:8@16@24"
```
