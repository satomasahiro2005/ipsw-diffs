## LocalAuthenticationPrivateUI

> `/System/Library/PrivateFrameworks/LocalAuthenticationPrivateUI.framework/LocalAuthenticationPrivateUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x316d8` | `0x31750` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0x3be0` | `0x3c10` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x16b8` | `0x16d0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x19a4` | `0x19bc` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x370` | `0x374` | **`+0x4`** |

### Other Changes

```diff

-2319.0.33.0.1
+2319.0.46.0.0

-  Functions: 994
-  Symbols:   1950
+  Functions: 996
+  Symbols:   1953
Symbols:
+ -[LAUIPhysicalButtonView inset]
+ -[LAUIPhysicalButtonView setInset:]
+ _OBJC_IVAR_$_LAUIPhysicalButtonView._inset
Functions:
~ -[LAUIPhysicalButtonView layoutSubviews] : 2408 -> 2456
+ -[LAUIPhysicalButtonView setInset:]
+ -[LAUIPhysicalButtonView inset]
~ -[LAUIPhysicalButtonLabel initWithFrame:] : 716 -> 732
```
