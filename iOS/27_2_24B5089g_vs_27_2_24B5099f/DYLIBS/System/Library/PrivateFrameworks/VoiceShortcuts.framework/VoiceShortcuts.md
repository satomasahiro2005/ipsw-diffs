## VoiceShortcuts

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/VoiceShortcuts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13fbc4` | `0x13f44c` | **`-0x778`** |
| `__TEXT.__oslogstring` | `0xe838` | `0xe764` | **`-0xd4`** |
| `__TEXT.__cstring` | `0xe2b0` | `0xe1fc` | **`-0xb4`** |
| `__DATA_DIRTY.__data` | `0x2a80` | `0x2a10` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x3e60` | `0x3e00` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x1d10` | `0x1ce8` | **`-0x28`** |
| `__TEXT.__const` | `0x6c48` | `0x6c28` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x4e38` | `0x4e58` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x824` | `0x838` | **`+0x14`** |
| `__DATA.__data` | `0x2650` | `0x2660` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x8918` | `0x8908` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x20f0` | `0x20f8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4448` | `0x4440` | **`-0x8`** |

### Other Changes

```diff

-5111.0.2.0.0
+5113.0.1.1.1

-  Functions: 8036
-  Symbols:   5273
-  CStrings:  2207
+  Functions: 8041
+  Symbols:   5268
+  CStrings:  2201
Symbols:
+ GCC_except_table1046
+ GCC_except_table1063
+ GCC_except_table1093
+ GCC_except_table1152
+ GCC_except_table1158
+ GCC_except_table1160
+ GCC_except_table1163
+ GCC_except_table1169
+ GCC_except_table1220
+ GCC_except_table1266
+ GCC_except_table1270
+ GCC_except_table1284
+ GCC_except_table1299
+ GCC_except_table1305
+ GCC_except_table1337
+ GCC_except_table1341
+ GCC_except_table1359
+ GCC_except_table1363
+ GCC_except_table1377
+ GCC_except_table1379
+ GCC_except_table1383
+ GCC_except_table1401
+ GCC_except_table1404
+ GCC_except_table1418
+ GCC_except_table230
+ GCC_except_table302
+ GCC_except_table324
+ GCC_except_table387
+ GCC_except_table406
+ GCC_except_table489
+ GCC_except_table570
+ GCC_except_table571
+ GCC_except_table584
+ GCC_except_table595
+ GCC_except_table624
+ GCC_except_table783
+ GCC_except_table917
+ GCC_except_table943
+ GCC_except_table949
+ GCC_except_table951
+ GCC_except_table969
+ _WFNotificationUserInfoForTriggerKeys
- -[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]
- -[VCVoiceShortcutManagerAccessWrapper getVoiceShortcutsForAppWithBundleIdentifier:completion:]
- GCC_except_table1050
- GCC_except_table1071
- GCC_except_table1097
- GCC_except_table1156
- GCC_except_table1162
- GCC_except_table1167
- GCC_except_table1168
- GCC_except_table1173
- GCC_except_table1225
- GCC_except_table1271
- GCC_except_table1275
- GCC_except_table1294
- GCC_except_table1304
- GCC_except_table1310
- GCC_except_table1342
- GCC_except_table1346
- GCC_except_table1364
- GCC_except_table1368
- GCC_except_table1382
- GCC_except_table1384
- GCC_except_table1388
- GCC_except_table1406
- GCC_except_table1409
- GCC_except_table1423
- GCC_except_table234
- GCC_except_table306
- GCC_except_table328
- GCC_except_table391
- GCC_except_table410
- GCC_except_table493
- GCC_except_table574
- GCC_except_table575
- GCC_except_table588
- GCC_except_table599
- GCC_except_table628
- GCC_except_table787
- GCC_except_table921
- GCC_except_table947
- GCC_except_table953
- GCC_except_table955
- GCC_except_table973
- ___99-[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]_block_invoke
- ___99-[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]_block_invoke_2
- ___99-[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]_block_invoke_3
- ___block_descriptor_40_e8_32s_e50_v32?0"NSString"8Q16?<v?"NSArray""NSError">24ls32l8
CStrings:
+ " had no readable data blob."
+ "Fetched library with change tag %s has no readable data blob, so we can't merge it. Leaving local alone."
+ "Library change tag "
- "%s Get VoiceShortcuts for apps with bundle IDs = %@"
- "-[VCVoiceShortcutManager getVoiceShortcutsForAppsWithBundleIdentifiers:accessSpecifier:completion:]"
- "Failed to force local library sync for library because database record is invalid"
- "Failed to force local library sync for library because trying to save library record failed: %@"
- "Received library with no data blob. Not handling it and scheduling sync of ours"
- "bundleIdentifiers"
- "bundleIdentifiers are needed"
- "getVoiceShortcutsForAppsWithBundleIdentifiers"
- "v32@?0@\"NSString\"8Q16@?<v@?@\"NSArray\"@\"NSError\">24"
```
