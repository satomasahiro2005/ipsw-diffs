## AppleAVE2FW_H17.im4p

> `Firmware/ave/AppleAVE2FW_H17.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x114044` | `0x1140b4` | **`+0x70`** |
| `__TEXT.__cstring` | `0x17e51` | `0x17e6f` | **`+0x1e`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`

### Other Changes

```diff

-  CStrings:  2713
+  CStrings:  2714
Functions:
~ __ZN15CMCTFController20LowLatencyCopyOutputEP14MCTF_FrameInfoP18AVE_PICMGMT_PARAMSb : 236 -> 344
~ __Z20AVE_IOP_Config_pandav : 488 -> 484
~ _exp2f : 168 -> 176
CStrings:
+ "9013.45.2"
+ "Applying gating for frame: %d"
- "9013.45.1"
```
