## AppleAccountSettings

> `/System/Library/PreferenceBundles/AccountSettings/AppleAccountSettings.bundle/AppleAccountSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42c84` | `0x42d50` | **`+0xcc`** |
| `__TEXT.__objc_methname` | `0xb0e6` | `0xb116` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x5096` | `0x50c6` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x80a0` | `0x80c0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2b98` | `0x2ba0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2c48` | `0x2c40` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-589.125.4.0.0
+589.125.7.0.0

-  Functions: 1521
+  Functions: 1522

-  CStrings:  2736
+  CStrings:  2738
CStrings:
+ "[AAUIAppleAccountViewController _isSplitView]: %@"
+ "aaui_isPresentedInExpandedSplitView"
+ "signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:telemetryFlowID:context:completion:"
- "signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:context:completion:"
```
