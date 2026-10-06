## NameAndPhotoSettingsBundle

> `/System/Library/PreferenceBundles/NameAndPhotoSettingsBundle.bundle/NameAndPhotoSettingsBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f8` | `0x954` | **`+0x25c`** |
| `__TEXT.__auth_stubs` | `0x100` | `0x190` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x28` | `0x88` | **`+0x60`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0x60` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x88` | `0xd8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x168` | `0x18d` | **`+0x25`** |
| `__TEXT.__objc_stubs` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x4d0` | `0x4e9` | **`+0x19`** |
| `__DATA_CONST.__got` | `0x50` | `0x68` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x78` | `0x90` | **`+0x18`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__const` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3072.100.1.2.5
+3077.200.51.2.1

+  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 13
-  Symbols:   37
-  CStrings:  96
+  Functions: 15
+  Symbols:   50
+  CStrings:  100
Symbols:
+ __Block_object_dispose
+ __NSConcreteStackBlock
+ __Unwind_Resume
+ ___NSArray0__struct
+ ___objc_personality_v0
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __sl_dlopen
+ _objc_getClass
+ _objc_opt_respondsToSelector
+ _objc_release_x25
+ _objc_retainAutorelease
+ _objc_retain_x2
+ _objc_retain_x23
- _objc_retain_x21
CStrings:
+ "IMMeCardSharingStateController"
+ "nicknamesEnabledForCalls"
+ "softlink:o:path:/System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities"
+ "v8@?0"
```
