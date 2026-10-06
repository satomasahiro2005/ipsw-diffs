## AppleEthernetRL

> `/System/Library/Extensions/AppleEthernetRL.kext/AppleEthernetRL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x27514` | `0x27bf4` | **`+0x6e0`** |
| `__TEXT.__cstring` | `0x2822` | `0x2a8f` | **`+0x26d`** |
| `__TEXT_EXEC.__auth_stubs` | `0x740` | `0x720` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x3a0` | `0x390` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x8` | `—` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-161.0.0.0.0
-  Functions: 571
-  Symbols:   1148
-  CStrings:  332
+168.0.0.0.0
+  Functions: 579
+  Symbols:   1154
+  CStrings:  343
Symbols:
+ _IORecursiveLockAlloc
+ _IORecursiveLockFree
+ _ZN15AppleEthernetRL22transmitTimeSyncPacketEPN20IOEthernetController19IOEthernetAVBPacketEy
+ __ZL23re_set_phy_mcu_ram_codeP8re_softcPKtt
+ __ZN15AppleEthernetRL13finalizeRingsEv
+ __ZN15AppleEthernetRL18acquireAllAvbLocksEv
+ __ZN15AppleEthernetRL18releaseAllAvbLocksEv
+ __ZN15AppleEthernetRL19handleCarrierUpdateEP18IOTimerEventSource
+ __ZN15AppleEthernetRL20writeMultiBufferIPC2EhPKvjPh
+ __ZN15AppleEthernetRL23acquireAllWorkLoopLocksEv
+ __ZN15AppleEthernetRL23releaseAllWorkLoopLocksEv
+ __ZN15AppleEthernetRL23validateNicProxyHandoffEv
+ __ZZN15AppleEthernetRL13allocateRingsEvE19kalloc_type_view_73
+ __ZZN15AppleEthernetRL13allocateRingsEvE19kalloc_type_view_93
+ __ZZN15AppleEthernetRL13allocateRingsEvE20kalloc_type_view_103
+ __ZZN15AppleEthernetRL14startInterfaceEvE20kalloc_type_view_274
+ __ZZN15AppleEthernetRL14startInterfaceEvE20kalloc_type_view_458
+ __ZZN15AppleEthernetRL4stopEP9IOServiceE20kalloc_type_view_283
+ __ZZN15AppleEthernetRL9freeRingsEvE20kalloc_type_view_116
+ __ZZN15AppleEthernetRL9freeRingsEvE20kalloc_type_view_120
+ __ZZN15AppleEthernetRL9freeRingsEvE20kalloc_type_view_125
+ __ZZN15AppleEthernetRL9freeRingsEvE20kalloc_type_view_131
- _IOLockAlloc
- _IOLockFree
- _IOLockLock
- _IOLockUnlock
- __ZZN15AppleEthernetRL13allocateRingsEvE19kalloc_type_view_63
- __ZZN15AppleEthernetRL13allocateRingsEvE19kalloc_type_view_76
- __ZZN15AppleEthernetRL13allocateRingsEvE19kalloc_type_view_95
- __ZZN15AppleEthernetRL14startInterfaceEvE20kalloc_type_view_224
- __ZZN15AppleEthernetRL14startInterfaceEvE20kalloc_type_view_408
- __ZZN15AppleEthernetRL4stopEP9IOServiceE20kalloc_type_view_271
- __ZZN15AppleEthernetRL9freeRingsEvE20kalloc_type_view_108
- __ZZN15AppleEthernetRL9freeRingsEvE20kalloc_type_view_112
- __ZZN15AppleEthernetRL9freeRingsEvE20kalloc_type_view_117
- __ZZN15AppleEthernetRL9freeRingsEvE20kalloc_type_view_127
- ___chkstk_darwin
- ___chkstk_darwin_probe
CStrings:
+ " (recovered missed link-up edge)"
+ "121111121222121211111112111212221111122221122212122222222222111111222211111121222211221111221111221122221212112222121211222212121122221212112222121211222212121122222221111222121211211222222222211112221222112121121121122222222222222222222222222221111111222111"
+ "[0x%llx] rl::%s(%d): dropping %u local IPv4 beyond FW cap %u\n"
+ "[0x%llx] rl::%s(%d): dropping %u local IPv6 beyond FW cap %u\n"
+ "[0x%llx] rl::%s(%d): dropping %u other IPv4 beyond FW cap %u\n"
+ "[0x%llx] rl::%s(%d): dropping %u other IPv6 beyond FW cap %u\n"
+ "[0x%llx] rl::%s(%d): invalid IPv4 counts: local %u total %u (cap total %u)\n"
+ "[0x%llx] rl::%s(%d): invalid IPv6 counts: local %u total %u (cap total %u)\n"
+ "[0x%llx] rl::%s(%d): invalid wake port counts: UDP %u TCP %u (caps UDP %u TCP %u)\n"
+ "[0x%llx] rl::%s(%d): link_state=%s, media active %d->%d%s\n"
+ "handleCarrierUpdate"
+ "validateNicProxyHandoff"
- "12111112122212121111111211121222111112222112221212222222222211111122221111112122221122111122111122112222121211222212121122221212112222121211222212121122221212112222222111122212121121122222222221111222122211212112112112222222222222222222222222222111111122211"
```
