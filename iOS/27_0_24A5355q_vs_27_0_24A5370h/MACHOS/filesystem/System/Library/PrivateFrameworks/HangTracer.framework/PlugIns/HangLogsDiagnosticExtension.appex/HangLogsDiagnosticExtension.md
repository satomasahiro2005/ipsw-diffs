## HangLogsDiagnosticExtension

> `/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/HangLogsDiagnosticExtension.appex/HangLogsDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13370` | `0x1331c` | **`-0x54`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-412.0.0.0.0
+415.0.0.0.0
Functions:
~ _checkForAssertionOverlap : 1232 -> 1264
~ sub_100001bc4 -> sub_100001be4 : 1344 -> 1340
~ _getHTForegroundTrackingDurations : 1284 -> 1280
~ _htAddAppForegroundDurations : 536 -> 532
~ sub_1000031fc -> sub_100003210 : 412 -> 408
~ _getHangHistoryRecords : 1216 -> 1212
~ _generateStringFormatForFGAppDurations : 600 -> 596
~ _getHangHistoryDescriptionWithForegroundSources : 2140 -> 2160
~ sub_100004d80 -> sub_100004d9c : 752 -> 748
~ sub_10000510c -> sub_100005124 : 276 -> 272
~ sub_100005220 -> sub_100005234 : 276 -> 272
~ sub_100005334 -> sub_100005344 : 272 -> 268
~ sub_100005444 -> sub_100005450 : 272 -> 268
~ sub_100005554 -> sub_10000555c : 288 -> 284
~ sub_100005674 -> sub_100005678 : 312 -> 308
~ sub_1000057ac : 176 -> 172
~ sub_1000095bc -> sub_1000095b8 : 1332 -> 1324
~ __isValidStateInfoSortedArray : 784 -> 780
~ _calculateDurationInCPURoleFromStateInfoDict : 392 -> 388
~ _createStateInfoSortedArrayWithPtr : 804 -> 808
~ sub_10000c6d0 -> sub_10000c6c0 : 1572 -> 1568
~ sub_10000e314 -> sub_10000e300 : 744 -> 740
~ sub_10000f210 -> sub_10000f1f8 : 288 -> 280
~ sub_10000f3c8 -> sub_10000f3a8 : 300 -> 292
~ sub_10000f58c -> sub_10000f564 : 300 -> 292
~ sub_100010c4c -> sub_100010c1c : 624 -> 616
~ sub_100011718 -> sub_1000116e0 : 664 -> 668
~ sub_100011a88 -> sub_100011a54 : 296 -> 292
~ sub_100011e3c -> sub_100011e04 : 896 -> 868
```
