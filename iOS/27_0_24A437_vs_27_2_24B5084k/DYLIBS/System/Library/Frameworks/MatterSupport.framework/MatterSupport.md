## MatterSupport

> `/System/Library/Frameworks/MatterSupport.framework/MatterSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x5850` | `0x5870` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x4323` | `0x4317` | **`-0xc`** |

### Other Changes

```diff

-1493.1.5.1.1
+1514.0.0.0.1

-  Symbols:   1666
+  Symbols:   1670
Symbols:
+ _logCategory._hmf_once_t32
+ _logCategory._hmf_once_t38
+ _logCategory._hmf_once_v33
+ _logCategory._hmf_once_v39
CStrings:
+ "[%{public}@] Successfully performed Matter device setup"
+ "[%{public}@] [%{public}@] Successfully performed Matter device setup"
- "[%{public}@] Successfully performed Matter device setup setup"
- "[%{public}@] [%{public}@] Successfully performed Matter device setup setup"
```
