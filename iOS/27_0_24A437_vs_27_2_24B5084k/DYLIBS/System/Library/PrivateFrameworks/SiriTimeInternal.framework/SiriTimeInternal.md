## SiriTimeInternal

> `/System/Library/PrivateFrameworks/SiriTimeInternal.framework/SiriTimeInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x601cc` | `0x6007c` | **`-0x150`** |
| `__TEXT.__oslogstring` | `0x346b` | `0x348b` | **`+0x20`** |
| `__TEXT.__const` | `0x5048` | `0x5058` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x360` | `0x358` | **`-0x8`** |

### Other Changes

```diff

-3600.26.13.0.0
+3605.9.1.0.0

-  CStrings:  387
+  CStrings:  386
Functions:
~ sub_2aa74a5e8 -> sub_2b0a845e8 : 1372 -> 1036
CStrings:
+ "Failed to get Bundle at path '%{public}s' for identifier '%{public}s'"
+ "Failed to get resourcePath for bundle with identifier '%{public}s'"
+ "Got Bundle (by path) for identifier '%{public}s'"
+ "Template directory for bundle %{public}s': %{public}s"
- "Failed to get Bundle for identifier '%s'"
- "Failed to get resourcePath for bundle with identifier '%s'"
- "Got Bundle (by ID) for identifier '%s'"
- "Got Bundle (by path) for identifier '%s'"
- "Template directory for bundle %s': %s"
```
