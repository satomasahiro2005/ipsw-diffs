## CFNetwork

> `/System/Library/Frameworks/CFNetwork.framework/CFNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x256a9c` | `0x256994` | **`-0x108`** |
| `__TEXT.__oslogstring` | `0xfa2d` | `0xf9d7` | **`-0x56`** |

### Other Changes

```diff

-3896.200.52.0.0
+3896.200.61.0.0

-  CStrings:  4756
+  CStrings:  4755
Functions:
~ __ZN10URLRequest10initializeEPKS_h : 952 -> 940
~ -[NSURLSessionTask _takePreventIdleSleepAssertionIfAppropriate] : 984 -> 732
CStrings:
- "%{public}@ system activity assertion did not revert sleep (attempt %d/3, result = %d)"
```
