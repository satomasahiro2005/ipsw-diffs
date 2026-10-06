## Contacts

> `/private/var/staged_system_apps/Contacts.app/Contacts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf860` | `0xf964` | **`+0x104`** |
| `__TEXT.__objc_stubs` | `0x3e40` | `0x3e80` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x4c0` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x5ec5` | `0x5ed3` | **`+0xe`** |
| `__DATA.__objc_selrefs` | `0x1608` | `0x1610` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x278` | `0x270` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x1e08` | `0x1e00` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1454.100.1.0.0
+1456.100.1.2.1

-  Symbols:   164
-  CStrings:  1156
+  Symbols:   163
+  CStrings:  1157
Symbols:
- _CNUIIsContacts
CStrings:
+ "constraintEqualToAnchor:"
+ "shouldDisplayContactCardEdgeToEdge"
- "_preferredSearchColumnForSplitViewController:"
```
