## nanoregistryd

> `/usr/libexec/nanoregistryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xe0d8` | `0xe174` | **`+0x9c`** |
| `__TEXT.__text` | `0x100784` | `0x10080c` | **`+0x88`** |
| `__DATA_CONST.__cfstring` | `0xc0a0` | `0xc120` | **`+0x80`** |

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

-  CStrings:  8656
+  CStrings:  8661
Functions:
~ sub_1000b09c4 : 14696 -> 14832
CStrings:
+ "27"
+ "704c505e-d459-42a9-b3b1-81b4cfa5911d"
+ "AllDayHeartRate"
+ "DeviceSupportsAudioIntelligence"
+ "DeviceSupportsContinuousHeartRate"
+ "d2f9b521-e715-4a96-94f9-19c209511ee5"
- "32"
```
