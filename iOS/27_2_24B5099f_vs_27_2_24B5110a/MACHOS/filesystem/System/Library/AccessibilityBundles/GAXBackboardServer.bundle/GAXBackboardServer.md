## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2be68` | `0x2c3a0` | **`+0x538`** |
| `__TEXT.__oslogstring` | `0x4388` | `0x44e5` | **`+0x15d`** |
| `__TEXT.__objc_methname` | `0x8eea` | `0x8ffc` | **`+0x112`** |
| `__TEXT.__objc_stubs` | `0x6a60` | `0x6b20` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x16b0` | `0x1708` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x84c` | `0x898` | **`+0x4c`** |
| `__DATA.__objc_const` | `0x2a68` | `0x2aa0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x2904` | `0x293c` | **`+0x38`** |
| `__TEXT.__cstring` | `0x47fe` | `0x4835` | **`+0x37`** |
| `__DATA.__objc_selrefs` | `0x1f10` | `0x1f40` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x37a0` | `0x37c0` | **`+0x20`** |
| `__TEXT.__const` | `0x188` | `0x190` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xab8` | `0xac0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1ac` | `0x1b0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1067.3.3.0.0
+1067.3.4.0.0

-  Functions: 980
+  Functions: 985

-  CStrings:  2280
+  CStrings:  2294
CStrings:
+ "Active interface orientation still unknown after %lu retries. Exiting the workspace."
+ "Active interface orientation was unknown. Retrying transition to mode %lu in %g seconds (attempt %lu of %lu)."
+ "Active interface orientation was unknown; resolved it to %ld from SpringBoard."
+ "Disabling GAX because the session app is restricted by Partner Financing."
+ "Dropping superseded orientation retry %lu."
+ "Error - Session app is restricted by Partner Financing"
+ "Session app %{public}@ is restricted. Reason: %lu"
+ "TQ,N,V_unknownOrientationRetryCount"
+ "_unknownOrientationRetryCount"
+ "applicationState"
+ "initWithBundleIdentifier:allowPlaceholder:error:"
+ "restrictionReason"
+ "sessionAppIsRestrictedByPartnerFinancingForIntegrityVerifier:"
+ "setUnknownOrientationRetryCount:"
+ "unknownOrientationRetryCount"
- "Active interface orientation was unknown. trying to transition gax again in .25. %{public}@"
```
