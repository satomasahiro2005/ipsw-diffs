## sysstatuscheck

> `/usr/libexec/sysstatuscheck`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd00c` | `0xd100` | **`+0xf4`** |
| `__TEXT.__cstring` | `0xc34` | `0xc5a` | **`+0x26`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-230.0.0.0.0
+233.0.0.0.0

-  CStrings:  82
+  CStrings:  83
Functions:
~ sub_100000800 : 2124 -> 2128
~ sub_1000014f0 -> sub_1000014f4 : 168 -> 164
~ sub_100001ec0 : 244 -> 272
~ sub_100001fb4 -> sub_100001fd0 : 848 -> 1012
~ sub_100002608 -> sub_1000026c8 : 348 -> 340
~ sub_10000367c -> sub_100003734 : 368 -> 360
~ sub_10000424c -> sub_1000042fc : 472 -> 484
~ sub_100008420 -> sub_1000084dc : 308 -> 300
~ sub_10000867c -> sub_100008730 : 172 -> 176
~ sub_100008c48 -> sub_100008d00 : 1768 -> 1784
~ sub_100009e90 -> sub_100009f58 : 504 -> 532
~ sub_10000a088 -> sub_10000a16c : 148 -> 176
~ sub_10000a11c -> sub_10000a21c : 200 -> 228
~ sub_10000a638 -> sub_10000a754 : 1212 -> 1180
~ sub_10000c03c -> sub_10000c138 : 40 -> 36
~ sub_10000c184 -> sub_10000c27c : 260 -> 264
~ sub_10000c288 -> sub_10000c384 : 456 -> 444
~ sub_10000cb3c -> sub_10000cc2c : 216 -> 220
CStrings:
+ "Failed to update permissions to %04o and/or user/group ownership to %d/%d for '%s'.\n"
+ "com.apple.driver.AppleProcessorTrace"
- "Failed to update permisions to %04o and/or user/group ownership to %d/%d for '%s'.\n"
```
