## BiomeFoundation

> `/System/Library/PrivateFrameworks/BiomeFoundation.framework/BiomeFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34600` | `0x347ac` | **`+0x1ac`** |
| `__TEXT.__oslogstring` | `0x3323` | `0x33a2` | **`+0x7f`** |
| `__TEXT.__cstring` | `0x504d` | `0x507d` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x5880` | `0x58a0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x18a8` | `0x18b8` | **`+0x10`** |
| `__TEXT.__const` | `0x22a` | `0x23a` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xdc0` | `0xdcc` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x380` | `0x388` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2a54` | `0x2a5c` | **`+0x8`** |

### Other Changes

```diff

-236.0.2.0.0
+239.0.2.0.0

-  Functions: 1228
-  Symbols:   2196
-  CStrings:  1056
+  Functions: 1229
+  Symbols:   2199
+  CStrings:  1058
Symbols:
+ -[BMAccessDelegate prepareResource:withMode:inContainer:error:]
+ -[BMProcess _canTrustUnrestrictedEntitlementsAndSigningIdentifier:]
+ -[BMProcess _shouldTrustIdentifier:validationCategory:onInternalDevice:]
+ GCC_except_table17
+ GCC_except_table43
+ _NSFilePathErrorKey
- -[BMAccessDelegate prepareResource:withMode:inContainer:]
- -[BMProcess _canTrustUnrestrictedEntitlementsAndSigningIdentifier]
- GCC_except_table51
CStrings:
+ "Failed to open property list for write"
+ "Warning: Not trusting process %{public}@(%d) with identifier %{public}@ (validation category %u, internal %d)"
+ "open_dprotected_np failed for %@: errno=%d (%{darwin.errno}d)"
- "Warning: Not trusting process %{public}@(%d)"
```
