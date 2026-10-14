## TactSwitchHIDServiceFilter

> `/System/Library/HIDPlugins/ServiceFilters/TactSwitchHIDServiceFilter.plugin/TactSwitchHIDServiceFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methtype` | `0x65a` | `0x6b5` | **`+0x5b`** |
| `__TEXT.__text` | `0x2bf0` | `0x2c3c` | **`+0x4c`** |
| `__TEXT.__objc_methname` | `0x9a8` | `0x9ea` | **`+0x42`** |
| `__DATA.__objc_const` | `0x928` | `0x930` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x488` | `0x490` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-10110.3.0.0.0
+10110.4.0.0.0

-  Functions: 71
-  Symbols:   277
-  CStrings:  272
+  Functions: 72
+  Symbols:   278
+  CStrings:  275
Symbols:
+ __ZN14SABinaryWriter5writeEPKvm
Functions:
~ ___53-[TouchSensitiveButtonHIDService handleResetRequest:]_block_invoke : 304 -> 308
~ __ZN14SABinaryWriter15initHostRequestEhtPKv : 240 -> 168
+ __ZN14SABinaryWriter5writeEPKvm
CStrings:
+ "@56@0:8Q16Q24Q32@\"NSObject<OS_dispatch_queue>\"40@?<v@?@\"NSData\">48"
+ "@56@0:8Q16Q24Q32@40@?48"
+ "initWithStreamSize:platformId:personalityId:queue:streamCallback:"
```
