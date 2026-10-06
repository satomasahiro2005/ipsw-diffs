## adc-rheia-d9x.im4p

> `Firmware/isp_bni/adc-rheia-d9x.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaa2384` | `0xaa1bc4` | **`-0x7c0`** |
| `__DATA.__zerofill` | `0x5b23f8` | `0x5b24f8` | **`+0x100`** |
| `__TEXT.__const` | `0x9cb988` | `0x9cba40` | **`+0xb8`** |
| `__TEXT.__cstring` | `0xa7e88` | `0xa7f15` | **`+0x8d`** |
| `__DATA.__const` | `0x557b0` | `0x557c0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA._rtk_smp_main`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-  CStrings:  18341
+  CStrings:  18343
CStrings:
+ "23:41:57"
+ "TMH9: isSifrOn %u SifrFrame %p sifrSkipRatio %u\n"
+ "TMH9:ch %d (#%d, %f) ch#InSync %d, tag 0x%x, preB %d, Bra %d (%d), f %d %d prj %d, bCap %u\n"
- "20:45:16"
```
