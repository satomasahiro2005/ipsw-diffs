## com.apple.driver.AppleC26Charger

> `com.apple.driver.AppleC26Charger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x11de8` | `0x13df4` | **`+0x200c`** |
| `__DATA_CONST.__const` | `0x58c8` | `0x6250` | **`+0x988`** |
| `__TEXT.__cstring` | `0x1e7e` | `0x27a6` | **`+0x928`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x450` | **`+0x450`** |
| `__DATA_CONST.__kalloc_type` | `0x500` | `0x5c0` | **`+0xc0`** |
| `__DATA.__common` | `0x348` | `0x3c0` | **`+0x78`** |

### Other Changes

```diff

-147.0.0.0.1
-  Functions: 543
+153.0.0.0.0
+  Functions: 603

-  CStrings:  221
+  CStrings:  270
CStrings:
+ "%s: ***** QiAuthProtocol RECEIVED AUTH DATA ***** (len=%lu bytes)\n"
+ "%s: ***** QiAuthProtocol SENDING AUTH DATA ***** (len=%d bytes)\n"
+ "%s: ===== AppleQiAuthProtocol::start() SUCCESS =====\n"
+ "%s: AppleC26AuthProtocol got device stream (number=%d, type=%d)\n"
+ "%s: AppleC26AuthProtocol is not AppleC26DeviceStream\n"
+ "%s: AppleC26AuthProtocol super::start() failed\n"
+ "%s: AppleC26AuthProtocol::sendData called with %d bytes\n"
+ "%s: AppleC26AuthProtocol::start() called\n"
+ "%s: AppleC26AuthProtocol::start() completed successfully\n"
+ "%s: AppleC26AuthProtocolWatch got device stream (number=%d, type=%d)\n"
+ "%s: AppleC26AuthProtocolWatch is not AppleC26DeviceStream\n"
+ "%s: AppleC26AuthProtocolWatch super::start() failed\n"
+ "%s: AppleC26AuthProtocolWatch::sendData called with %d bytes\n"
+ "%s: AppleC26AuthProtocolWatch::start() completed successfully\n"
+ "%s: AppleQiAuthProtocol got device stream (number=%d, type=%d, protocol=%d)\n"
+ "%s: AppleQiAuthProtocol provider is not AppleC26DeviceStream\n"
+ "%s: AppleQiAuthProtocol super::start() failed\n"
+ "%s: AuthProtocol attached to dock\n"
+ "%s: AuthProtocol registered service\n"
+ "%s: AuthProtocol stream created\n"
+ "%s: AuthProtocol stream enabled\n"
+ "%s: AuthProtocolWatch attached to dock\n"
+ "%s: AuthProtocolWatch registered service\n"
+ "%s: AuthProtocolWatch stream created\n"
+ "%s: AuthProtocolWatch stream enabled\n"
+ "%s: Config stream enabled, sending GetDevInfo command\n"
+ "%s: Config stream setup complete, registered service\n"
+ "%s: Processing RetConfig response - payloadDataLen=%zu\n"
+ "%s: Processing RetDevInfo response\n"
+ "%s: QiAuthProtocol attached to dock\n"
+ "%s: QiAuthProtocol auth data sent successfully\n"
+ "%s: QiAuthProtocol registered service\n"
+ "%s: QiAuthProtocol stream created successfully\n"
+ "%s: QiAuthProtocol stream enabled\n"
+ "%s: Received config data - cmdID=0x%02x, dataLen=%zu\n"
+ "%s: RetConfig: configVersion=0x%04x, numStreams=%zu\n"
+ "%s: Sending GetConfig command to enumerate streams\n"
+ "%s: Starting config stream setup\n"
+ "%s: calling _c26Stream->sendData\n"
+ "%s: could not open AuthProtocolWatch stream\n"
+ "%s: could not start device stream, detached; str:%d typ:%d prot:%d\n"
+ "%s: createDeviceStream: streamNumber=%d, streamType=%d, protocolType=%d, deferStart=%d\n"
+ "%s: device stream init or attach failed; str:%d typ:%d prot:%d\n"
+ "%s: device stream started successfully; str:%d typ:%d prot:%d deferStart:%d\n"
+ "%s: received AuthProtocolWatch telegram:%s\n"
+ "%s: sending AuthProtocolWatch telegram:%s\n"
+ "1222222222222222"
+ "AppleC26AuthProtocolWatch"
+ "AppleC26AuthProtocolWatch::start()\n"
+ "AppleC26FFBDataStream"
+ "AppleC26FFBPacket"
+ "site.AppleC26AuthProtocolWatch"
+ "site.AppleC26FFBDataStream"
+ "site.AppleC26FFBPacket"
- "%s: could not start device stream, detached; str:%d typ:%d prot%d\n"
- "%s: createDeviceStream: streamType=%d, protocolType=%d\n"
- "%s:AuthProtocol stream created\n"
- "%s:QiAuthProtocol stream created\n"
- "AppleQiAuthProtocol::start()\n"
```
