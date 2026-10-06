## DriverKit

> `/System/Library/Frameworks/DriverKit.framework/DriverKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37cbc` | `0x37d08` | **`+0x4c`** |

### Other Changes

```diff

-509.0.0.0.0
+509.0.1.0.0
Functions:
~ __Z21OSUnserializeXMLparsePv : 3864 -> 3952
~ __ZL27PE_parse_boot_argn_internalPKcPvib : 1196 -> 1148
~ __ZL6getTagP12parser_statePcPiPA32_cS4_ : 1076 -> 1084
~ __ZL21_IODispatchQueueSleepP26IODispatchQueue_LocalIVarsyPv8timespecb : 452 -> 468
~ __ZN15IODispatchQueue17WakeupWithOptionsEPvy : 196 -> 200
~ __ZL28OSDictionarySetValueInternalP12OSDictionaryP8OSObjectPKcS2_ : 900 -> 908
```
