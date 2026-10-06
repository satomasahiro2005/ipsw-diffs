## Diagnostic-4615

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4615.appex/Diagnostic-4615`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15a4` | `0x1904` | **`+0x360`** |
| `__TEXT.__auth_stubs` | `0x380` | `0x3e0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x662` | `0x6bf` | **`+0x5d`** |
| `__DATA_CONST.__auth_got` | `0x1c8` | `0x1f8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x212` | `0x22d` | **`+0x1b`** |
| `__TEXT.__cstring` | `0x35` | `0x3f` | **`+0xa`** |
| `__DATA.__objc_selrefs` | `0x210` | `0x218` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x294` | `0x29c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb8` | `0xc0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 48
-  Symbols:   84
-  CStrings:  136
+  Functions: 49
+  Symbols:   90
+  CStrings:  139
Symbols:
+ _IOObjectRetain
+ _IORegistryEntryGetName
+ _IORegistryEntryGetParentEntry
+ _objc_release_x27
+ _objc_retain_x22
+ _strcmp
Functions:
~ sub_100001270 : 16 -> 864
+ sub_1000015d0
CStrings:
+ "@64@0:8@16@24@32@?40@48Q56"
+ "IOService"
+ "getIORegistryClass:property:optionalKey:classValidator:ancestorNameContaining:ancestorDepth:"
```
