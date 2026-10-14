## ReplicatorServices

> `/System/Library/PrivateFrameworks/ReplicatorServices.framework/ReplicatorServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11f528` | `0x11fd60` | **`+0x838`** |
| `__TEXT.__oslogstring` | `0x3f80` | `0x3fd0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x100` | `0x120` | **`+0x20`** |
| `__DATA.__data` | `0x1e78` | `0x1e68` | **`-0x10`** |
| `__TEXT.__const` | `0xc848` | `0xc858` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2af0` | `0x2afc` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x208` | `0x210` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x548` | `0x540` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-176.2.5.0.0
+176.2.6.0.0

-  Functions: 5535
+  Functions: 5534

-  CStrings:  508
+  CStrings:  509
CStrings:
+ "Fetched %{private}s: %{public}s - %{public}s"
+ "Illegal state for %{private}s in relationship %{public}s: %{public}s"
+ "No migrating-from ID for %{private}s in relationship %{public}s"
+ "Parsed stored relationship %{public}s"
+ "Returning local device ID %{private}s for migration"
+ "homeAccessory"
- "Fetched %{public}s - %{public}s"
- "Illegal state for %{public}s: %{public}s"
- "No migrating-from ID for %{public}s"
- "Parsed stored relationship: %s"
- "Returning local device ID %{public}s for migration"
```
