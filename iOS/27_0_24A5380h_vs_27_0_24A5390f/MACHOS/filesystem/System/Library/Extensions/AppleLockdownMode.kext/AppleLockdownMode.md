## AppleLockdownMode

> `/System/Library/Extensions/AppleLockdownMode.kext/AppleLockdownMode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4892` | `0x48cf` | **`+0x3d`** |
| `__TEXT_EXEC.__text` | `0x15064` | `0x150a0` | **`+0x3c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`

### Other Changes

```diff

-128.0.4.0.0
+128.0.5.0.0

-  CStrings:  494
+  CStrings:  495
Symbols:
+ DeallocCredentialList.kalloc_type_view_1975
+ DeserializeCredentialList.kalloc_type_view_1937
- DeallocCredentialList.kalloc_type_view_1969
- DeserializeCredentialList.kalloc_type_view_1931
Functions:
~ _DeserializeCredential : 1380 -> 1440
CStrings:
+ "sigSize > 0 && sigSize <= kACMCredentialDataSignatureMaxSize"
```
