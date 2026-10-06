## com.apple.plugin.IOgPTPPlugin

> `com.apple.plugin.IOgPTPPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x71260` | `0x7059c` | **`-0xcc4`** |
| `__TEXT.__os_log` | `0x1c585` | `0x1c00e` | **`-0x577`** |
| `__TEXT.__cstring` | `0x6d31` | `0x6bdc` | **`-0x155`** |
| `__TEXT_EXEC.__auth_stubs` | `0xe40` | `0xdd0` | **`-0x70`** |
| `__DATA_CONST.__kalloc_type` | `0x980` | `0x940` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x720` | `0x6e8` | **`-0x38`** |

### Other Changes

```diff

-1510.7.0.0.0
-  Functions: 1641
+1510.8.0.0.0
+  Functions: 1619

-  CStrings:  1577
+  CStrings:  1555
CStrings:
- "2222222222222222221"
- "IOTimeSyncgPTPManagerDaemonClient::dockReplayTimestamps: fProcessID = %u\n"
- "NULL == bsdName"
- "NULL == interfaces"
- "[%u] t1=%llu,t2=%llu,t3=%llu,t4=%llu,seq=%llu\n"
- "bsdName = %s"
- "bsdName == nullptr\n"
- "bytesRead == replayLength"
- "bytesRead == replayTimestampsLength"
- "interface != nullptr"
- "interface == nullptr"
- "interface is not a test interface\n"
- "interface not found\n"
- "interfaces == nullptr\n"
- "mem != nullptr"
- "mem->complete() == kIOReturnSuccess"
- "mem->prepare(kIODirectionOutIn) == kIOReturnSuccess"
- "obj == nullptr"
- "ret == kIOReturnSuccess"
- "site.TSReplayTimestamps"
- "syncRate = %lld portType = %llu timestampCount = %llu\n"
- "task != nullptr"
```
