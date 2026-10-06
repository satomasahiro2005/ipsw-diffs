## DataAccess

> `/System/Library/PrivateFrameworks/DataAccess.framework/DataAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ae84` | `0x3b16c` | **`+0x2e8`** |
| `__AUTH_CONST.__objc_const` | `0x7220` | `0x72a8` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x482c` | `0x488c` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x537f` | `0x53d9` | **`+0x5a`** |
| `__TEXT.__unwind_info` | `0xf48` | `0xf90` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x2da0` | `0x2dc0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x358` | `0x360` | **`+0x8`** |

### Other Changes

```diff

-2708.0.0.0.0
+2708.1.5.0.0

-  Functions: 1607
-  Symbols:   2918
-  CStrings:  778
+  Functions: 1616
+  Symbols:   2929
+  CStrings:  779
Symbols:
+ -[DAABLegacyContainer hasUserVisibleChanges]
+ -[DAABLegacyContainer setUserVisibleChanges:]
+ -[DAABLegacyContainer userVisibleChanges]
+ -[DAContactsContainer hasUserVisibleChanges]
+ -[DAContactsContainer setUserVisibleChanges:]
+ -[DAContactsContainer userVisibleChanges]
+ -[DALocalDBHelper abSaveDBSuppressingChangeNotifications]
+ _ABAddressBookSetSuppressChangeNotifications
+ _OBJC_IVAR_$_DAABLegacyContainer._userVisibleChanges
+ _OBJC_IVAR_$_DAContactsContainer._userVisibleChanges
+ ___57-[DALocalDBHelper abSaveDBSuppressingChangeNotifications]_block_invoke
CStrings:
+ "abSaveDBSuppressingChangeNotifications is unsupported under modern Contacts framework :%@"
```
