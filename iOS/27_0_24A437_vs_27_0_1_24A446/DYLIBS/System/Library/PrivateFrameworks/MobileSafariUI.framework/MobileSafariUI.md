## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ee578` | `0x2ee354` | **`-0x224`** |
| `__TEXT.__gcc_except_tab` | `0x1f4f4` | `0x1f478` | **`-0x7c`** |
| `__DATA_CONST.__const` | `0x98c0` | `0x9910` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xdd20` | `0xdd60` | **`+0x40`** |
| `__TEXT.__cstring` | `0x10a84` | `0x10ab4` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x24d5c` | `0x24d7c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x10298` | `0x10288` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0x33458` | `0x33460` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x186f0` | `0x186f8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-625.1.29.10.29
+625.1.29.10.33

-  Functions: 16270
-  Symbols:   23028
-  CStrings:  3283
+  Functions: 16271
+  Symbols:   23029
+  CStrings:  3285
Symbols:
+ -[BrowserController _beginSiriReaderConnection:title:text:identifier:readerContext:activeTabDocument:activationSource:invocationDescription:]
+ -[TabCollectionViewManager evaluatePostponedSnapshotInvalidations]
+ GCC_except_table1326
+ GCC_except_table1330
+ GCC_except_table1332
+ GCC_except_table1335
+ GCC_except_table1338
+ GCC_except_table1346
+ GCC_except_table1353
+ GCC_except_table1361
+ GCC_except_table1363
+ GCC_except_table1436
+ ___141-[BrowserController _beginSiriReaderConnection:title:text:identifier:readerContext:activeTabDocument:activationSource:invocationDescription:]_block_invoke
+ ___141-[BrowserController _beginSiriReaderConnection:title:text:identifier:readerContext:activeTabDocument:activationSource:invocationDescription:]_block_invoke_2
+ ___141-[BrowserController _beginSiriReaderConnection:title:text:identifier:readerContext:activeTabDocument:activationSource:invocationDescription:]_block_invoke_3
+ ___39-[BrowserController didEnterBackground]_block_invoke_3
+ ___block_descriptor_112_ea8_32s40s48s56s64s72s80s88r96w_e17_v16?0"UIImage"8lr88l8w96l8s32l8s40l8s48l8s56l8s64l8s72l8s80l8
+ ___block_descriptor_40_ea8_32bs_e36_v24?0"LPLinkMetadata"8"NSError"16ls32l8
+ ___block_descriptor_56_ea8_32s40bs48r_e5_v8?0lr48l8s32l8s40l8
- -[BrowserController _flushPendingSnapshotsDidComplete]
- GCC_except_table1312
- GCC_except_table1317
- GCC_except_table1327
- GCC_except_table1331
- GCC_except_table1334
- GCC_except_table1337
- GCC_except_table1341
- GCC_except_table1347
- GCC_except_table1354
- GCC_except_table1362
- GCC_except_table1435
- ___48-[BrowserController _siriReadThisMenuInvocation]_block_invoke
- ___48-[BrowserController _siriReadThisMenuInvocation]_block_invoke_2
- ___49-[BrowserController _siriReadThisVocalInvocation]_block_invoke
- ___49-[BrowserController _siriReadThisVocalInvocation]_block_invoke_2
- ___54-[BrowserController _flushPendingSnapshotsDidComplete]_block_invoke
- ___block_descriptor_96_ea8_32s40s48s56s64s72s80r88w_e36_v24?0"LPLinkMetadata"8"NSError"16lw88l8r80l8s32l8s40l8s48l8s56l8s64l8s72l8
CStrings:
+ "Safari requested starting playback because of %{public}@"
+ "Timed out waiting for link metadata; starting playback without a leading image"
+ "app intent based invocation"
+ "menu based invocation"
- "Safari requested starting playback because of app intent based invocation"
- "Safari requested starting playback because of menu based invocation"
```
