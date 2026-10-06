## PSVR2HIDServicePlugin

> `/System/Library/HIDPlugins/ServicePlugins/PSVR2HIDServicePlugin.plugin/PSVR2HIDServicePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4884` | `0x4954` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x936` | `0x963` | **`+0x2d`** |
| `__TEXT.__auth_stubs` | `0x6f0` | `0x700` | **`+0x10`** |
| `__TEXT.__const` | `0x50` | `0x60` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x388` | `0x390` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-14.0.17.0.0
+14.0.19.0.0

-  Symbols:   140
-  CStrings:  283
+  Symbols:   141
+  CStrings:  284
Symbols:
+ _IOObjectCopyClass
Functions:
~ sub_e20 : 184 -> 392
~ sub_ed8 -> sub_fa8 : 1000 -> 68
~ sub_12c0 -> sub_fec : 68 -> 1000
~ sub_4f50 -> sub_5020 : 60 -> 20
~ sub_4fc8 -> sub_5070 : 52 -> 60
~ sub_5030 -> sub_50e0 : 140 -> 52
~ sub_5148 -> sub_51a0 : 116 -> 140
~ sub_51bc -> sub_522c : 52 -> 116
~ sub_528c -> sub_533c : 20 -> 52
CStrings:
+ "%{public}@ probe <%{public}@ %#010llx> (%zi)"
```
