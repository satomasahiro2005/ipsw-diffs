## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34c988` | `0x34ca7c` | **`+0xf4`** |
| `__DATA_CONST.__cfstring` | `0xd620` | `0xd6a0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x4044` | `0x4084` | **`+0x40`** |
| `__TEXT.__cstring` | `0xf13f` | `0xf17e` | **`+0x3f`** |
| `__DATA.__objc_const` | `0x1900` | `0x1930` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x3240` | `0x3260` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x112c` | `0x113c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x10c0` | `0x10c8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1258` | `0x1250` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xfc` | `0x100` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-1145.40.5.502.1
+1145.40.5.0.4

-  Functions: 1664
-  Symbols:   4063
-  CStrings:  3081
+  Functions: 1666
+  Symbols:   4067
+  CStrings:  3088
Symbols:
+ -[DeviceType is_home_accessory]
+ OBJC_IVAR_$_DeviceType._is_home_accessory
+ _is_home_accessory
+ _objc_msgSend$is_home_accessory
Functions:
~ -[DeviceType init] : 2212 -> 2232
+ -[DeviceType ucrt_enforced]
+ _has_internal_diagnostics
~ _producttype_supports_missing_emac : 8 -> 128
~ _device_supports_missing_emac : 40 -> 64
CStrings:
+ "1145.40.5.0.4"
+ "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.40.5.0.4 built on Oct  3 2026 at 22:24:14)"
+ "AudioAccessory11,1"
+ "HomeAccessory"
+ "HomeAccessory17,1"
+ "HomeAccessory17,2"
+ "TB,R,N,V_is_home_accessory"
+ "_is_home_accessory"
+ "iOS Device Activator (MobileActivation-1145.40.5.0.4)"
+ "is_home_accessory"
- "1145.40.5.502.1"
- "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.40.5.502.1 built on Sep 28 2026 at 21:08:25)"
- "iOS Device Activator (MobileActivation-1145.40.5.502.1)"
```
