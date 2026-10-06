## WebContentRestrictionsUI

> `/Applications/WebContentRestrictionsUI.app/WebContentRestrictionsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6a60` | `0x6f64` | **`+0x504`** |
| `__TEXT.__objc_stubs` | `0xfe0` | `0x1020` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2e` | `0x5f` | **`+0x31`** |
| `__TEXT.__auth_stubs` | `0x7b0` | `0x7e0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x214` | `0x240` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x480` | `0x458` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x580` | `0x5a8` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0xe47` | `0xe67` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x3e8` | `0x400` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x2b8` | **`+0x18`** |
| `__DATA.__objc_const` | `0x968` | `0x978` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x500` | `0x510` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-67.0.0.0.0
+70.0.0.0.0

-  Functions: 161
-  Symbols:   208
-  CStrings:  281
+  Functions: 163
+  Symbols:   211
+  CStrings:  284
Symbols:
+ _$s26ScreenTimeSettingsServices0abC0C10ManagementV8passcodeSSvg
+ _$s26ScreenTimeSettingsServices0abC0C10ManagementVMa
+ _$s26ScreenTimeSettingsServices0abC0C10managementAC10ManagementVvg
CStrings:
+ "Error checking ScreenTimeSettings passcode: %@"
+ "hasPasscode"
+ "hasPasscodeWithCompletion:"
+ "layoutIfNeeded"
- "viewDidLayoutSubviews"
```
