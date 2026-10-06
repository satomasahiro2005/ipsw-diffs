## com.apple.driver.AFKHIDTBDevice

> `com.apple.driver.AFKHIDTBDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xb878` | `0xbfd8` | **`+0x760`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x4f0` | **`+0x4f0`** |
| `__TEXT.__cstring` | `0x15ce` | `0x177e` | **`+0x1b0`** |

### Other Changes

```diff

-223.0.0.0.0
+224.0.0.0.0

-  CStrings:  119
+  CStrings:  123
Functions:
~ sub_fffffff008418b28 -> sub_fffffff00841cd08 : 40 -> 128
~ _afkhidtbdevice_report__marshal_sizeof.cold.1 : 40 -> 120
~ sub_fffffff008418c90 -> sub_fffffff00841cf18 : 124 -> 168
~ sub_fffffff008418ef0 -> sub_fffffff00841d1a4 : 40 -> 128
~ sub_fffffff008418f18 -> sub_fffffff00841d224 : 40 -> 120
~ sub_fffffff008419058 -> sub_fffffff00841d3b4 : 124 -> 168
~ sub_fffffff008419478 -> sub_fffffff00841d800 : 40 -> 128
~ sub_fffffff0084194a0 -> sub_fffffff00841d880 : 140 -> 408
~ sub_fffffff008419644 -> sub_fffffff00841db30 : 300 -> 344
~ _afkhidtbdevice_device_getreport : 728 -> 776
~ sub_fffffff00841a09c -> sub_fffffff00841e5e4 : 24 -> 40
~ _afkhidtbdevice_device_setreport : 768 -> 864
~ _OUTLINED_FUNCTION_5 : 172 -> 220
~ ___afkhidtbdevice_device__server_start_owned_block_invoke.31 : 168 -> 216
~ ___afkhidtbdevice_device__server_start_owned_block_invoke.38 : 172 -> 220
~ ___afkhidtbdevice_device__server_start_owned_block_invoke.45 : 172 -> 220
~ sub_fffffff00841be94 -> sub_fffffff00842050c : 492 -> 540
~ _OUTLINED_FUNCTION_0_0 : 188 -> 208
~ sub_fffffff00841c86c -> sub_fffffff008420f28 : 64 -> 92
~ sub_fffffff00841c8ac -> sub_fffffff008420f84 : 64 -> 92
~ sub_fffffff00841c8ec -> sub_fffffff008420fe0 : 88 -> 164
~ sub_fffffff00841cd2c -> sub_fffffff00842146c : 128 -> 264
~ sub_fffffff00841cf18 -> sub_fffffff0084216e0 : 24 -> 40
~ sub_fffffff00841d0bc -> sub_fffffff008421894 : 116 -> 204
~ sub_fffffff00841d264 -> sub_fffffff008421a94 : 128 -> 264
~ sub_fffffff00841d478 -> sub_fffffff008421d30 : 128 -> 264
CStrings:
+ "\"TB_ASSERT: \" \"(afkhidtbdevice_descriptor__sizeof(value, &__sz) == TB_ERROR_SUCCESS) && \\\"marshal_sizeof\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(afkhidtbdevice_devicedescription__sizeof(value, &__sz) == TB_ERROR_SUCCESS) && \\\"marshal_sizeof\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_ASSERT: \" \"(afkhidtbdevice_report__sizeof(value, &__sz) == TB_ERROR_SUCCESS) && \\\"marshal_sizeof\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "marshal_sizeof"
```
