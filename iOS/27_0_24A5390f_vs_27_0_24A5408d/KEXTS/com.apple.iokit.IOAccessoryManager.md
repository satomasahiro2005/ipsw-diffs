## com.apple.iokit.IOAccessoryManager

> `com.apple.iokit.IOAccessoryManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xe4e84` | `0xe4f58` | **`+0xd4`** |
| `__TEXT.__os_log` | `0x121cf` | `0x121fe` | **`+0x2f`** |

### Other Changes

```diff

-1068.0.0.0.0
+1068.0.0.0.2

-  CStrings:  2962
+  CStrings:  2963
Functions:
~ __ZN17IOPortFeatureLDCM32_handleMitigationsForLiquidStateEb : 1616 -> 1828
CStrings:
+ "%s::%s(): [%s%s%s] Mitigations not supported\n\n"
```
