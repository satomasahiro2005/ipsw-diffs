## SecuritySettings

> `/System/Library/PreferenceBundles/SecuritySettings.bundle/SecuritySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x780` | `0x7c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x6df` | `0x705` | **`+0x26`** |
| `__TEXT.__auth_stubs` | `0x4b0` | `0x4a0` | **`-0x10`** |
| `__TEXT.__text` | `0x85a4` | `0x85b0` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x268` | `0x260` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1166.0.0.0.0
+1171.0.3.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Symbols:   193
-  CStrings:  624
+  Symbols:   192
+  CStrings:  626
Symbols:
+ _MGGetBoolAnswer
- _objc_retain_x27
- _objc_retain_x28
Functions:
~ sub_389c -> sub_38dc : 1580 -> 1568
~ sub_3f10 -> sub_3f44 : 608 -> 604
~ sub_4194 -> sub_41c4 : 408 -> 404
~ sub_432c -> sub_4358 : 384 -> 380
~ sub_4e18 -> sub_4e40 : 1176 -> 1216
~ sub_772c -> sub_777c : 296 -> 292
CStrings:
+ "DEVICES_PAIR_ALERT_MSG_WIFI"
+ "DEVICES_PAIR_ALERT_MSG_WLAN"
+ "wapi"
- "DEVICES_PAIR_ALERT_MSG"
```
