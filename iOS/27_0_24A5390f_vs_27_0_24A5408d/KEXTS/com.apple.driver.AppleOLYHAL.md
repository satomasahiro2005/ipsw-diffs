## com.apple.driver.AppleOLYHAL

> `com.apple.driver.AppleOLYHAL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1d0b0` | `0x1d8c0` | **`+0x810`** |
| `__TEXT.__cstring` | `0x4967` | `0x4f86` | **`+0x61f`** |
| `__TEXT.__const` | `0x1ef0` | `0x1f88` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x13a8` | `0x1418` | **`+0x70`** |

### Other Changes

```diff

-530.7.0.0.0
-  Functions: 576
+530.9.0.0.0
+  Functions: 587

-  CStrings:  516
+  CStrings:  535
CStrings:
+ "%s::%s: OLYHAL-port(AMFM) enableGated is_enabled=%d pActionType=%d first=%d fResetProgress=%d\n"
+ "%s::%s: setPowerEnable is_enabled=%d\n"
+ "1211111212221212111111112212112111221121112212221111111"
+ "AppleOLYHAL::reportInitFailure: str=%s\n"
+ "AppleOLYHAL::reportInitFailureWithChipReset: str=%s requiresChipResetAndRegisterService=%d\n"
+ "BCMWLAN Init-failure chip reset limit reached"
+ "Init-failure chip reset (attempt %u/%u); AMFM-coordinated power-cycle + respawn\n"
+ "Init-failure chip reset limit (%u) reached; leaving WiFi down\n"
+ "Init-failure chip reset requested during shutdown; ignoring reset\n"
+ "Init-failure chip reset unsupported on non-AMFM-managed port; leaving WiFi down\n"
+ "Manually triggering IOPCIDevice powerOn\n"
+ "OLYHAL initFailureChipResetComplete -> restoreDeviceState()\n"
+ "OLYHAL initFailureChipResetComplete: reset finished (attempt %u)\n"
+ "OLYHAL requestDextInitFailureChipReset gate: shutdown=%d fPCIePort=%p amfmManaged=%d count=%u/%u\n"
+ "OLYHAL reset -> fPCIePort->requestChipReset attempt=%u\n"
+ "OLYHAL reset -> registerActionHandler + resetPortActionHandler status=0x%x\n"
+ "OLYHAL reset -> requestChipReset returned 0x%x\n"
+ "OLYHAL reset -> saveDeviceState() (captured cfg pre power-cycle)\n"
+ "OLYHAL-port kAMFMChipIsUp -> init failure recovery reset complete, notifying OLYHAL\n"
+ "OLYHAL-port requestChipReset -> fManager NULL (offline, no reset)\n"
+ "OLYHAL-port requestChipReset powerPreserve=%d fManager=%p fResetProgress=%d fResetIsInternal=%d\n"
+ "OLYHAL-port setInitFailureRecoveryPending pending=%d\n"
+ "Retriggering wifi dext matching\n"
+ "initFailureChipResetComplete: dext already published. nothing to respawn\n"
+ "initFailureChipResetComplete: fWlanPCIDevice missing. dext will spawn automatically when it appears\n"
+ "reportInitFailureWithChipResetDK_Impl"
- "%s::%s: %u\n"
- "%s::%s: PCIe device is gone.\n"
- "121111121222121211111111221211211122111121112212221111111"
- "APB0_S"
- "APB1_S"
- "OLYHAL panic: %s[%x] = 0x%08x\n"
- "mapbar0"
```
