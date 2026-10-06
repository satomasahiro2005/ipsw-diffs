## Message

> `/System/Library/PrivateFrameworks/Message.framework/Message`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaf3a2c` | `0xaf5248` | **`+0x181c`** |
| `__AUTH_CONST.__const` | `0xac010` | `0xac300` | **`+0x2f0`** |
| `__TEXT.__swift5_capture` | `0x33494` | `0x335bc` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x27b40` | `0x27c00` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x369e4` | `0x36a70` | **`+0x8c`** |
| `__DATA.__data` | `0xe958` | `0xe908` | **`-0x50`** |
| `__TEXT.__eh_frame` | `0x18634` | `0x1860c` | **`-0x28`** |
| `__TEXT.__cstring` | `0x31346` | `0x31366` | **`+0x20`** |
| `__AUTH.__data` | `0xb408` | `0xb3f8` | **`-0x10`** |
| `__TEXT.__const` | `0x6b5e8` | `0x6b5d8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1ea08` | `0x1ea00` | **`-0x8`** |

### Other Changes

```diff

-3897.100.8.2.5
+3901.100.1.2.7

-  Functions: 48452
-  Symbols:   21324
-  CStrings:  8521
+  Functions: 48468
+  Symbols:   21326
+  CStrings:  8524
Symbols:
+ -[MFSearchableIndexManager_iOS initWithDatabase:messagePersistence:richLinkPersistence:hookRegistry:accountsProvider:serverMessagesIndexerProvider:]
+ GCC_except_table219
+ GCC_except_table236
+ GCC_except_table237
+ GCC_except_table271
+ GCC_except_table276
+ GCC_except_table330
+ GCC_except_table336
+ GCC_except_table340
+ GCC_except_table358
+ GCC_except_table364
+ GCC_except_table372
+ GCC_except_table383
+ GCC_except_table398
+ GCC_except_table401
+ GCC_except_table411
+ GCC_except_table420
+ GCC_except_table451
+ GCC_except_table456
+ GCC_except_table457
+ GCC_except_table478
+ GCC_except_table481
+ GCC_except_table486
+ GCC_except_table487
+ GCC_except_table496
+ GCC_except_table497
+ GCC_except_table501
+ GCC_except_table502
+ GCC_except_table506
+ GCC_except_table510
+ GCC_except_table514
+ GCC_except_table520
+ GCC_except_table532
+ GCC_except_table535
+ GCC_except_table557
+ GCC_except_table565
+ GCC_except_table566
+ ___85-[MFMailMessageLibrary _writeEmlxData:toFile:protectionClass:purgeable:dateReceived:]_block_invoke
+ ___85-[MFMailMessageLibrary _writeEmlxData:toFile:protectionClass:purgeable:dateReceived:]_block_invoke_2
+ ___swift_closure_destructor.7Tm
+ _symbolic Siz_Xx
- -[MFSearchableIndexManager_iOS initWithDatabase:messagePersistence:richLinkPersistence:hookRegistry:serverMessagesIndexerProvider:]
- GCC_except_table238
- GCC_except_table239
- GCC_except_table273
- GCC_except_table277
- GCC_except_table278
- GCC_except_table287
- GCC_except_table288
- GCC_except_table321
- GCC_except_table332
- GCC_except_table344
- GCC_except_table350
- GCC_except_table356
- GCC_except_table360
- GCC_except_table377
- GCC_except_table380
- GCC_except_table400
- GCC_except_table403
- GCC_except_table413
- GCC_except_table422
- GCC_except_table453
- GCC_except_table476
- GCC_except_table479
- GCC_except_table484
- GCC_except_table485
- GCC_except_table488
- GCC_except_table489
- GCC_except_table498
- GCC_except_table499
- GCC_except_table504
- GCC_except_table508
- GCC_except_table512
- GCC_except_table516
- GCC_except_table523
- GCC_except_table526
- GCC_except_table555
- GCC_except_table558
- GCC_except_table561
- ___swift_closure_destructor.8Tm
CStrings:
+ "<none>"
+ "Backfill completed after downloading %ld messages."
+ "Backfill was cancelled after downloading %ld messages."
+ "Bootstrap: no accounts need. Completing."
+ "Error %{public}@ Attempting to get the item replacement directory for file %@, falling back to %{public}@"
+ "RaveResetBackFillMessageBodiesStages"
+ "[%.*hhx-%.*X] Completing back-fill sync (id: %hu, host: %{public}s, status: %d."
+ "[%.*hhx-%.*X] Starting back-fill sync=#%u, id=%hu, host=%{public}s, policy=%@"
- "Backfill completed."
- "Backfill was cancelled."
- "Bootstrap: no accounts need back-fill. Completing."
- "[%.*hhx-%.*X] Completing back-fill sync (id: %hu, status: %d."
- "[%.*hhx-%.*X] Starting back-fill sync=#%u, id=%hu, policy=%@"
```
