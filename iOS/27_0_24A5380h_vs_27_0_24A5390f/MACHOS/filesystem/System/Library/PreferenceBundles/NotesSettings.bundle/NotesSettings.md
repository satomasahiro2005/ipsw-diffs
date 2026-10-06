## NotesSettings

> `/System/Library/PreferenceBundles/NotesSettings.bundle/NotesSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdd0c` | `0xdc48` | **`-0xc4`** |
| `__TEXT.__objc_stubs` | `0x2b20` | `0x2ac0` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x33e4` | `0x33c5` | **`-0x1f`** |
| `__DATA.__objc_selrefs` | `0xdf8` | `0xde0` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x288` | `0x290` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2996.0.0.0.0
+2998.0.0.0.0

-  CStrings:  875
+  CStrings:  872
Symbols:
+ _OBJC_CLASS_$_ICPasswordChangePresenter
- _OBJC_CLASS_$_ICPasswordChangeViewController
Functions:
~ sub_5cf8 : 876 -> 840
~ sub_6e2c -> sub_6e08 : 668 -> 348
~ sub_70c8 -> sub_6f64 : 64 -> 524
~ sub_7108 -> sub_7170 : 288 -> 64
~ sub_7360 -> sub_72e8 : 448 -> 412
~ sub_7bd4 -> sub_7b38 : 316 -> 312
~ sub_7d10 -> sub_7c70 : 1208 -> 1172
CStrings:
+ "viewControllerForAddingPasswordWithAccount:completion:"
+ "viewControllerForChangingPasswordWithAccount:didAuthenticateWithBiometrics:completion:"
- "initWithCompletionHandler:"
- "setIsInSettings:"
- "setIsSettingInitialPassword:"
- "setUpForAddingPasswordWithAccount:"
- "setUpForChangePasswordWithAccount:didAuthenticateWithBiometrics:"
```
