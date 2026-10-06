## AppleAVE2FW_H17.im4p

> `Firmware/ave/AppleAVE2FW_H17.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x114058` | `0x1143fc` | **`+0x3a4`** |
| `__TEXT.__cstring` | `0x17e6f` | `0x17f25` | **`+0xb6`** |
| `__DATA.__data` | `0x11b8` | `0x11d0` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__TEXT.__const`

### Other Changes

```diff

-  Functions: 1223
-  Symbols:   1712
-  CStrings:  2714
+  Functions: 1225
+  Symbols:   1714
+  CStrings:  2720
Symbols:
+ __ZN11RateControl13updateFixedQPEi
+ __ZN12CRateControl13UpdateFixedQPEi
CStrings:
+ "%s:%d %s | too many parameter sets %d %d %d %p %d"
+ "%s:%s Enter %d"
+ "%s:%s Exit %d"
+ "0 <= iNum && iNum < (1 + ((2) < ((63 + 1)) ? (2) : ((63 + 1))) * (1 + 9 ))"
+ "9013.55.1"
+ "UpdateFixedQP"
+ "updateFixedQP"
- "9013.48.1"
```
