## ActiveSyncSettings

> `/System/Library/PreferenceBundles/AccountSettings/ActiveSyncSettings.bundle/ActiveSyncSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a890` | `0x1a89c` | **`+0xc`** |
| `__TEXT.__cstring` | `0x1358` | `0x135a` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2079.0.1.0.0
+2079.200.31.0.0
Symbols:
+ _EASIsHotmailAccountToAuthenticate
- _EASNameForAccountToAuthenticate
Functions:
~ sub_15bb0 : 492 -> 500
~ sub_1ab94 -> sub_1ab9c : 476 -> 480
CStrings:
+ "EASIsHotmailAccountToAuthenticate"
+ "EXCHANGE_NEEDS_SIGNIN"
+ "HOTMAIL_NEEDS_SIGNIN"
- "ACCOUNT_NOT_AUTHENTICATED"
- "EASNameForAccountToAuthenticate"
- "REENTER_PASSWORD"
```
