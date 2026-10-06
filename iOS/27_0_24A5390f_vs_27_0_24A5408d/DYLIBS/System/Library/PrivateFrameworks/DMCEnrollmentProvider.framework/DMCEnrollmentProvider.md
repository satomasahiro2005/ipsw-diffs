## DMCEnrollmentProvider

> `/System/Library/PrivateFrameworks/DMCEnrollmentProvider.framework/DMCEnrollmentProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ddac` | `0x4dbe0` | **`-0x1cc`** |
| `__TEXT.__cstring` | `0x2f58` | `0x2f28` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x1168` | `0x1140` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0x10838` | `0x10818` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x6eb4` | `0x6ea4` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4838` | `0x4830` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1510` | `0x1508` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x5b8` | `0x5b4` | **`-0x4`** |

### Other Changes

```diff

-113.0.2.0.0
+113.2.5.0.0

-  Functions: 2145
-  Symbols:   4129
-  CStrings:  628
+  Functions: 2143
+  Symbols:   4125
+  CStrings:  626
Symbols:
+ -[DMCAccountSpecifierProvider _specifierForManagedAccountGroupWithPlural:]
+ -[DMCAccountSpecifierProvider managedAccountSpecifiers]
- -[DMCAccountSpecifierProvider _specifierForManagedAccountGroupWithTitle:plural:]
- -[DMCAccountSpecifierProvider specifiersWithCompletion:]
- -[DMCAccountSpecifierProvider specifiersWithTitle:includePrimaryAccounts:]
- _OBJC_IVAR_$_DMCAccountSpecifierProvider._updateQueue
- ___56-[DMCAccountSpecifierProvider specifiersWithCompletion:]_block_invoke
- ___block_descriptor_48_e8_32bs40w_e5_v8?0lw40l8s32l8
CStrings:
- "\""
- "com.apple.devicemanagementclient.secondaryAccountUpdate"
```
