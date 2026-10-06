## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85e20` | `0x86914` | **`+0xaf4`** |
| `__TEXT.__cstring` | `0x2809a` | `0x2837c` | **`+0x2e2`** |
| `__TEXT.__const` | `0x22ab8` | `0x22a08` | **`-0xb0`** |
| `__TEXT.__unwind_info` | `0x668` | `0x670` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-913.8.0.0.0
+913.29.1.0.0

-  CStrings:  3412
+  CStrings:  3427
Functions:
~ sub_3320 : 6584 -> 7052
~ sub_1ca00 -> sub_1cbd4 : 2780 -> 2772
~ sub_302b8 -> sub_30484 : 1136 -> 1152
~ sub_31598 -> sub_31774 : 5320 -> 5300
~ sub_341b0 -> sub_34378 : 968 -> 984
~ sub_34c40 -> sub_34e18 : 8100 -> 8704
~ sub_38f00 -> sub_39334 : 4036 -> 4040
~ sub_3dda4 -> sub_3e1dc : 28220 -> 29256
~ sub_44f78 -> sub_457bc : 11284 -> 11420
~ sub_494a0 -> sub_49d6c : 7756 -> 7784
~ sub_50bf0 -> sub_514d8 : 1592 -> 1596
~ sub_5123c -> sub_51b28 : 136 -> 492
~ sub_51e28 -> sub_52878 : 264 -> 428
CStrings:
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %d %lld"
+ "%lld %d AVE %s: %s:%d %s | size overflow %d %d %d %d %lld\n"
+ "%lld %d AVE %s: %s::%s:%d  ps[%d] aveType=%d layerID=%d size=%d byte0=0x%02x byte1=0x%02x hevcNalType=%d"
+ "%lld %d AVE %s: %s::%s:%d  ps[%d] aveType=%d layerID=%d size=%d byte0=0x%02x byte1=0x%02x hevcNalType=%d\n"
+ "%lld %d AVE %s: %s::%s:%d VTEncoderSessionCreateVideoFormatDescription failed res=%d; dumping %d HEVC NAL units"
+ "%lld %d AVE %s: %s::%s:%d VTEncoderSessionCreateVideoFormatDescription failed res=%d; dumping %d HEVC NAL units\n"
+ "%s%d"
+ "%s%s:%d:%d"
+ ","
+ "21:39:53"
+ "913.29.1"
+ "AVE_CalcBufSizeOfMBInputCtrl"
+ "AuxiliaryLayerProperties = "
+ "EncodesAuxiliaryWithAuxID = %d\n"
+ "HEVCAuxiliaryIDs = "
+ "HEVCAuxiliaryLayerIDs = "
+ "Jul 14 2026"
+ "size >= 0 && size <= 2147483647"
- "21:23:03"
- "913.8.0"
- "Jun 29 2026"
```
