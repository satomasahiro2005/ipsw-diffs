## Mail

> `/System/Library/Assistant/Plugins/Mail.assistantBundle/Mail`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3338` | `0x33d0` | **`+0x98`** |
| `__TEXT.__objc_methtype` | `0x295` | `0x2c2` | **`+0x2d`** |
| `__DATA.__objc_const` | `0x738` | `0x758` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x300` | `0x320` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x83c` | `0x851` | **`+0x15`** |
| `__DATA_CONST.__auth_got` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x20` | `0x24` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3893.100.7.0.0
+3895.100.17.2.1

-  Symbols:   131
-  CStrings:  196
+  Symbols:   134
+  CStrings:  198
Symbols:
+ OBJC_IVAR_$_MFAssistantEmailSearch._searchCompletedLock
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
Functions:
~ sub_3444 : 536 -> 568
~ sub_392c -> sub_394c : 52 -> 172
CStrings:
+ "_searchCompletedLock"
+ "{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}"
```
