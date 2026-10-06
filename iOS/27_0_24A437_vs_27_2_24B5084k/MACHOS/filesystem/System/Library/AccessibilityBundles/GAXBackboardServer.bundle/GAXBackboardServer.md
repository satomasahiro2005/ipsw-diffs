## GAXBackboardServer

> `/System/Library/AccessibilityBundles/GAXBackboardServer.bundle/GAXBackboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b720` | `0x2b9dc` | **`+0x2bc`** |
| `__TEXT.__oslogstring` | `0x41e2` | `0x42ca` | **`+0xe8`** |
| `__TEXT.__objc_methname` | `0x8d7a` | `0x8df7` | **`+0x7d`** |
| `__TEXT.__cstring` | `0x4737` | `0x47a4` | **`+0x6d`** |
| `__DATA_CONST.__cfstring` | `0x3720` | `0x3760` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x6980` | `0x69c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x28ac` | `0x28cc` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1ed8` | `0x1ee8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x16b8` | `0x16c8` | **`+0x10`** |
| `__DATA.__objc_const` | `0x2a30` | `0x2a38` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x18ca` | `0x18cd` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1064.0.0.0.0
+1067.3.0.0.0

-  Functions: 967
-  Symbols:   583
-  CStrings:  2262
+  Functions: 970
+  Symbols:   586
+  CStrings:  2268
Symbols:
+ _GAXIPCPayloadKeyHostedApplicationCornerRadii
+ _GAXUIMessageKeyHostedApplicationCornerRadii
+ _deserializeGAXBackboardState
CStrings:
+ "-[AXSpringBoardServer(GAXAdditions) gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:cornerRadiiStringRepresentation:animationDurationNumber:]"
+ "GAXIPCPayloadKeyHostedApplicationCornerRadii"
+ "Reconciling implicit GAX client check-in for still-frontmost session app %@ (pid:%@). Its one-shot check-in ping was lost, not absent"
+ "Session app is still frontmost but its GAX client never checked in; reconciling the lost check-in"
+ "didReconcileCheckInForEffectiveSessionApp"
+ "didReconcileSessionAppCheckInForIntegrityVerifier:"
+ "gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:cornerRadiiStringRepresentation:animationDurationNumber:"
+ "hosted application corner radii"
+ "v56@0:8@16@24@32@40@48"
- "-[AXSpringBoardServer(GAXAdditions) gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:animationDurationNumber:]"
- "gaxUpdateStateOfHostedApplicationWithIdentifier:scaleFactorNumber:centerStringRepresentation:animationDurationNumber:"
- "v48@0:8@16@24@32@40"
```
