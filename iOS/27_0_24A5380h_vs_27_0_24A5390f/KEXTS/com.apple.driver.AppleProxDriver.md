## com.apple.driver.AppleProxDriver

> `com.apple.driver.AppleProxDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xa650` | `0xa818` | **`+0x1c8`** |
| `__TEXT.__cstring` | `0x8ca` | `0x8f1` | **`+0x27`** |
| `__TEXT.__os_log` | `0x79f` | `0x7b8` | **`+0x19`** |
| `__DATA_CONST.__got` | `0x80` | `0x88` | **`+0x8`** |

### Other Changes

```diff

-58.0.0.0.0
+59.0.0.0.0

-  CStrings:  165
+  CStrings:  168
Functions:
~ sub_fffffff00947077c -> sub_fffffff0094915ec : 56 -> 60
~ sub_fffffff0094707b4 -> sub_fffffff009491628 : 56 -> 60
~ sub_fffffff0094707ec -> sub_fffffff009491664 : 120 -> 160
~ sub_fffffff009470864 -> sub_fffffff009491704 : 120 -> 160
~ sub_fffffff009470990 -> sub_fffffff009491858 : 108 -> 112
~ sub_fffffff009470a10 -> sub_fffffff0094918dc : 92 -> 96
~ sub_fffffff009470a6c -> sub_fffffff00949193c : 92 -> 96
~ sub_fffffff009471308 -> sub_fffffff0094921dc : 628 -> 716
~ sub_fffffff009475ccc -> sub_fffffff009496bf8 : 300 -> 580
~ sub_fffffff009475df8 -> sub_fffffff009496e3c : 776 -> 764
CStrings:
+ "12111112122212121111111211111122111112121"
+ "AtlantisProcessingPlan"
+ "ProcessingPlan"
+ "Using processing plan %s"
- "1211111212221212111111121111112211111212"
```
