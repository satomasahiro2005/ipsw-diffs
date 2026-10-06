## RemoteManagementAgent

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/RemoteManagementAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d740` | `0x8da28` | **`+0x2e8`** |
| `__TEXT.__oslogstring` | `0xc67a` | `0xc6f3` | **`+0x79`** |
| `__TEXT.__gcc_except_tab` | `0x41dc` | `0x4238` | **`+0x5c`** |
| `__TEXT.__objc_methname` | `0xf44f` | `0xf494` | **`+0x45`** |
| `__TEXT.__objc_stubs` | `0xc540` | `0xc580` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x27a0` | `0x2778` | **`-0x28`** |
| `__DATA.__objc_selrefs` | `0x35b8` | `0x35c8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4b08` | `0x4b18` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-624.40.13.0.0
+624.40.15.0.0

-  Functions: 2597
+  Functions: 2598

-  CStrings:  3932
+  CStrings:  3936
CStrings:
+ "RMMigrationConfigurationUI3"
+ "Removing orphaned store %{public}@ whose persona no longer exists"
+ "Unable to remove orphaned store %{public}@: %{public}@"
+ "_removeStoreWithIdentifier:error:"
+ "personaWithUniqueIdentifierExists:"
- "RMMigrationConfigurationUI2"
```
