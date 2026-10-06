## com.apple.driver.AppleT8140MCC

> `com.apple.driver.AppleT8140MCC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x15aa0` | `0x168a0` | **`+0xe00`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x5b0` | **`+0x5b0`** |
| `__TEXT.__cstring` | `0x56c9` | `0x5a3d` | **`+0x374`** |
| `__TEXT.__os_log` | `0x23ba` | `0x2671` | **`+0x2b7`** |
| `__DATA_CONST.__const` | `0x3370` | `0x33c0` | **`+0x50`** |

### Other Changes

```diff

-120.0.0.0.0
-  Functions: 566
+125.0.0.0.0
+  Functions: 574

-  CStrings:  890
+  CStrings:  921
CStrings:
+ "\"%s has not been implemented by platform\" @%s:%d"
+ "\"%s has not been implemented by platform.\" @%s:%d"
+ "\"%s: \" \"Failed to map memory aperture %u\" @%s:%d"
+ "%s: EDT blob too small (%u bytes, need %zu)"
+ "%s:%d: %s: EDT blob too small (%u bytes, need %zu)\n"
+ "%s:%d: DRAMECC: Invalid register table for memory hashing\n\n"
+ "%s:%d: DRAMECC: Starting init mem hash param\n\n"
+ "%s:%d: DRAMECC: bank-drop-mask0 is missing in mcc node in EDT\n\n"
+ "%s:%d: DRAMECC: bank-drop-mask1 is missing in mcc node in EDT\n\n"
+ "%s:%d: DRAMECC: bank-group-drop-mask0 is missing in mcc node in EDT\n\n"
+ "%s:%d: DRAMECC: bank-group-drop-mask1 is missing in mcc node in EDT\n\n"
+ "%s:%d: DRAMECC: rank-drop-mask0 is missing in mcc node in EDT\n\n"
+ "%s:%d: DRAMECC: row-drop-mask is missing in mcc node in EDT\n\n"
+ "%s:%d: _dcsNumChannels = %d _dcsEnableMask = 0x%llx\n"
+ "%s:%d: dcs-channel-enable-mask is not set in EDT. Setting dcs channel mask to 0x%llx\n"
+ "%s:%d: dcs-channel-enable-mask: 0x%llx\n\n"
+ "%s:%d: regIdx = %d _apertureNum = %d _apertureEnableMask = 0x%llx\n"
+ "12111112122212121111111111111111111111111111112111111111111111111111111111111111111111111111111111111111111111111111111111211111112121111121"
+ "121111121222121211111111111111111111111111111121111111111111111111111111111111111111111111111111111111111111111111111111112111111121211111212221122222222222211111112111121211121212121212"
+ "DRAMECC: Invalid register table for memory hashing\n"
+ "DRAMECC: Starting init mem hash param\n"
+ "DRAMECC: bank-drop-mask0 is missing in mcc node in EDT\n"
+ "DRAMECC: bank-drop-mask1 is missing in mcc node in EDT\n"
+ "DRAMECC: bank-group-drop-mask0 is missing in mcc node in EDT\n"
+ "DRAMECC: bank-group-drop-mask1 is missing in mcc node in EDT\n"
+ "DRAMECC: rank-drop-mask0 is missing in mcc node in EDT\n"
+ "DRAMECC: row-drop-mask is missing in mcc node in EDT\n"
+ "_dcsNumChannels = %d _dcsEnableMask = 0x%llx"
+ "_initMemHashParam"
+ "bank-drop-mask0"
+ "bank-drop-mask1"
+ "bank-group-drop-mask0"
+ "bank-group-drop-mask1"
+ "dcs-channel-enable-mask is not set in EDT. Setting dcs channel mask to 0x%llx"
+ "dcs-channel-enable-mask: 0x%llx\n"
+ "getAmccInstanceLp6"
+ "getDcsInstanceFromHashBitVal"
+ "getDcsScFromHashBitVal"
+ "getMCCProperty"
+ "rank-drop-mask0"
+ "regIdx = %d _apertureNum = %d _apertureEnableMask = 0x%llx"
+ "row-drop-mask"
- "\"%s: \" \"Failed to map amcc aperture %u\" @%s:%d"
- "%s:%d: _dcsNumChannels = %d _dcsEnableMask = 0x%x\n"
- "%s:%d: dcs-channel-enable-mask is not set in EDT. Setting dcs channel mask to 0x%x\n"
- "%s:%d: dcs-channel-enable-mask: 0x%x\n\n"
- "%s:%d: regIdx = %d _apertureNum = %d _apertureEnableMask = 0x%x\n"
- "1211111212221212111111111111111111111111112111111111111111111111111111111111111111111111111111111111111111111111111111211111112121111121"
- "1211111212221212111111111111111111111111112111111111111111111111111111111111111111111111111111111111111111111111111111211111112121111121112222222222211111112111121211121212121212"
- "_dcsNumChannels = %d _dcsEnableMask = 0x%x"
- "dcs-channel-enable-mask is not set in EDT. Setting dcs channel mask to 0x%x"
- "dcs-channel-enable-mask: 0x%x\n"
- "regIdx = %d _apertureNum = %d _apertureEnableMask = 0x%x"
```
