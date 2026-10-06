## com.apple.plugin.IOgPTPPlugin

> `com.apple.plugin.IOgPTPPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x6e43c` | `0x6fcec` | **`+0x18b0`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xe40` | **`+0xe40`** |
| `__TEXT.__os_log` | `0x1bd96` | `0x1c46f` | **`+0x6d9`** |
| `__TEXT.__cstring` | `0x6bd6` | `0x6cc3` | **`+0xed`** |
| `__DATA_CONST.__auth_got` | `0x718` | `0x720` | **`+0x8`** |

### Other Changes

```diff

-1500.96.0.0.0
-  Functions: 1633
+1501.1.0.0.0
+  Functions: 1637

-  CStrings:  1534
+  CStrings:  1569
CStrings:
+ "  %s(%s): Announce has null grandmasterIdentity from source 0x%016llx:%u\n"
+ "  %s(%s): port-manager refcount for %s (Unicast%s) already balanced (kIOReturnNotFound)\n"
+ "  %s(%s): purging stale Unicast%s entry for %s (hadPort=%d)\n"
+ "  %s(%s): unexpected 0x%08x rebalancing port-manager refcount for %s (Unicast%s)\n"
+ "%s %s %p terminated for %s, running cleanup\n"
+ "%s %s %p terminated with no %s property, dropping cleanup\n"
+ "%s %s %p terminated with no BSD Name property, dropping cleanup\n"
+ "%s called with NULL ifName, dropping cleanup\n"
+ "%s domain interface %s terminated\n"
+ "%s failed to allocate domains iterator for %s, leaving state intact\n"
+ "%s failed to allocate domainsArray for %s, leaving state intact\n"
+ "%s::%s UnicastUDPv4EtE port attach() failed for interface %s, provider %p (isInactive=%d)\n"
+ "%s::%s UnicastUDPv4EtE port init() failed for interface %s\n"
+ "%s::%s UnicastUDPv4EtE port start() failed for interface %s, provider %p (isInactive=%d)\n"
+ "%s::%s UnicastUDPv4PtP port attach() failed for interface %s, provider %p (isInactive=%d)\n"
+ "%s::%s UnicastUDPv4PtP port init() failed for interface %s\n"
+ "%s::%s UnicastUDPv4PtP port start() failed for interface %s, provider %p (isInactive=%d)\n"
+ "%s::%s UnicastUDPv6EtE port attach() failed for interface %s, provider %p (isInactive=%d)\n"
+ "%s::%s UnicastUDPv6EtE port init() failed for interface %s\n"
+ "%s::%s UnicastUDPv6EtE port start() failed for interface %s, provider %p (isInactive=%d)\n"
+ "%s::%s UnicastUDPv6PtP port attach() failed for interface %s, provider %p (isInactive=%d)\n"
+ "%s::%s UnicastUDPv6PtP port init() failed for interface %s\n"
+ "%s::%s UnicastUDPv6PtP port start() failed for interface %s, provider %p (isInactive=%d)\n"
+ "12111112122212121111111111111111121121121111111112222222222222112112111112122222111112112112222"
+ "Failed to add tsninterface terminated notifier.\n"
+ "IOTimeSyncgPTPManager %s dumped controller adapter for %s\n"
+ "IOTimeSyncgPTPManager %s dumped interface adapter for %s\n"
+ "IOTimeSyncgPTPManager %s dumped port manager for %s\n"
+ "LinkLayerEtE"
+ "LinkLayerPtP"
+ "NULL == fTSNInterfaceTerminatedNotifier"
+ "UDPv4EtE"
+ "UDPv4PtP"
+ "UDPv6EtE"
+ "UDPv6PtP"
+ "addUnicastUDPv4Port"
+ "addUnicastUDPv6Port"
+ "cleanupForInterfaceByName"
+ "notifier == fTSNInterfaceTerminatedNotifier"
+ "tsnInterfaceTerminated"
- "%s domain interface %s terminated"
- "121111121222121211111111111111111211211211111112222222222222112112111112122222111112112112222"
- "IOTimeSyncgPTPManager interfaceTerminated dumped controller adapter for %s\n"
- "IOTimeSyncgPTPManager interfaceTerminated dumped interface adapter for %s\n"
- "IOTimeSyncgPTPManager interfaceTerminated dumped port manager for %s\n"
```
