## ContactsUI

> `/System/Library/Frameworks/ContactsUI.framework/ContactsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x385678` | `0x386b48` | **`+0x14d0`** |
| `__DATA_CONST.__got` | `0x28f8` | `0x2b50` | **`+0x258`** |
| `__TEXT.__oslogstring` | `0xac1f` | `0xaccf` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0xfc68` | `0xfd08` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x2108` | `0x2068` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x138e7` | `0x1393b` | **`+0x54`** |
| `__AUTH_CONST.__auth_got` | `0x2c88` | `0x2cb8` | **`+0x30`** |
| `__DATA.__common` | `0x348` | `0x378` | **`+0x30`** |
| `__DATA.__data` | `0xace8` | `0xad18` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xdca8` | `0xdcd8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xba40` | `0xba60` | **`+0x20`** |
| `__TEXT.__const` | `0xc440` | `0xc460` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x18558` | `0x18568` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xefc2` | `0xefce` | **`+0xc`** |

### Other Changes

```diff

-1452.100.5.0.0
+1454.100.1.0.0

-  Functions: 24361
-  Symbols:   34117
-  CStrings:  3224
+  Functions: 24369
+  Symbols:   34119
+  CStrings:  3230
Symbols:
+ _OBJC_CLASS_$_UIScrollEdgeEffectStyle
+ _symbolic _____Sg_ABt 10AppIntents16EntityIdentifierV
CStrings:
+ "Cannot create an EntityIdentifier for a contact that has not been persisted."
+ "app-intent-triage"
+ "com.apple.Spotlight"
+ "com.apple.contacts.intents"
+ "set UIView.appEntityIdentifier to %s"
+ "set UIView.appEntityIdentifier to nil"
```
