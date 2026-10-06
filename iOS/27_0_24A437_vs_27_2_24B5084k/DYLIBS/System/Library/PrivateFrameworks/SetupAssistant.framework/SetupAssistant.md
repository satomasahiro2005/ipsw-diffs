## SetupAssistant

> `/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44ac4` | `0x44b24` | **`+0x60`** |
| `__TEXT.__cstring` | `0x3539` | `0x34e9` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3b20` | `0x3b00` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x6308` | `0x6300` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x1788` | `0x1780` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2cb0` | `0x2ca8` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x420c` | `0x4204` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x5a31` | `0x5a30` | **`-0x1`** |

### Other Changes

```diff

-5411.101.0.0.0
+5411.103.0.0.0

-  Symbols:   3119
-  CStrings:  1141
+  Symbols:   3117
+  CStrings:  1138
Symbols:
+ -[BYBuddyDaemonGeneralClient dealloc]
+ GCC_except_table41
- -[BuddyFeatureFlags isDataAndPrivacyBundleEnabled]
- GCC_except_table40
- GCC_except_table46
- _BYPrivacySubscriptionBundleIdentifier
CStrings:
+ "No _stashedIntelligenceState"
- " No _stashedIntelligenceState"
- "DataAndPrivacyBundle"
- "SetupAssistantPane"
- "com.apple.onboarding.subscriptionbundle"
```
