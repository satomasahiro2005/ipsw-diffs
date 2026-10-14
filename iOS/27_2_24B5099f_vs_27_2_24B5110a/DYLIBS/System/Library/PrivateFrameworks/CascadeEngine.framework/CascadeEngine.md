## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/CascadeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65b8c` | `0x65d64` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0x6d4f` | `0x6e0f` | **`+0xc0`** |

### Other Changes

```diff

-258.0.0.0.0
+259.0.0.0.0

-  CStrings:  836
+  CStrings:  839
Functions:
~ -[CCRapportManager discoveryControlFlagsForDevicePlatform:] : 188 -> 196
~ -[CCRapportSyncEngine _matchesSystemDomainDeviceRules:currentPlatform:] : 1008 -> 1352
~ -[CCRapportSyncEngine _matchesUserDomainDeviceRules:currentPlatform:] : 524 -> 644
CStrings:
+ "%@: matched — HomeAccessory→Owner personal (system-domain)"
+ "%@: matched — iOS→Owner HomeAccessory (user-domain)"
+ "%@: matched — personal→Owner HomeAccessory non-synthesized (system-domain)"
```
