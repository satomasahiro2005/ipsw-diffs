## ContainerManagerCommon

> `/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/ContainerManagerCommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf1814` | `0xf1ad0` | **`+0x2bc`** |
| `__TEXT.__oslogstring` | `0xe405` | `0xe509` | **`+0x104`** |
| `__TEXT.__cstring` | `0x9445` | `0x94b9` | **`+0x74`** |
| `__AUTH_CONST.__cfstring` | `0x4c40` | `0x4ca0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xac5c` | `0xac8c` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x2c8` | `0x2e0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x36e8` | `0x3700` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x24b8` | `0x24d0` | **`+0x18`** |
| `__TEXT.__const` | `0x1330` | `0x1320` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x12d8` | `0x12d0` | **`-0x8`** |
| `__AUTH_CONST.__objc_const` | `0x17048` | `0x17050` | **`+0x8`** |

### Other Changes

```diff

-826.0.0.0.1
+833.0.0.0.0

-  Functions: 3636
-  Symbols:   6878
-  CStrings:  1994
+  Functions: 3639
+  Symbols:   6880
+  CStrings:  2000
Symbols:
+ -[MCMContainerCache _queue_containerClassCacheForContainerClassPath:initialGeneration:]
+ -[MCMContainerCache _queue_createContainerClassCacheForContainerClassPath:initialGeneration:]
+ -[MCMContainerCache _queue_resetClassCache:]
+ -[MCMContainerClassCache initWithContainerClassPath:cacheEntryClass:targetQueue:initialGeneration:userIdentityCache:]
+ GCC_except_table1016
+ GCC_except_table1018
+ GCC_except_table1074
+ GCC_except_table1083
+ GCC_except_table1087
+ GCC_except_table1137
+ GCC_except_table1153
+ GCC_except_table1155
+ GCC_except_table1159
+ GCC_except_table1164
+ GCC_except_table1167
+ GCC_except_table1173
+ GCC_except_table1175
+ GCC_except_table1177
+ GCC_except_table1179
+ GCC_except_table1182
+ GCC_except_table1184
+ GCC_except_table1188
+ GCC_except_table1190
+ GCC_except_table1192
+ GCC_except_table1198
+ GCC_except_table1201
+ GCC_except_table1203
+ GCC_except_table1211
+ GCC_except_table1226
+ GCC_except_table1230
+ GCC_except_table1232
+ GCC_except_table1287
+ GCC_except_table1297
+ GCC_except_table1328
+ GCC_except_table1563
+ GCC_except_table1713
+ GCC_except_table1717
+ GCC_except_table1877
+ GCC_except_table1883
+ GCC_except_table1984
+ GCC_except_table2118
+ GCC_except_table2259
+ GCC_except_table2277
+ GCC_except_table2342
+ GCC_except_table2400
+ GCC_except_table2421
+ GCC_except_table2490
+ GCC_except_table2502
+ GCC_except_table2571
+ GCC_except_table2581
+ GCC_except_table2606
+ GCC_except_table2629
+ GCC_except_table2639
+ GCC_except_table2663
+ GCC_except_table2668
+ GCC_except_table2673
+ GCC_except_table2731
+ GCC_except_table2880
+ GCC_except_table2956
+ GCC_except_table985
+ _container_notify_create_with_initial_gen_count
- -[MCMContainerCache _queue_containerClassCacheForContainerClassPath:]
- GCC_except_table1015
- GCC_except_table1017
- GCC_except_table1073
- GCC_except_table1082
- GCC_except_table1086
- GCC_except_table1135
- GCC_except_table1152
- GCC_except_table1154
- GCC_except_table1158
- GCC_except_table1163
- GCC_except_table1166
- GCC_except_table1172
- GCC_except_table1174
- GCC_except_table1176
- GCC_except_table1178
- GCC_except_table1181
- GCC_except_table1183
- GCC_except_table1187
- GCC_except_table1189
- GCC_except_table1191
- GCC_except_table1197
- GCC_except_table1200
- GCC_except_table1202
- GCC_except_table1210
- GCC_except_table1225
- GCC_except_table1229
- GCC_except_table1231
- GCC_except_table1286
- GCC_except_table1296
- GCC_except_table1327
- GCC_except_table1562
- GCC_except_table1712
- GCC_except_table1716
- GCC_except_table1876
- GCC_except_table1882
- GCC_except_table1983
- GCC_except_table2117
- GCC_except_table2258
- GCC_except_table2275
- GCC_except_table2341
- GCC_except_table2399
- GCC_except_table2420
- GCC_except_table2489
- GCC_except_table2501
- GCC_except_table2570
- GCC_except_table2580
- GCC_except_table2605
- GCC_except_table2628
- GCC_except_table2638
- GCC_except_table2660
- GCC_except_table2662
- GCC_except_table2670
- GCC_except_table2728
- GCC_except_table2874
- GCC_except_table2953
- GCC_except_table984
- _container_notify_create
- _container_notify_set_class
CStrings:
+ "17:37:26"
+ "Failed creating new class cache; classPath = %@"
+ "Failed to get existing generation on class cache setup; containerClassPath = %@"
+ "Jun  9 2026"
+ "MobileContainerManager-833~126"
+ "Unexpected difference between initial generation and existing; initial = %llu, existing = %llu, token = %d, containerClassPath = %@"
+ "com.apple.TVRemoteUIService"
+ "com.apple.TVRemoteUIService.TVRemoteIntentExtension"
+ "com.apple.TVRemoteUIService.TVRemoteWidget"
- "06:35:23"
- "May 22 2026"
- "MobileContainerManager-826.0.0.0.1~39"
```
