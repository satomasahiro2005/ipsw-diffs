## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/CoreRepairCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a558` | `0x8b738` | **`+0x11e0`** |
| `__TEXT.__oslogstring` | `0x96fc` | `0x9a50` | **`+0x354`** |
| `__AUTH_CONST.__cfstring` | `0x8360` | `0x84c0` | **`+0x160`** |
| `__TEXT.__cstring` | `0x6ee0` | `0x6ff8` | **`+0x118`** |
| `__TEXT.__gcc_except_tab` | `0x166c` | `0x171c` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0xa00` | `0xaa0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x456c` | `0x45ac` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x13e0` | `0x1420` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x25a0` | `0x25c0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x64d8` | `0x64e8` | **`+0x10`** |
| `__TEXT.__const` | `0x848` | `0x858` | **`+0x10`** |

### Other Changes

```diff

-1291.0.0.502.1
+1307.0.16.0.0

-  Functions: 2504
+  Functions: 2517

-  CStrings:  2393
+  CStrings:  2422
CStrings:
+ "AMFDRError"
+ "AssetChannel"
+ "AssetChannel overridden: %@"
+ "CDN"
+ "CheckPressureSensor"
+ "DOFU of battery is in future"
+ "Diagnostic-8264"
+ "Display swap validation failed."
+ "Failed to set battery date of first use on real writing, error: 0x%08x"
+ "Failed to set battery date of first use on starting, error: 0x%08x"
+ "Generating reference frames files...\n"
+ "Get repair date of %@"
+ "GetRepairDateXPC"
+ "Got repair date of %@: %lld"
+ "Invalid updaterOptions parameter"
+ "MobileAsset"
+ "Network failure detected during permission or sealing request"
+ "Network failure detected on data recovering"
+ "Partial Sealing Failed in RealSealing:%@"
+ "Partial Sealing Failed in StagedSealing:%@"
+ "Response dictionary empty"
+ "Sealing failed on RealToReal repair, error: %@"
+ "Sealing failed on StagedToReal repair, error: %@"
+ "UseXPC"
+ "XPC call failed to get repair date of %@: %@"
+ "_PressureSN"
+ "completionIokitError: 0x%08x"
+ "getComponentState: Return Override kCRComponentStateIssue"
+ "getComponentState: Return Override kCRComponentStateMismatch"
+ "getComponentState: Return Override kCRComponentStateRepairedWithServicePart"
+ "getComponentState: Return Override kCRComponentStateRepairedWithUsedPart"
+ "getComponentState: componentType=%d, internalName=%@, overrideState=%ld"
+ "getRepairDate: componentType=%d, internalName=%@, dateOverrideStr=%@"
+ "startIokitError: 0x%08x"
+ "v28@?0B8@\"NSString\"12@\"NSError\"20"
- "Failed to set battery date of first use when starting: 0x%08x"
- "Failed to set battery date of first use when writing: 0x%08x"
- "Network failure detected"
- "Partial Sealing Failed:%@"
- "completionIokitError: %d"
- "startIokitError: %d"
```
