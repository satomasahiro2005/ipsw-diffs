## BackBoard

> `/System/Library/AccessibilityBundles/BackBoard.axbundle/BackBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28850` | `0x28b54` | **`+0x304`** |
| `__TEXT.__oslogstring` | `0x2233` | `0x23ac` | **`+0x179`** |
| `__AUTH_CONST.__cfstring` | `0x1e20` | `0x1e40` | **`+0x20`** |
| `__TEXT.__cstring` | `0x23d1` | `0x23f1` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c38` | `0x1c50` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x237c` | `0x2394` | **`+0x18`** |
| `__DATA.__bss` | `0x538` | `0x540` | **`+0x8`** |
| `__TEXT.__const` | `0x510` | `0x518` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd00` | `0xd08` | **`+0x8`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 1037
-  Symbols:   2124
-  CStrings:  506
+  Functions: 1040
+  Symbols:   2127
+  CStrings:  510
Symbols:
+ -[AXBDisplayWakeManager _setupBuddyCompletionMonitoring]
+ -[AXBDisplayWakeManager _suppressAccessibilityHelpBannerIfFeatureEnabledDuringSetup]
+ GCC_except_table635
+ GCC_except_table648
+ GCC_except_table660
+ GCC_except_table693
+ GCC_except_table731
+ GCC_except_table745
+ GCC_except_table819
+ __buddySetupDidComplete
- GCC_except_table632
- GCC_except_table645
- GCC_except_table657
- GCC_except_table690
- GCC_except_table728
- GCC_except_table742
- GCC_except_table816
CStrings:
+ "Accessibility feature was enabled during device setup, help banner will not be shown: VoiceOver=%{BOOL}d, SwitchControl=%{BOOL}d, TouchAccommodations=%{BOOL}d"
+ "Denying request to set Guided Access enabled=%i: no bundle identifier for sender pid %d (process is gone, or is not bundled)."
+ "Device setup is in progress, not showing accessibility help banner"
+ "Received request to set Guided Access enabled=%i from %{public}@ (pid %d), but GAXBackboard was nil."
+ "com.apple.purplebuddy.setupdone"
- "Received request to set Guided Access enabled=%i, but GAXBackboard was nil."
```
