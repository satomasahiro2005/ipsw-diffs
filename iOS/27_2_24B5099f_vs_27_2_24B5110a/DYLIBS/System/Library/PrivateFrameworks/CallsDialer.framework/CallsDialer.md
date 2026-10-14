## CallsDialer

> `/System/Library/PrivateFrameworks/CallsDialer.framework/CallsDialer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43bac` | `0x43bf4` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x5e18` | `0x5e48` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x3f84` | `0x3f9c` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1a0` | `0x1b4` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xb78` | `0xb88` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3470` | `0x3480` | **`+0x10`** |
| `__TEXT.__const` | `0x1784` | `0x1794` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1260` | `0x1268` | **`+0x8`** |

### Other Changes

```diff

-156.200.120.0.0
+156.200.131.2.6

-  Symbols:   2278
+  Symbols:   2281
Symbols:
+ GCC_except_table6
+ _objc_sync_enter
+ _objc_sync_exit
Functions:
~ sub_21745689c -> sub_217c3189c : 44 -> 48
~ sub_2174568c8 -> sub_217c318cc : 44 -> 48
~ +[PHHandsetDialerResizableButton verticalPaddingForCategory:screenSize:] : 216 -> 220
~ +[PHHandsetDialerResizableButton horizontalPaddingForCategory:] : 220 -> 228
~ -[DialerDataProvider contactsDataProvider] : 128 -> 180
```
