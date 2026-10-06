## com.apple.driver.ApplePTD

> `com.apple.driver.ApplePTD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x310` | **`+0x310`** |
| `__TEXT_EXEC.__text` | `0x8d8c` | `0x8db0` | **`+0x24`** |

### Other Changes

```diff

-47.0.0.502.1
+48.0.0.0.0
Functions:
~ __ZN8ApplePTD16_ptdAllocVectorsEv : 1280 -> 1288
~ sub_fffffff009344dec -> sub_fffffff0093845f4 : 352 -> 348
~ _OUTLINED_FUNCTION_6 : 644 -> 640
~ sub_fffffff00934587c -> sub_fffffff00938507c : 548 -> 532
~ sub_fffffff009345aa0 -> sub_fffffff009385290 : 424 -> 416
~ __ZN8ApplePTD13dumpInterruptEP9IOServicei : 2612 -> 2608
~ __ZN8ApplePTD8_ptdReadEP19ptd_data_entry_v1_tP18ptd_gather_requestb : 152 -> 140
~ __ZN8ApplePTD9_ptdWriteEP19ptd_data_entry_v1_tP18ptd_gather_request : 96 -> 104
~ __ZN14ApplePTDCommon18_ptdLookupMultipleEP19ptd_data_entry_v1_tj : 376 -> 412
~ __ZN14ApplePTDCommon16_ptdReadMultipleEP18ptd_gather_requestjbRK16ApplePTDAccessor : 176 -> 208
```
