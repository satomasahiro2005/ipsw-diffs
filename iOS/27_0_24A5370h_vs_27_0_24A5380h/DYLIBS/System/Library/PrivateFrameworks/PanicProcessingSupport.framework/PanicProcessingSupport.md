## PanicProcessingSupport

> `/System/Library/PrivateFrameworks/PanicProcessingSupport.framework/PanicProcessingSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc578` | `0xcb5c` | **`+0x5e4`** |
| `__AUTH_CONST.__cfstring` | `0x2080` | `0x2180` | **`+0x100`** |
| `__TEXT.__cstring` | `0x152a` | `0x15ba` | **`+0x90`** |
| `__DATA_CONST.__objc_arraydata` | `0x148` | `0x170` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x1118` | `0x1138` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x18` | `0x30` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b8` | `0x6d0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2e8` | `0x300` | **`+0x18`** |
| `__DATA.__data` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x81c` | `0x82c` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x4b0` | `0x4b8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x120` | `0x124` | **`+0x4`** |

### Other Changes

```diff

-31.0.0.0.0
+34.0.0.0.0

-  Functions: 265
-  Symbols:   438
-  CStrings:  336
+  Functions: 270
+  Symbols:   440
+  CStrings:  344
Symbols:
+ -[PanicReport useCrashlogContainers:]
+ GCC_except_table41
+ _OBJC_IVAR_$_PanicReport._crashlogContainerArray
- GCC_except_table40
CStrings:
+ "CrashlogContainer"
+ "CrashlogContainers"
+ "chassisID"
+ "ensembleID"
+ "hw.osenvironment"
+ "platformSOCDBuffer"
+ "totalNodeNumber"
+ "totalReportNumber"
+ "unique_crash_event_id"
- "kern.osvariant_status"
```
