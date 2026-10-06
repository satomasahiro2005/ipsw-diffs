## ModelCatalogRuntime

> `/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/ModelCatalogRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83e7c` | `0x83d60` | **`-0x11c`** |
| `__DATA_DIRTY.__data` | `0x1538` | `0x1608` | **`+0xd0`** |
| `__AUTH.__data` | `0x508` | `0x488` | **`-0x80`** |
| `__DATA.__bss` | `0x1a90` | `0x1a10` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0xa00` | `0xa80` | **`+0x80`** |
| `__TEXT.__const` | `0x3048` | `0x30a8` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x42ca` | `0x432a` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x44b4` | `0x4464` | **`-0x50`** |
| `__TEXT.__swift5_typeref` | `0x19e2` | `0x1a26` | **`+0x44`** |
| `__TEXT.__constg_swiftt` | `0x1208` | `0x1244` | **`+0x3c`** |
| `__AUTH_CONST.__const` | `0x4558` | `0x4590` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xba0` | `0xbcc` | **`+0x2c`** |
| `__DATA.__data` | `0x790` | `0x768` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0x1678` | `0x1698` | **`+0x20`** |
| `__TEXT.__cstring` | `0x14db` | `0x14fb` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xa03` | `0xa23` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1478` | `0x1490` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1cc8` | `0x1cb8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x178` | `0x17c` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x48` | `0x4c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x10c` | `0x110` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x30c` | `0x310` | **`+0x4`** |

### Other Changes

```diff

-295.0.1.0.0
+298.3.0.0.0

-  Functions: 3173
-  Symbols:   249
-  CStrings:  341
+  Functions: 3176
+  Symbols:   248
+  CStrings:  342
Symbols:
- _swift_willThrowTypedImpl
CStrings:
+ "CoherenceTokenStore: coherenceTokens called on a non-initialized coherence store"
+ "CoherenceTokenStore: coherenceTokens called on a record with no tokens"
+ "Skip requesting resource bundle for %s: bundle policy gated_by_use_case_access not yet granted."
- "Could not inflate asset sets as the store is not initialized"
- "usageAgnosticCoherentAssetSets called on a non-initialized coherence store"
```
