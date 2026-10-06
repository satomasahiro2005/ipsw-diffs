## nsurlsessiond

> `/usr/libexec/nsurlsessiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x8e38` | `0x8cf8` | **`-0x140`** |
| `__TEXT.__objc_methname` | `0xf154` | `0xf03c` | **`-0x118`** |
| `__TEXT.__text` | `0x82f18` | `0x82eb8` | **`-0x60`** |
| `__DATA.__objc_ivar` | `0x6f8` | `0x6d0` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0xe5b0` | `0xe5d4` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x1da0` | `0x1dc0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3a7e` | `0x3a89` | **`+0xb`** |
| `__DATA_CONST.__const` | `0x15c8` | `0x15c0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2de8` | `0x2df0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3892.100.1.0.0
+3896.100.1.2.1

-  Functions: 2073
+  Functions: 2074

-  CStrings:  3852
+  CStrings:  3843
CStrings:
+ "atsContext"
- "_deleteAllSessionsForBundleIDStmt"
- "_deleteEntriesForSessionStmt"
- "_deleteSessionStmt"
- "_getAllSessionsStmt"
- "_insertOrUpdateSessionConfigurationStmt"
- "_insertOrUpdateSessionOptionsStmt"
- "_selectEntriesStmt"
- "_selectSessionConfigurationStmt"
- "_selectSessionOptionsStmt"
- "_selectUniqueBundleIDsStmt"
```
