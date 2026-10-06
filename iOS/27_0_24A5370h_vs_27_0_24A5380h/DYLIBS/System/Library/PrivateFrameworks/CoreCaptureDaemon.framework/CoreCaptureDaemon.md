## CoreCaptureDaemon

> `/System/Library/PrivateFrameworks/CoreCaptureDaemon.framework/CoreCaptureDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5aea4` | `0x5b998` | **`+0xaf4`** |
| `__TEXT.__oslogstring` | `0xb4fa` | `0xb71b` | **`+0x221`** |
| `__TEXT.__cstring` | `0xb956` | `0xbb5e` | **`+0x208`** |
| `__TEXT.__const` | `0x538` | `0x638` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x1230` | `0x1268` | **`+0x38`** |
| `__DATA.__bss` | `0x50` | `0x28` | **`-0x28`** |
| `__DATA_CONST.__const` | `0x390` | `0x3b0` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x298` | `0x2b8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x9c0` | `0x9c8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7c8` | `0x7d0` | **`+0x8`** |

### Other Changes

```diff

-1355.41.0.0.0
+1355.42.0.0.0

-  Functions: 611
-  Symbols:   1147
-  CStrings:  1231
+  Functions: 615
+  Symbols:   1152
+  CStrings:  1237
Symbols:
+ GCC_except_table278
+ GCC_except_table355
+ GCC_except_table356
+ GCC_except_table403
+ GCC_except_table414
+ GCC_except_table417
+ GCC_except_table419
+ GCC_except_table420
+ GCC_except_table456
+ GCC_except_table465
+ GCC_except_table467
+ GCC_except_table472
+ GCC_except_table474
+ GCC_except_table477
+ GCC_except_table487
+ GCC_except_table497
+ GCC_except_table535
+ GCC_except_table563
+ GCC_except_table572
+ GCC_except_table584
+ GCC_except_table585
+ GCC_except_table609
+ GCC_except_table610
+ GCC_except_table70
+ __ZN15CCPipeInterface15extractPipeNameEPK10__CFStringPcm
+ __ZN15CCPipeInterface16extractOwnerNameEPK10__CFStringPcm
+ __ZN15CCPipeInterface16setDispatchQueueEb
+ __ZN15CCPipeInterface18resetDispatchQueueEb
+ ____ZN15CCPipeInterface18resetDispatchQueueEb_block_invoke
+ _dispatch_set_target_queue
- GCC_except_table274
- GCC_except_table351
- GCC_except_table352
- GCC_except_table399
- GCC_except_table410
- GCC_except_table411
- GCC_except_table413
- GCC_except_table416
- GCC_except_table452
- GCC_except_table459
- GCC_except_table461
- GCC_except_table466
- GCC_except_table468
- GCC_except_table473
- GCC_except_table475
- GCC_except_table493
- GCC_except_table531
- GCC_except_table559
- GCC_except_table568
- GCC_except_table580
- GCC_except_table581
- GCC_except_table605
- GCC_except_table606
- GCC_except_table72
- __ZN15CCPipeInterface16setDispatchQueueEv
CStrings:
+ "CCDaemon::%s initial scan not complete, staying active"
+ "CCPipeInterface::resetDispatchQueue re-targeted dispatch source to capture queue entry:%u Owner:%s Pipe:%s\n"
+ "CCPipeInterface::resetDispatchQueue re-targeted notification port to capture queue entry:%u Owner:%s Pipe:%s\n"
+ "CCPipeInterface::setDispatchQueue entry:%u Owner:%s Pipe:%s\n"
+ "CCPipeInterface::setDispatchQueue failed to create a serial dispatch queue for continuous pipe entry:%u Owner:%s Pipe:%s\n"
+ "CCPipeInterface::setDispatchQueue re-targeted dispatch source to continuous queue entry:%u Owner:%s Pipe:%s\n"
+ "CCPipeInterface::setDispatchQueue re-targeted notification port to continuous queue entry:%u Owner:%s Pipe:%s\n"
+ "result=init_scan_pending"
- "CCPipeInterface::setDispatchQueue entry:%u fConnectRef(%d)\n"
- "CCPipeInterface::setDispatchQueue failed to create a serial dispatch queue for continuous pipe\n"
```
