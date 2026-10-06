## com.apple.driver.AppleOLYHAL

> `com.apple.driver.AppleOLYHAL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4ff0` | `0x4ee4` | **`-0x10c`** |
| `__TEXT_EXEC.__text` | `0x1d904` | `0x1d9c4` | **`+0xc0`** |

### Other Changes

```diff

-530.9.4.1.0
-  Functions: 588
+530.9.4.2.0
+  Functions: 585

-  CStrings:  536
+  CStrings:  531
CStrings:
+ "%s::%s: FCR begin during dext crash! Saving device state.\n"
+ "%s::%s: FCR end during dext crash! Restoring device state.\n"
+ "%s::%s: FLR result: 0x%08x\n"
+ "%s::%s: Received Dext Publish Notification (%p)\n"
+ "%s::%s: Received Dext Termination Notification (%p)\n"
+ "%s::%s: Received IOPCIDevice gIOPublish Notification (%p)\n"
+ "%s::%s: Received IOPCIDevice gIOWillTerminate Notification (%p)\n"
+ "%s::%s: Recovering dext crash (FCR: %d)"
+ "%s::%s: Recovering dext crash (FLR: %u, 0x%08x, %p\n)"
+ "%s::%s: Triggering FLR\n"
- "\"%s:%u:\" \"!is_enabled\" @%s:%d"
- "\"%s:%u:\" \"pActionType == kAppleOLYHALPortInterfacePowerActionTypeHardReset\" @%s:%d"
- "\"Pending powerOn never arrived\\n\" @%s:%d"
- "%s::%s: Dext Recovery was paused. Wait until AMFM completes its 3 sequence handshakes\n"
- "%s::%s: No pending AMFM messages\n"
- "%s::%s: Received Dext Publish Notification\n"
- "%s::%s: Received Dext Termination Notification\n"
- "%s::%s: Received IOPCIDevice gIOPublish Notification\n"
- "%s::%s: Received IOPCIDevice gIOWillTerminate Notification\n"
- "%s::%s: Sleep until pending powerOn completes\n"
- "%s::%s: Using pre-existing powercycle as the recovery mechanism\n"
- "OLYHAL initFailureChipResetComplete -> restoreDeviceState()\n"
- "OLYHAL reset -> saveDeviceState() (captured cfg pre power-cycle)\n"
- "handleDextPublish"
- "handleDextTerminate"
```
