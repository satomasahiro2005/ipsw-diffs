## AirDropAlertUI

> `/System/Library/PrivateFrameworks/Sharing.framework/PlugIns/AirDropAlertUI.appex/AirDropAlertUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dec` | `0x21d8` | **`+0x3ec`** |
| `__TEXT.__oslogstring` | `0x206` | `0x29c` | **`+0x96`** |
| `__TEXT.__objc_methname` | `0x84c` | `0x89b` | **`+0x4f`** |
| `__DATA.__objc_const` | `0x4e8` | `0x528` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x920` | `0x960` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x2d0` | `0x300` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x178` | `0x190` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x340` | `0x350` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3c` | `0x44` | **`+0x8`** |
| `__TEXT.__const` | `0x48` | `0x50` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2124.10.2.2.2
+2126.10.4.0.0

-  Symbols:   73
-  CStrings:  191
+  Symbols:   76
+  CStrings:  201
Symbols:
+ __os_signpost_emit_with_name_impl
+ _os_signpost_enabled
+ _os_signpost_id_make_with_pointer
Functions:
~ sub_100000ea0 : 1120 -> 1416
~ sub_100001300 -> sub_100001428 : 76 -> 380
~ sub_100001720 -> sub_100001978 : 184 -> 588
CStrings:
+ " enableTelemetry=YES "
+ "Alert.Decision.Accept"
+ "Alert.Decision.Decline"
+ "Alert.Present"
+ "Alert.UserDecision"
+ "_signpostAlertPresentBegan"
+ "_signpostUserDecisionBegan"
+ "length"
+ "substringToIndex:"
+ "transferID=%{public, signpost.telemetry:string1}@"
```
