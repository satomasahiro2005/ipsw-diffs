## com.apple.driver.AppleH16ANEInterface

> `com.apple.driver.AppleH16ANEInterface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x15b014` | `0x15bb10` | **`+0xafc`** |
| `__TEXT.__os_log` | `0x3dfe8` | `0x3e23b` | **`+0x253`** |
| `__TEXT.__cstring` | `0x11ddc` | `0x11ec2` | **`+0xe6`** |
| `__DATA_CONST.__const` | `0x10058` | `0x100c0` | **`+0x68`** |
| `__TEXT.__const` | `0x1250` | `0x1260` | **`+0x10`** |
| `__TEXT_EXEC.__auth_stubs` | `0x1290` | `0x12a0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x948` | `0x950` | **`+0x8`** |

### Other Changes

```diff

-10.101.100.0.0
-  Functions: 5091
+10.102.3.0.0
+  Functions: 5100

-  CStrings:  5447
+  CStrings:  5458
CStrings:
+ "%s: %s: ANE%u: AGX peer already latched, ignoring additional %s service\n"
+ "%s: %s: ANE%u: FW shared event signaling disabled, cleared FW-FW signaling for programHandle: 0x%llx transactionId: 0x%llx\n"
+ "%s: %s: ANE%u: Watching for peer AGX service %s\n"
+ "%s: %s: Leaving recoverable request uuid: 0x%llx on ANE%d - re-dispatched after power on\n"
+ "%s: %s: Powered MPM off via PS register before powering down\n"
+ "%s: %s: Timed out after waiting %u seconds for requests to complete on the ANE.\n"
+ "%s: %s: takeAneSysClockAssertion_gated result = 0x%x fAneSysClockAssertions=%d\n"
+ "2111112"
+ "B24@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{IONotifier=^^?i}16"
+ "[ERROR] %s: %s: ANE%u: Couldn't create matching dictionary for %s\n"
+ "[ERROR] %s: %s: ANE%u: Failed to install %s arrival notification\n"
+ "[ERROR] %s: %s: ANE%u: Failed to push AGX signaling state %d to firmware: 0x%x\n"
+ "[ERROR] %s: %s: Failed to power MPM off before powering down: 0x%x\n"
+ "agxArrivalNotificationHandler"
+ "power-off-exclave-mpm"
- "%s: %s: AGX peer EP service NOT FOUND\n"
- "%s: %s: ANE powered off, clearing MPM powered state so the Exclave re-arm re-enables it\n"
- "%s: %s: Timed out after waiting %u ms for requests to complete on the ANE.\n"
- "21112"
```
