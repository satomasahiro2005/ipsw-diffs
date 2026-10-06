## Leo

> `/System/Library/PrivateFrameworks/Leo.framework/Leo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3fa0c` | `0x3ff60` | **`+0x554`** |
| `__DATA.__bss` | `0x1480` | `0x1780` | **`+0x300`** |
| `__TEXT.__const` | `0x1a80` | `0x1ca0` | **`+0x220`** |
| `__TEXT.__cstring` | `0xae15` | `0xaf6a` | **`+0x155`** |
| `__TEXT.__unwind_info` | `0x15d0` | `0x1638` | **`+0x68`** |
| `__DATA.__data` | `0x508` | `0x550` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1aa0` | `0x1ae0` | **`+0x40`** |
| `__DATA.__common` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x8f0` | `0x8d0` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0xcc` | `0xe4` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xe10` | `0xe20` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x71e` | `0x72e` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x8d0` | `0x8c4` | **`-0xc`** |
| `__TEXT.__swift5_mpenum` | `0x24` | `0x18` | **`-0xc`** |
| `__AUTH_CONST.__const` | `0x1330` | `0x1328` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x378` | `0x380` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x2a20` | `0x2a18` | **`-0x8`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Functions: 1823
+  Functions: 1856

-  CStrings:  365
+  CStrings:  375
Symbols:
+ _LEOErrorDomain
+ _LEOSQLiteErrorDomain
+ _NSDebugDescriptionErrorKey
+ ___swift_memcpy33_8
+ _associated conformance 3Leo0A10StoreErrorO10Foundation13CustomNSErrorAAs0C0
+ _associated conformance 3Leo0A13DatabaseErrorO10Foundation13CustomNSErrorAAs0C0
+ _associated conformance 3Leo11SQLiteErrorV10Foundation13CustomNSErrorAAs0C0
+ _get_enum_tag_for_layout_string 3Leo0A10StoreErrorO
+ _get_enum_tag_for_layout_string 3Leo0A13DatabaseErrorO
+ _symbolic _____ 3Leo0A10StoreErrorO
+ _symbolic _____ 3Leo0A13DatabaseErrorO
+ _symbolic _____ 3Leo11SQLiteErrorV
+ _type_layout_string 3Leo0A10StoreErrorO
+ _type_layout_string 3Leo0A13DatabaseErrorO
+ _type_layout_string 3Leo11SQLiteErrorV
- ___swift_memcpy25_8
- ___swift_memcpy40_8
- ___swift_memcpy56_8
- ___unnamed_4
- _get_enum_tag_for_layout_string 3Leo0A5ErrorO
- _get_enum_tag_for_layout_string 3Leo11SQLiteErrorO
- _symbolic SS7message______8locationt 3Leo12CodeLocationV
- _symbolic Su
- _symbolic _____ 3Leo0A5ErrorO
- _symbolic _____ 3Leo11SQLiteErrorO
- _symbolic _____ 3Leo12CodeLocationV
- _symbolic _____4code_SS7messaget s5Int32V
- _type_layout_string 3Leo0A5ErrorO
- _type_layout_string 3Leo11SQLiteErrorO
- _type_layout_string 3Leo12CodeLocationV
CStrings:
+ ", scores count = "
+ ". Lexeme IDs count = "
+ "An item with identifier "
+ "Attribute context is invalid"
+ "Attribute context is not writable"
+ "Failed to open database"
+ "Failed to prepare statement"
+ "Found corrupt lexeme scores data for identifier "
+ "Specified invalid sort descriptor: "
+ "Specified invalid text match mode: "
+ "Unexpected database state: "
+ "com.apple.leo.sqlite"
- "Attempted to create a WritableAttributeContext with read-only access"
- "Leo/Utilities.swift"
```
