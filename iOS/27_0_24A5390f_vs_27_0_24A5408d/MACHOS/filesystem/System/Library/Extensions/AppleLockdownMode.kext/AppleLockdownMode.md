## AppleLockdownMode

> `/System/Library/Extensions/AppleLockdownMode.kext/AppleLockdownMode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x150a0` | `0x15180` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x48cf` | `0x4918` | **`+0x49`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`

### Other Changes

```diff

-128.0.5.0.0
+128.0.8.0.0

-  CStrings:  495
+  CStrings:  498
Functions:
~ _DeserializeCredential : 1440 -> 1444
~ _LibSer_SEPControl_Deserialize : 356 -> 496
~ _LibSer_SEPControlResponse_Deserialize : 208 -> 288
CStrings:
+ "remaining >= cmdSize"
+ "remaining >= respSize"
+ "remaining >= sizeof(uint32_t)"
```
