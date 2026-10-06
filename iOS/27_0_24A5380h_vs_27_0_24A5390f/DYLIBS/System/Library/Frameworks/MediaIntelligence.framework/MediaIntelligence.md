## MediaIntelligence

> `/System/Library/Frameworks/MediaIntelligence.framework/MediaIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x196b0` | `0x19854` | **`+0x1a4`** |
| `__TEXT.__oslogstring` | `0x4d4` | `0x524` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x800` | `0x818` | **`+0x18`** |
| `__TEXT.__const` | `0x1778` | `0x1788` | **`+0x10`** |

### Other Changes

```diff

-435.69.2.0.0
+435.73.2.0.0

-  Symbols:   476
-  CStrings:  49
+  Symbols:   479
+  CStrings:  50
Symbols:
+ _CGContextSetInterpolationQuality
+ _CGRectInset
+ _CGRectIntegral
Functions:
~ sub_24949659c -> sub_24a5e659c : 432 -> 656
~ sub_24949674c -> sub_24a5e682c : 960 -> 1156
CStrings:
+ "Scaling down face crop from %{public}fpx max side with factor %{public}f"
```
