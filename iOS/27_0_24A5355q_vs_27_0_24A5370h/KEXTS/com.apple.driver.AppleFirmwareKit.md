## com.apple.driver.AppleFirmwareKit

> `com.apple.driver.AppleFirmwareKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xbb0` | **`+0xbb0`** |
| `__TEXT_EXEC.__text` | `0x4dad4` | `0x4e224` | **`+0x750`** |
| `__DATA_CONST.__const` | `0x11790` | `0x11980` | **`+0x1f0`** |
| `__TEXT.__cstring` | `0x5630` | `0x57c5` | **`+0x195`** |
| `__DATA_CONST.__kalloc_type` | `0x1e80` | `0x1d80` | **`-0x100`** |
| `__TEXT.__os_log` | `0x1781` | `0x170d` | **`-0x74`** |
| `__DATA.__common` | `0x8e0` | `0x908` | **`+0x28`** |
| `__TEXT.__const` | `0x298` | `0x2a8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5e0` | `0x5d8` | **`-0x8`** |

### Other Changes

```diff

-736.0.0.502.1
-  Functions: 2623
+743.0.0.0.1
+  Functions: 2640

-  CStrings:  868
+  CStrings:  874
CStrings:
+ "\"((&_eventQ)->stqh_first == __null)\" @%s:%d"
+ "\"AFKEPInterfaceKextV2::%s: command response timeout (%u ms) on %s, \" \"commandID:%u, EP:%s\" @%s:%d"
+ "\"_handleCommandAction == __null\" @%s:%d"
+ "\"_handleReportAction == __null\" @%s:%d"
+ "\"_handleResponseAction == __null\" @%s:%d"
+ "\"_pipe\" @%s:%d"
+ "\"command && commandLength && handler\" @%s:%d"
+ "\"packetSize >= sizeof(PublishReport)\" @%s:%d"
+ "121111"
+ "12111111112"
+ "1211111212221212111112"
+ "12111112122212121111121"
+ "121111121222121211111211112111112221111212111122111122221112"
+ "AFKEPInterfaceServiceEvent"
+ "AFKUserDataPipe_kext.cpp"
+ "CommandTimeoutMS"
+ "cmdTimeoutTimerAction"
+ "i48@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{IOWorkLoop}^{OSArray}B}16I24Q28^{AFKMemoryDescriptor=^^?i^{AFKMemoryDescriptorImpl}B}36I44"
+ "i64@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{IOWorkLoop}^{OSArray}B}16^{AFKEPCommandContextInterface=^^?}24I32Q36r^v44Q52I60"
+ "site.AFKEPInterfaceServiceEvent"
+ "v56@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{IOWorkLoop}^{OSArray}B}16I24Q28r^v36Q44I52"
+ "v60@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{IOWorkLoop}^{OSArray}B}16^v24i32Q36r^v44Q52"
+ "v64@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{IOWorkLoop}^{OSArray}B}16^{AFKEPCommandContextInterface=^^?}24I32Q36r^v44Q52I60"
- "\"command && commandLength && respBuffer && respBufferLength\" @%s:%d"
- "\"event->packetSize >= sizeof(PublishReport)\" @%s:%d"
- "%s(%s:%#llx): handleReportAction SetAbortedHandler 0x%x\n"
- "%s(%s:%#llx): handleResponseAction SetAbortedHandler 0x%x\n"
- "112122"
- "121111121112"
- "1211111212221212111121"
- "121111121222121211112111121111122211112121111221111222211"
- "i48@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{OSArray}B}16I24Q28^{AFKMemoryDescriptor=^^?i^{AFKMemoryDescriptorImpl}B}36I44"
- "i64@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{OSArray}B}16^{AFKEPCommandContextInterface=^^?}24I32Q36r^v44Q52I60"
- "if-num"
- "site.Event"
- "site.PublishEvent"
- "site.TerminateEvent"
- "v56@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{OSArray}B}16I24Q28r^v36Q44I52"
- "v60@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{OSArray}B}16^v24i32Q36r^v44Q52"
- "v64@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{OSArray}B}16^{AFKEPCommandContextInterface=^^?}24I32Q36r^v44Q52I60"
```
