## KeyboardSettingsBundle

> `/System/Library/PreferenceBundles/KeyboardSettingsBundle.bundle/KeyboardSettingsBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b470` | `0x2b388` | **`-0xe8`** |
| `__TEXT.__cstring` | `0x36f8` | `0x3688` | **`-0x70`** |
| `__DATA_CONST.__cfstring` | `0x31c0` | `0x3180` | **`-0x40`** |
| `__DATA_CONST.__const` | `0xcd0` | `0xcb0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x8b5e` | `0x8b6f` | **`+0x11`** |
| `__DATA.__bss` | `0x200` | `0x1f0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x2ab0` | `0x2ac0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x9c8` | `0x9c0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-147.100.0.0.0
+148.1.3.0.0

-  Functions: 910
+  Functions: 908

-  CStrings:  2087
+  CStrings:  2084
CStrings:
+ "%s Feedback %@: RC_SEED_BUILD: 1 enabled: %d"
+ "updateEditButtonEnabledState"
- "%s Feedback %@: RC_SEED_BUILD: 0 enabled: %d"
- "-[KSKeyboardListController setEditing:animated:]"
- "_numberOfEnabledKeyboards > 1"
- "apple-internal-install"
- "boolForKey:"
```
