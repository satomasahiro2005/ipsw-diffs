## NanoPassbookBridgeSettings

> `/System/Library/NanoPreferenceBundles/Applications/NanoPassbookBridgeSettings.bundle/NanoPassbookBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2658` | `0x2685` | **`+0x2d`** |
| `__TEXT.__const` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__text` | `0x14998` | `0x149a0` | **`+0x8`** |

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

-1338.0.0.0.0
+1341.0.0.0.0
Functions:
~ sub_2c00 : 2756 -> 2760
~ sub_d2e4 -> sub_d2e8 : 368 -> 372
CStrings:
+ "Notice: Provisioning controller: pass with unique ID %@ updated with balance reminder %@ balance %{private}@"
+ "Notice: Provisioning controller: pass with unique ID %@ updated with balances %{private}@"
+ "Notice: Provisioning controller: transaction source identifier %@ received transaction %{private}@"
+ "Notice: Telling delegate %@ about transit pass properties with balance %{private}@"
+ "Notice: type ID %@ serial number %{private}@ unique ID %@"
- "Notice: Provisioning controller: pass with unique ID %@ updated with balance reminder %@ balance %@"
- "Notice: Provisioning controller: pass with unique ID %@ updated with balances %@"
- "Notice: Provisioning controller: transaction source identifier %@ received transaction %@"
- "Notice: Telling delegate %@ about transit pass properties with balance %@"
- "Notice: type ID %@ serial number %@ unique ID %@"
```
