## nanoregistryd

> `/usr/libexec/nanoregistryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x101134` | `0x101170` | **`+0x3c`** |
| `__TEXT.__oslogstring` | `0x164d9` | `0x16513` | **`+0x3a`** |
| `__TEXT.__cstring` | `0xe299` | `0xe274` | **`-0x25`** |
| `__DATA_CONST.__cfstring` | `0xc1e0` | `0xc200` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1075.11.0.0.0
+1075.12.0.0.0

-  CStrings:  8683
+  CStrings:  8679
Functions:
~ sub_1000b121c : 14928 -> 14988
CStrings:
+ "42"
+ "545ac5a6-e886-4466-b1b1-6621157fe0d6"
+ "NanoRegistry-1075.12"
+ "os_eligibility_get_domain_answer for ELAPHRUS returned %d"
- "27"
- "AllDayHeartRate"
- "Health"
- "NanoRegistry-1075.11"
- "acacia"
- "deprecateIRN1"
- "nebula"
- "sleepAlarmCoordination"
```
