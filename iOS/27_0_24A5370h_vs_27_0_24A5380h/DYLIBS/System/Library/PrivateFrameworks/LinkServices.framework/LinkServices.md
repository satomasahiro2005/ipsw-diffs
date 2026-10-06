## LinkServices

> `/System/Library/PrivateFrameworks/LinkServices.framework/LinkServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x33d0` | `0x3920` | **`+0x550`** |
| `__DATA_DIRTY.__objc_data` | `0x21f8` | `0x1ca8` | **`-0x550`** |
| `__TEXT.__text` | `0x14cc04` | `0x14ce00` | **`+0x1fc`** |
| `__AUTH_CONST.__objc_const` | `0x15258` | `0x152b8` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x71a2` | `0x71f7` | **`+0x55`** |
| `__TEXT.__cstring` | `0xbaf7` | `0xbb3d` | **`+0x46`** |
| `__TEXT.__objc_methlist` | `0xa820` | `0xa850` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x83e0` | `0x8400` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d90` | `0x4db0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1650` | `0x1648` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xaac` | `0xab4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1830` | `0x1838` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1e08` | `0x1e10` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x64b0` | `0x64a8` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x2d2a` | `0x2d24` | **`-0x6`** |

### Other Changes

```diff

-301.0.42.7.0
+301.0.43.6.0

-  Functions: 9744
-  Symbols:   8910
-  CStrings:  2018
+  Functions: 9748
+  Symbols:   8914
+  CStrings:  2020
Symbols:
+ -[LNConnection lastSentContext]
+ -[LNConnection setLastSentContext:]
+ -[LNQueryEntityOptions displayRepresentationComponents]
+ -[LNQueryEntityOptions setDisplayRepresentationComponents:]
+ GCC_except_table1066
+ GCC_except_table1076
+ GCC_except_table1077
+ GCC_except_table1080
+ GCC_except_table1087
+ GCC_except_table1112
+ GCC_except_table1131
+ GCC_except_table1132
+ GCC_except_table1175
+ GCC_except_table1176
+ GCC_except_table1183
+ GCC_except_table1194
+ GCC_except_table1198
+ GCC_except_table1205
+ GCC_except_table1210
+ GCC_except_table1223
+ GCC_except_table1224
+ GCC_except_table1238
+ GCC_except_table1258
+ GCC_except_table1270
+ GCC_except_table1291
+ GCC_except_table1295
+ GCC_except_table1561
+ GCC_except_table1572
+ GCC_except_table1593
+ GCC_except_table1603
+ GCC_except_table1608
+ GCC_except_table1621
+ GCC_except_table1622
+ GCC_except_table1746
+ GCC_except_table1767
+ GCC_except_table1778
+ GCC_except_table1787
+ GCC_except_table1805
+ GCC_except_table1827
+ GCC_except_table1839
+ GCC_except_table1855
+ GCC_except_table1913
+ GCC_except_table1918
+ GCC_except_table1945
+ GCC_except_table1955
+ GCC_except_table1967
+ GCC_except_table1979
+ GCC_except_table1991
+ GCC_except_table2003
+ GCC_except_table2015
+ GCC_except_table2031
+ GCC_except_table2043
+ GCC_except_table2054
+ GCC_except_table2066
+ GCC_except_table2078
+ GCC_except_table2090
+ GCC_except_table2100
+ GCC_except_table2114
+ GCC_except_table2124
+ GCC_except_table2136
+ GCC_except_table2161
+ GCC_except_table2175
+ GCC_except_table2186
+ GCC_except_table2197
+ GCC_except_table2211
+ GCC_except_table2212
+ GCC_except_table2223
+ GCC_except_table2224
+ GCC_except_table2235
+ GCC_except_table2510
+ GCC_except_table2963
+ GCC_except_table2966
+ GCC_except_table3016
+ GCC_except_table3112
+ GCC_except_table3124
+ GCC_except_table3174
+ GCC_except_table3183
+ GCC_except_table3196
+ GCC_except_table3214
+ GCC_except_table3219
+ GCC_except_table3232
+ GCC_except_table3341
+ GCC_except_table3343
+ _MDItemIsTwoFactorCode
+ _OBJC_IVAR_$_LNConnection._lastSentContext
+ _OBJC_IVAR_$_LNQueryEntityOptions._displayRepresentationComponents
- GCC_except_table1060
- GCC_except_table1074
- GCC_except_table1075
- GCC_except_table1078
- GCC_except_table1085
- GCC_except_table1110
- GCC_except_table1126
- GCC_except_table1129
- GCC_except_table1172
- GCC_except_table1173
- GCC_except_table1181
- GCC_except_table1192
- GCC_except_table1196
- GCC_except_table1203
- GCC_except_table1208
- GCC_except_table1219
- GCC_except_table1220
- GCC_except_table1236
- GCC_except_table1256
- GCC_except_table1268
- GCC_except_table1289
- GCC_except_table1293
- GCC_except_table1559
- GCC_except_table1570
- GCC_except_table1591
- GCC_except_table1601
- GCC_except_table1604
- GCC_except_table1619
- GCC_except_table1620
- GCC_except_table1744
- GCC_except_table1765
- GCC_except_table1776
- GCC_except_table1785
- GCC_except_table1803
- GCC_except_table1825
- GCC_except_table1837
- GCC_except_table1853
- GCC_except_table1911
- GCC_except_table1916
- GCC_except_table1943
- GCC_except_table1949
- GCC_except_table1965
- GCC_except_table1977
- GCC_except_table1989
- GCC_except_table2001
- GCC_except_table2013
- GCC_except_table2029
- GCC_except_table2041
- GCC_except_table2052
- GCC_except_table2064
- GCC_except_table2076
- GCC_except_table2088
- GCC_except_table2098
- GCC_except_table2112
- GCC_except_table2122
- GCC_except_table2134
- GCC_except_table2159
- GCC_except_table2173
- GCC_except_table2184
- GCC_except_table2195
- GCC_except_table2209
- GCC_except_table2210
- GCC_except_table2221
- GCC_except_table2222
- GCC_except_table2233
- GCC_except_table2508
- GCC_except_table2959
- GCC_except_table2962
- GCC_except_table3012
- GCC_except_table3108
- GCC_except_table3120
- GCC_except_table3170
- GCC_except_table3175
- GCC_except_table3192
- GCC_except_table3210
- GCC_except_table3215
- GCC_except_table3224
- GCC_except_table3337
- GCC_except_table3339
- _get_type_metadata 15Synchronization5MutexVySDySo12RBSAssertionC10Foundation4DateVGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "%{public}@ [Context Setup] Context unchanged from last send, skipping XPC update: %@"
+ "<LNQueryEntityOptions levelOfDetail: %@, componentKinds: %@, requiresStableEntityIdentifiers: %@, propertyResolution: %@, maximumArrayPropertyItemCount: %ld, maximumEntityDepth: %ld, deferredPropertyResolutionTimeout: %g, deferredPropertyResolutionConcurrencyLimit: %ld, displayRepresentationComponents: %ld>"
+ "displayRepresentationComponents"
- "<LNQueryEntityOptions levelOfDetail: %@, componentKinds: %@, requiresStableEntityIdentifiers: %@, propertyResolution: %@, maximumArrayPropertyItemCount: %ld, maximumEntityDepth: %ld, deferredPropertyResolutionTimeout: %g, deferredPropertyResolutionConcurrencyLimit: %ld>"
```
