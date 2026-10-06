## CoreAnalytics

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b298` | `0x2b504` | **`+0x26c`** |
| `__AUTH_CONST.__const` | `0xae0` | `0xb48` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0xfcb` | `0x101b` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1240` | `0x1258` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x3824` | `0x3838` | **`+0x14`** |

### Other Changes

```diff

-564.0.0.0.0
+569.0.5.0.0

-  Functions: 811
-  Symbols:   1306
-  CStrings:  460
+  Functions: 818
+  Symbols:   1311
+  CStrings:  461
Symbols:
+ GCC_except_table101
+ GCC_except_table103
+ GCC_except_table104
+ GCC_except_table120
+ GCC_except_table121
+ GCC_except_table123
+ GCC_except_table185
+ GCC_except_table202
+ GCC_except_table206
+ GCC_except_table221
+ GCC_except_table222
+ GCC_except_table224
+ GCC_except_table225
+ GCC_except_table229
+ GCC_except_table232
+ GCC_except_table236
+ GCC_except_table244
+ GCC_except_table247
+ GCC_except_table255
+ GCC_except_table256
+ GCC_except_table258
+ GCC_except_table259
+ GCC_except_table260
+ GCC_except_table263
+ GCC_except_table268
+ GCC_except_table270
+ GCC_except_table271
+ GCC_except_table273
+ GCC_except_table278
+ GCC_except_table280
+ GCC_except_table287
+ GCC_except_table288
+ GCC_except_table289
+ GCC_except_table290
+ GCC_except_table291
+ GCC_except_table292
+ GCC_except_table304
+ GCC_except_table319
+ GCC_except_table320
+ GCC_except_table322
+ GCC_except_table329
+ GCC_except_table333
+ GCC_except_table334
+ GCC_except_table337
+ GCC_except_table338
+ GCC_except_table342
+ GCC_except_table53
+ GCC_except_table60
+ GCC_except_table74
+ GCC_except_table83
+ GCC_except_table91
+ GCC_except_table92
+ GCC_except_table93
+ GCC_except_table94
+ ____ZN13CoreAnalytics6Client19sendXpcMessage_syncEN10applesauce3xpc4dictE18XPCMessagePrioritybbb_block_invoke_2
+ ___copy_helper_block_e8_32c36_ZTSN10applesauce8dispatch2v15groupE
+ ___copy_helper_block_e8_48c36_ZTSN10applesauce8dispatch2v15groupE
+ ___destroy_helper_block_e8_32c36_ZTSN10applesauce8dispatch2v15groupE
+ ___destroy_helper_block_e8_48c36_ZTSN10applesauce8dispatch2v15groupE
- GCC_except_table108
- GCC_except_table109
- GCC_except_table117
- GCC_except_table179
- GCC_except_table180
- GCC_except_table194
- GCC_except_table196
- GCC_except_table209
- GCC_except_table211
- GCC_except_table212
- GCC_except_table213
- GCC_except_table216
- GCC_except_table220
- GCC_except_table230
- GCC_except_table235
- GCC_except_table237
- GCC_except_table238
- GCC_except_table239
- GCC_except_table250
- GCC_except_table252
- GCC_except_table253
- GCC_except_table254
- GCC_except_table261
- GCC_except_table262
- GCC_except_table264
- GCC_except_table265
- GCC_except_table266
- GCC_except_table274
- GCC_except_table275
- GCC_except_table282
- GCC_except_table283
- GCC_except_table284
- GCC_except_table285
- GCC_except_table286
- GCC_except_table295
- GCC_except_table298
- GCC_except_table300
- GCC_except_table305
- GCC_except_table308
- GCC_except_table309
- GCC_except_table310
- GCC_except_table325
- GCC_except_table326
- GCC_except_table328
- GCC_except_table47
- GCC_except_table69
- GCC_except_table76
- GCC_except_table77
- GCC_except_table85
- GCC_except_table87
- GCC_except_table88
- GCC_except_table95
- GCC_except_table97
- GCC_except_table98
CStrings:
+ "waitForSend timed out after %u ms flushing event to analyticsd; delivery not confirmed"
```
