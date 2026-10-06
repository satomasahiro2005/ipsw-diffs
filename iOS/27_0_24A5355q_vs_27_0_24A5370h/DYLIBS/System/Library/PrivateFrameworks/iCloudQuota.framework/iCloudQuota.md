## iCloudQuota

> `/System/Library/PrivateFrameworks/iCloudQuota.framework/iCloudQuota`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75c98` | `0x75d4c` | **`+0xb4`** |
| `__TEXT.__oslogstring` | `0x85c9` | `0x85f9` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x6660` | `0x6680` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4f60` | `0x4f80` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xbd8` | `0xbe0` | **`+0x8`** |

### Other Changes

```diff

-301.24.0.19.0
+301.24.0.21.0

-  Functions: 2906
-  Symbols:   4286
-  CStrings:  1624
+  Functions: 2907
+  Symbols:   4288
+  CStrings:  1626
Symbols:
+ ___47-[ICQRequestProvider addBasicHeadersToRequest:]_block_invoke
+ _os_variant_has_internal_diagnostics
CStrings:
+ "Injecting debug header %{public}@: %{private}@"
+ "_ICQInjectedRequestHeaders"
```
