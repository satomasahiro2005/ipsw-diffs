## HomeKitDiagnosticExtension

> `/System/Library/Frameworks/HomeKit.framework/PlugIns/HomeKitDiagnosticExtension.appex/HomeKitDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24620` | `0x2465c` | **`+0x3c`** |
| `__TEXT.__objc_stubs` | `0x3a20` | `0x3a40` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x3e9a` | `0x3ead` | **`+0x13`** |
| `__TEXT.__auth_stubs` | `0x990` | `0x980` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x12d8` | `0x12e0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x4d8` | `0x4d0` | **`-0x8`** |

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
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1468.5.0.0.6
+1479.0.0.1.0

-  Symbols:   301
-  CStrings:  1598
+  Symbols:   300
+  CStrings:  1599
Symbols:
- _objc_retain_x27
Functions:
~ sub_1000023e4 : 580 -> 576
~ sub_1000029e4 -> sub_1000029e0 : 580 -> 576
~ sub_100003734 -> sub_10000372c : 500 -> 496
~ sub_10000816c -> sub_100008160 : 720 -> 716
~ sub_10000a7f8 -> sub_10000a7e8 : 4928 -> 4920
~ sub_10000c1a0 -> sub_10000c188 : 2132 -> 2144
~ sub_10000f598 -> sub_10000f58c : 1732 -> 1728
~ sub_100010240 -> sub_100010230 : 784 -> 804
~ sub_100010558 -> sub_10001055c : 2584 -> 2580
~ sub_100010f70 : 860 -> 856
~ sub_100011a04 -> sub_100011a00 : 468 -> 464
~ sub_100011de0 -> sub_100011dd8 : 2088 -> 2084
~ sub_10001d228 -> sub_10001d21c : 1376 -> 1372
~ sub_10001daa4 -> sub_10001da94 : 1836 -> 1832
~ sub_10001e1d0 -> sub_10001e1bc : 7788 -> 7804
~ sub_100020ea8 -> sub_100020ea4 : 4432 -> 4444
~ sub_100022860 -> sub_100022868 : 5544 -> 5596
CStrings:
+ "setFetchBatchSize:"
```
