## SMS

> `/System/Library/Messages/PlugIns/SMS.imservice/SMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b6c` | `0x10aa4` | **`-0xc8`** |
| `__TEXT.__objc_stubs` | `0x2b40` | `0x2ac0` | **`-0x80`** |
| `__TEXT.__objc_methname` | `0x492e` | `0x48c7` | **`-0x67`** |
| `__DATA.__objc_selrefs` | `0x1048` | `0x1028` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x3e0` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Symbols:   309
-  CStrings:  1026
+  Symbols:   307
+  CStrings:  1022
Symbols:
- _IMChatPropertyNeedsInitialHidingForUPIMessages
- _OBJC_CLASS_$_IMDBroadcastController
Functions:
~ sub_b544 : 1248 -> 1048
CStrings:
- "broadcasterForChatListenersUsingBlackholeRegistry:"
- "chat:propertiesUpdated:"
- "isBlackholed"
- "sharedProvider"
```
