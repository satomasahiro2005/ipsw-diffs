## diskarbitrationd

> `/usr/libexec/diskarbitrationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bc44` | `0x1bcfc` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x338e` | `0x33fe` | **`+0x70`** |
| `__DATA_CONST.__const` | `0xef0` | `0xef8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-593.0.0.0.1
+597.0.0.0.0

-  CStrings:  702
+  CStrings:  704
Functions:
~ sub_100003674 : 264 -> 268
~ sub_100003ab0 -> sub_100003ab4 : 436 -> 452
~ sub_100003f24 -> sub_100003f38 : 352 -> 344
~ sub_100004084 -> sub_100004090 : 280 -> 284
~ sub_100004900 -> sub_100004910 : 1004 -> 1008
~ sub_1000097a8 -> sub_1000097bc : 252 -> 264
~ sub_10000a658 -> sub_10000a678 : 676 -> 692
~ sub_10000d7b8 -> sub_10000d7e8 : 1112 -> 1176
~ sub_10000e634 -> sub_10000e6a4 : 468 -> 500
~ sub_100011abc -> sub_100011b4c : 864 -> 876
~ sub_100014134 -> sub_1000141d0 : 292 -> 296
~ sub_1000144f8 -> sub_100014598 : 320 -> 332
~ sub_10001579c -> sub_100015848 : 1620 -> 1648
~ sub_100016374 -> sub_10001643c : 396 -> 400
~ sub_100019c48 -> sub_100019d14 : 44 -> 48
~ sub_10001a958 -> sub_10001aa28 : 136 -> 140
~ sub_10001a9e0 -> sub_10001aab4 : 276 -> 272
~ sub_10001afe4 -> sub_10001b0b4 : 1816 -> 1788
~ sub_10001c0e8 -> sub_10001c19c : 584 -> 588
CStrings:
+ "Attempt to use FSKit to mount volume of type %@ when not supported"
+ "diskarbitrationd exited"
+ "eject call of %@ returned (status code 0x%08X)."
+ "mount call of %@ returned (status code 0x%08X)."
+ "unmount call of %@ returned (status code 0x%08X)."
- "unable to eject %@ (status code 0x%08X)."
- "unable to mount %@ (status code 0x%08X)."
- "unable to unmount %@ (status code 0x%08X)."
```
