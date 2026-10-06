## OSEligibility

> `/System/Library/PrivateFrameworks/OSEligibility.framework/OSEligibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e6b0` | `0x1e72c` | **`+0x7c`** |
| `__DATA_CONST.__objc_selrefs` | `0x138` | `0x150` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x1c0` | `0x1d0` | **`+0x10`** |

### Other Changes

```diff

-446.0.2.0.0
+446.2.1.0.0
Functions:
~ sub_295277aa8 -> sub_294e87aa8 : 2888 -> 2932
~ sub_295291e70 -> sub_294ea1e9c : 32 -> 112
CStrings:
+ "Not bypassing eligibility for %s:%s (isProfileValidated: %{bool}d isUPPValidated:%{bool}d isExternalBeta:%{bool}d)"
- "Not bypassing eligibility for %s:%s (isProfileValidated: %{bool}d isUPPValidated:%{bool}d isBeta:%{bool}d"
```
