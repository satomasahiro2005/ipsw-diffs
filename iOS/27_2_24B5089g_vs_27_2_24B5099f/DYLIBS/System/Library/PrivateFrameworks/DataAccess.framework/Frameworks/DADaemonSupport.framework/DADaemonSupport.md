## DADaemonSupport

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DADaemonSupport.framework/DADaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x373d0` | `0x3729c` | **`-0x134`** |
| `__DATA_CONST.__const` | `0x8f0` | `0x918` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xb68` | `0xb80` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x65b8` | `0x65cb` | **`+0x13`** |

### Other Changes

```diff

-2708.1.5.0.0
+2708.2.2.0.0

-  Symbols:   2116
+  Symbols:   2118
Symbols:
+ ___51-[DARefreshWrapper startFetchActivityWithInterval:]_block_invoke_2
+ ___block_descriptor_49_e8_32s40s_e5_v8?0ls32l8s40l8
CStrings:
+ "XPC: Fetch Activity has no account; setting XPC activity state to XPC_ACTIVITY_STATE_DONE"
- "Updating criteria for fetch xpc activity for account \"%@\" (%{public}@)"
```
