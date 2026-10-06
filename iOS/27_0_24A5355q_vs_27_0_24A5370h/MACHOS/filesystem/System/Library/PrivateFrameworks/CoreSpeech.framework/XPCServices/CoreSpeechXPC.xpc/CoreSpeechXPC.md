## CoreSpeechXPC

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/XPCServices/CoreSpeechXPC.xpc/CoreSpeechXPC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1b8` | `0xe284` | **`+0xcc`** |
| `__DATA_CONST.__cfstring` | `0x1120` | `0x11c0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x202d` | `0x209d` | **`+0x70`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.64.114.1.5
+3600.70.8.0.0

-  CStrings:  892
+  CStrings:  897
Functions:
~ sub_100003124 : 2964 -> 2960
~ sub_100003d68 -> sub_100003d64 : 1812 -> 1804
~ sub_10000458c -> sub_100004580 : 1732 -> 1724
~ sub_100005060 -> sub_10000504c : 1024 -> 1016
~ sub_1000054cc -> sub_1000054b0 : 464 -> 460
~ sub_10000569c -> sub_10000567c : 660 -> 652
~ sub_100006064 -> sub_10000603c : 580 -> 576
~ sub_100009060 -> sub_100009034 : 604 -> 600
~ sub_10000a27c -> sub_10000a24c : 1328 -> 1320
~ sub_10000a858 -> sub_10000a820 : 452 -> 448
~ sub_10000b66c -> sub_10000b630 : 584 -> 572
~ sub_10000ca34 -> sub_10000c9ec : 872 -> 868
~ sub_10000d634 -> sub_10000d5e8 : 644 -> 636
~ sub_10000dc10 -> sub_10000dbbc : 516 -> 512
~ sub_10000ef2c -> sub_10000eed4 : 664 -> 660
~ sub_10000f1c4 -> sub_10000f168 : 556 -> 852
CStrings:
+ "Invalid config for Ures at %@ (failureTarget: %@): %@"
+ "SLUresConfigDict"
+ "SLUresConfigFailureTarget"
+ "SLUresConfigPath"
+ "configLoadFailed"
+ "unknown"
- "Missing config for Ures %@"
```
