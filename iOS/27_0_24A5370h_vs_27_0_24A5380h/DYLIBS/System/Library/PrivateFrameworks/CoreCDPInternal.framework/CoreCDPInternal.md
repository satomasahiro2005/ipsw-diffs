## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1070` | `0x120` | **`-0xf50`** |
| `__DATA_DIRTY.__objc_data` | `0xa60` | `0x19b0` | **`+0xf50`** |
| `__TEXT.__text` | `0x8d5a0` | `0x8db84` | **`+0x5e4`** |
| `__TEXT.__oslogstring` | `0x1494e` | `0x14a5e` | **`+0x110`** |
| `__AUTH.__data` | `0x58` | `—` | **`-0x58`** |
| `__DATA_DIRTY.__data` | `0x1a8` | `0x200` | **`+0x58`** |
| `__DATA.__bss` | `0x4c0` | `0x490` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `0x1a0` | `0x1d0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x94a0` | `0x94c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xe035` | `0xe055` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x5664` | `0x567c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x38f0` | `0x3900` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1de0` | `0x1df0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x968` | `0x960` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x10b0` | `0x10b8` | **`+0x8`** |

### Other Changes

```diff

-442.0.0.0.0
+444.0.0.0.0

-  Functions: 3151
-  Symbols:   4143
-  CStrings:  2802
+  Functions: 3157
+  Symbols:   4145
+  CStrings:  2806
Symbols:
+ -[CDPDFollowUpController _existingTelemetryFlowIDForIdentifier:usingController:]
+ -[CDPInternalWalrusStateController _hydrateRepairTelemetryOnContext]
+ _CDPFollowUpItemUserInfoKeyTelemetryFlowID
- _swift_retain_x25
CStrings:
+ "AKAccountStateErrorDomain"
+ "CDPInternalWalrusStateController: no CDPContext available; walrusRepair telemetry will lack flow/session IDs"
+ "CDPInternalWalrusStateController: no telemetryFlowID on daemon _context; minted for repair pair: %{public}@"
+ "Failed to fetch pending CFUs for telemetryFlowID reuse (%@): %@"
```
