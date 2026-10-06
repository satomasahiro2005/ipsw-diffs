## teslad

> `/usr/libexec/teslad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xea14` | `0xead0` | **`+0xbc`** |
| `__DATA_CONST.__cfstring` | `0x1e00` | `0x1e80` | **`+0x80`** |
| `__TEXT.__cstring` | `0x13ba` | `0x13ea` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x840` | `0x860` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-113.2.5.0.0
+113.40.17.0.0

-  CStrings:  971
+  CStrings:  975
Functions:
~ sub_10000cba4 : 4820 -> 5008
CStrings:
+ "OrganizationID"
+ "OrganizationType"
+ "org-id"
+ "org-type"
```
