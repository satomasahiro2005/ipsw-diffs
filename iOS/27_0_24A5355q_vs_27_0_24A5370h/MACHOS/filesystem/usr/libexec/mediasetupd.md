## mediasetupd

> `/usr/libexec/mediasetupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f0fc` | `0x2f094` | **`-0x68`** |
| `__TEXT.__objc_methname` | `0x6b50` | `0x6b9e` | **`+0x4e`** |
| `__TEXT.__objc_methtype` | `0x12f6` | `0x1313` | **`+0x1d`** |
| `__TEXT.__objc_methlist` | `0x1fc4` | `0x1fdc` | **`+0x18`** |
| `__DATA.__objc_const` | `0x30f8` | `0x3108` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1bc8` | `0x1bd8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  1963
+  CStrings:  1966
Functions:
~ sub_100002444 : 172 -> 168
~ sub_100002570 -> sub_10000256c : 144 -> 140
~ sub_100002828 -> sub_100002820 : 84 -> 80
~ sub_1000043b8 -> sub_1000043ac : 968 -> 964
~ sub_100005ad4 -> sub_100005ac4 : 1464 -> 1460
~ sub_100006a60 -> sub_100006a4c : 1216 -> 1204
~ sub_10000a060 -> sub_10000a040 : 1172 -> 1168
~ sub_10000c4a0 -> sub_10000c47c : 340 -> 336
~ sub_10000deec -> sub_10000dec4 : 464 -> 460
~ sub_10000fec8 -> sub_10000fe9c : 772 -> 768
~ sub_100014704 -> sub_1000146d4 : 1656 -> 1652
~ sub_100017154 -> sub_100017120 : 540 -> 536
~ sub_100018304 -> sub_1000182cc : 880 -> 876
~ sub_1000189cc -> sub_100018990 : 1376 -> 1372
~ sub_10001dd20 -> sub_10001dce0 : 740 -> 736
~ sub_10001e16c -> sub_10001e128 : 488 -> 484
~ sub_1000215f0 -> sub_1000215a8 : 256 -> 252
~ sub_100022398 -> sub_10002234c : 776 -> 772
~ sub_1000226a8 -> sub_100022658 : 888 -> 884
~ sub_100025bfc -> sub_100025ba8 : 1780 -> 1776
~ sub_100026a30 -> sub_1000269d8 : 676 -> 672
~ sub_1000278cc -> sub_100027870 : 632 -> 628
~ sub_100027bd8 -> sub_100027b78 : 1388 -> 1392
~ sub_10002a114 -> sub_10002a0b8 : 1632 -> 1624
~ sub_10002ceb8 -> sub_10002ce54 : 432 -> 428
CStrings:
+ "home:didUpdateClipCaptionLocales:"
+ "home:didUpdateClipCaptioningEnabledCameras:"
+ "v32@0:8@\"HMHome\"16@\"NSSet\"24"
```
