## JournalDataclassOwner

> `/System/Library/Accounts/DataclassOwners/JournalDataclassOwner.bundle/JournalDataclassOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb370` | `0xb9e4` | **`+0x674`** |
| `__TEXT.__objc_stubs` | `0x480` | `0x520` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x6c0` | `0x733` | **`+0x73`** |
| `__TEXT.__oslogstring` | `0xb6d` | `0xbbd` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x228` | `0x250` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1a3` | `0x1c3` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x198` | `0x1b0` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-89.0.0.0.0
+94.0.0.0.0

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 189
-  Symbols:   148
-  CStrings:  161
+  Functions: 190
+  Symbols:   151
+  CStrings:  169
Symbols:
+ _OBJC_CLASS_$_RBSProcessPredicate
+ _OBJC_CLASS_$_RBSTerminateContext
+ _OBJC_CLASS_$_RBSTerminationAssertion
CStrings:
+ "Disabling Journal dataclass"
+ "Failed to terminate Journal: %@"
+ "Terminating Journal while disabling dataclass"
+ "acquireWithError:"
+ "initWithExplanation:"
+ "initWithPredicate:context:"
+ "invalidate"
+ "predicateMatchingBundleIdentifier:"
```
