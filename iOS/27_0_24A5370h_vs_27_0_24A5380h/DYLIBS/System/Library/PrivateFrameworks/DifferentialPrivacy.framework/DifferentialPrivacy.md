## DifferentialPrivacy

> `/System/Library/PrivateFrameworks/DifferentialPrivacy.framework/DifferentialPrivacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1238` | `0x360` | **`-0xed8`** |
| `__DATA_DIRTY.__objc_data` | `0x1400` | `0x22d8` | **`+0xed8`** |
| `__AUTH.__data` | `0x1e0` | `—` | **`-0x1e0`** |
| `__DATA_DIRTY.__data` | `0x10` | `0x1f0` | **`+0x1e0`** |
| `__TEXT.__text` | `0x47630` | `0x4763c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x8c8` | `0x8c0` | **`-0x8`** |

### Other Changes

```diff

-786.0.0.0.5
+791.0.0.0.1

-  Symbols:   2876
+  Symbols:   2875
Symbols:
- _swift_willThrowTypedImpl
Functions:
~ -[_DPPrio3SumVectorRandomizer randomizeBitVectors:metadata:forKey:error:] : 1784 -> 1808
~ sub_227032794 -> sub_22b8f475c : 1504 -> 1492
```
