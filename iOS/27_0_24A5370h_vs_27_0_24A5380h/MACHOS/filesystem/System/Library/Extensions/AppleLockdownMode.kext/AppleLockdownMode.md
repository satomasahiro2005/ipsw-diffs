## AppleLockdownMode

> `/System/Library/Extensions/AppleLockdownMode.kext/AppleLockdownMode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1506c` | `0x15064` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`

### Other Changes

```diff

-128.0.3.0.0
+128.0.4.0.0
Symbols:
+ DeallocCredentialList.kalloc_type_view_1969
+ DeserializeCredentialList.kalloc_type_view_1931
- DeallocCredentialList.kalloc_type_view_1943
- DeserializeCredentialList.kalloc_type_view_1905
Functions:
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 1512 -> 1504
```
