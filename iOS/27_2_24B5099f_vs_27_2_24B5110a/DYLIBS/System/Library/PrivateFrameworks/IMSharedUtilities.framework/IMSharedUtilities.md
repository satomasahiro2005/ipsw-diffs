## IMSharedUtilities

> `/System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x381394` | `0x382c6c` | **`+0x18d8`** |
| `__TEXT.__oslogstring` | `0x1ed96` | `0x1efb6` | **`+0x220`** |
| `__TEXT.__cstring` | `0x285b3` | `0x28723` | **`+0x170`** |
| `__AUTH_CONST.__const` | `0x17e70` | `0x17fd0` | **`+0x160`** |
| `__AUTH_CONST.__cfstring` | `0x241c0` | `0x242a0` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0xfd00` | `0xfdc0` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x9f14` | `0x9fbc` | **`+0xa8`** |
| `__TEXT.__const` | `0x1fbd8` | `0x1fc58` | **`+0x80`** |
| `__DATA.__bss` | `0x39050` | `0x39090` | **`+0x40`** |
| `__DATA.__data` | `0xb348` | `0xb378` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x299d0` | `0x299a8` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x1a670` | `0x1a690` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x69f4` | `0x6a10` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0xd950` | `0xd968` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0xe98` | `0xe88` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x7fe4` | `0x7ff4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2c70` | `0x2c78` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x6e08` | `0x6e10` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x792a` | `0x7932` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x10d0` | `0x10cc` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x830` | `0x834` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-1491.200.95.0.0
+1491.200.101.2.5

-  Functions: 21613
-  Symbols:   4256
-  CStrings:  8110
+  Functions: 21650
+  Symbols:   4264
+  CStrings:  8128
Symbols:
+ _IMBalloonBundleIDIsAskToRequest
+ _IMChatPropertyPromotedToKnownByReply
+ _IMServiceCapabilityDetectInternationalSenderBySIMRegion
+ _IMSharedHelperCurrentRegionCode
+ _IMSharedHelperCurrentRegionRestrictsUnknownSenders
+ _IMSharedHelperCurrentRegionStrengthensUnknownSenderScamWarnings
+ _IMSharedHelperUnknownSenderCopyRestrictedInCurrentRegion
+ _IMSharedHelperUnknownSenderLinkRestrictionDisabled
CStrings:
+ "!!!-- Agent Condition Inducer inducing main-thread hang for %ldms, then relieving for %ldms --!!"
+ "!!!-- Agent Condition Inducer scheduling main-thread hang loop, ConditionInducerHangDuration: %ldms --!!"
+ "ConditionInducerHangDuration"
+ "ConditionInducerHangReliefDuration"
+ "ConditionInducerHangsEnabled"
+ "Could not find a default subscription context"
+ "DetectInternationalSenderBySIMRegion"
+ "Unknown sender copy restriction disabled by bag"
+ "Unknown sender link restriction disabled by bag: %{BOOL}d"
+ "Unknown sender restrictions apply in Region %{public}@"
+ "Unknown sender restrictions overridden for Region %{public}@: %{BOOL}d"
+ "UnknownSenderRestrictionAdditionalRegions"
+ "Using overridden SIM country code (%@)."
+ "disable-unknown-sender-copy-restriction"
+ "disable-unknown-sender-link-restriction"
+ "promotedToKnownByReply"
+ "setSIMCountryCodeForUnknownSender"
+ "strengthened-unknown-sender-warning-country-codes"
```
