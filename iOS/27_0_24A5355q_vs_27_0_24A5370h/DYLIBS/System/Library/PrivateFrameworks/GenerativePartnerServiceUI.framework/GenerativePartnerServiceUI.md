## GenerativePartnerServiceUI

> `/System/Library/PrivateFrameworks/GenerativePartnerServiceUI.framework/GenerativePartnerServiceUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc422c` | `0xc88ec` | **`+0x46c0`** |
| `__TEXT.__swift5_typeref` | `0xe863` | `0x1089b` | **`+0x2038`** |
| `__TEXT.__const` | `0x678c` | `0x6b7c` | **`+0x3f0`** |
| `__DATA.__data` | `0x2934` | `0x2ccc` | **`+0x398`** |
| `__TEXT.__oslogstring` | `0x215d` | `0x1e3d` | **`-0x320`** |
| `__TEXT.__eh_frame` | `0x4948` | `0x4750` | **`-0x1f8`** |
| `__AUTH.__data` | `0x1b20` | `0x1ce8` | **`+0x1c8`** |
| `__TEXT.__unwind_info` | `0x2ff0` | `0x3158` | **`+0x168`** |
| `__AUTH.__objc_data` | `0xab8` | `0x960` | **`-0x158`** |
| `__DATA.__bss` | `0x4848` | `0x4998` | **`+0x150`** |
| `__AUTH_CONST.__objc_const` | `0x1570` | `0x1428` | **`-0x148`** |
| `__AUTH_CONST.__auth_got` | `0x1ad0` | `0x1bd0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x34c3` | `0x3593` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x1730` | `0x17c8` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x2008` | `0x2078` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x1934` | `0x19a4` | **`+0x70`** |
| `__DATA_CONST.__got` | `0xc90` | `0xcf8` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x5148` | `0x51a0` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x648` | `0x600` | **`-0x48`** |
| `__TEXT.__swift5_assocty` | `0x400` | `0x448` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x414` | `0x3d4` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x188` | `0x1b8` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x778` | `0x750` | **`-0x28`** |
| `__DATA.__common` | `0x188` | `0x168` | **`-0x20`** |
| `__TEXT.__swift5_types` | `0x1b4` | `0x1c8` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x154` | `0x144` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x274` | `0x27c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x124` | `0x12c` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x1428` | `0x1424` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x294` | `0x290` | **`-0x4`** |

### Other Changes

```diff

-279.0.15.0.0
+284.0.7.0.0

+  - /System/Library/PrivateFrameworks/_IconServices_SwiftUI.framework/_IconServices_SwiftUI

-  Functions: 4926
-  Symbols:   320
-  CStrings:  402
+  Functions: 5019
+  Symbols:   318
+  CStrings:  400
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ _kCFPreferencesAnyApplication
+ _swift_projectBox
- _OBJC_CLASS_$_MCProfileConnection
- _PSAllowMultilineTitleKey
- _PSCellClassKey
- _PSEnabledKey
- _PSTableCellSubtitleTextKey
CStrings:
+ "(Nonexistent App)"
+ "AgentIntentSettings"
+ "All installed extensions"
+ "Allowed workspace IDs: %s"
+ "Apple Intelligence Extensions are currently not available in your location."
+ "Apple Intelligence Extensions are currently unavailable"
+ "CFBundlePrimaryIcon"
+ "CFBundleSymbolName"
+ "Disallow External Intelligence"
+ "Disallow External Intelligence Sign-In"
+ "ExtensionRoomViewModel: loaded external providers, count: %{public}ld"
+ "Extensions are disabled by your organization."
+ "Forces isExternalIntelligenceAllowed to false"
+ "Forces isExternalIntelligenceSignInAllowed to false"
+ "GenerativePartnerSettingsPanelView.init()"
+ "Internal-only debug overrides for GenerativePartnerRestrictionPolicy. These simulate MDM-managed values from com.apple.applicationaccess without an actual configuration profile."
+ "Logging off %{public}s."
+ "MDM Restriction Policy Overrides"
+ "NSAccentColorName"
+ "No extensions installed"
+ "No intent available"
+ "No provider available"
+ "Populates allowedExternalIntelligenceWorkspaceIDs"
+ "Require Workspace Sign-In"
+ "SiriExpressiveVoicesEnabled"
+ "Trying to sign in with workspace ID: %s"
+ "V2 Provider Availability"
+ "You may need to exit Siri Settings and re-enter for these settings to take effect."
+ "Your organization’s device management profile is misconfigured to simultaneously require and disallow signing in to the Extension."
+ "alwaysShowEntryPointIgnoringAvailability"
+ "com.apple.application-icon.apple-intelligence"
+ "com.apple.application-icon.apple-intelligence-gen2"
+ "isChatGPTSoftRestrictedDueToIPCountryCode"
+ "legacyPrimarySettingsList(currentLLM:)"
+ "legacyPrimarySettingsListWhenNotEnabled()"
+ "name languageCode "
+ "optedInAppBundleIDs didSet triggered"
+ "received availabilityDidChange"
+ "received changeNotification"
+ "received changeNotification update with event: %{public}s"
+ "retrieveAvailableVoices: mode=%{public}s, count=%{public}ld (%{public}s)"
+ "useChatGPTOnlyUIForV3"
- "\n\nPlease file a bug report to feedback.apple.com"
- "%{public}s - will perform reloadSpecifiers(), invocationSource: %{public}s"
- "%{public}s: %{bool,public}d"
- "%{public}s: %{public}s is not allowed"
- "%{public}s: a workspace is required, but the credentials have none"
- "%{public}s: allowExternalIntelligenceIntegrationsSignIn does not allow sign in, but allowedExternalIntelligenceWorkspaceIDs requires it."
- "%{public}s: allowedExternalIntelligenceWorkspaceIDs is set but empty."
- "%{public}s: an empty value for allowedExternalIntelligenceWorkspaceIDs was provided, unable to validate any credentials."
- "%{public}s: no workspace restriction"
- "%{public}s: previousPartnerID: %{public}s, currentPartnerID: %{public}s"
- "%{public}s: workspace id %{public}s matched. User signed in with an accepted workspace."
- "Apple Intelligence Extension Not Found"
- "Change Extension"
- "Extending Apple Intelligence is currently not available in your location."
- "Extending Apple Intelligence is currently unavailable"
- "Extending Apple Intelligence is not available to children 13 or younger."
- "Extending Apple Intelligence is protected by a Screen Time passcode."
- "Extending Apple Intelligence requires enabling Apple Intelligence first."
- "Extension (Legacy)"
- "No opted in extensions uninstalled"
- "SIRI_REQUESTS_GROUP"
- "Unable to find the Apple Intelligence Extension for: "
- "Uninstalled Opted In Extensions"
- "Your organization's mobile device management profile is misconfigured to simultaneously require and disallow signing in to the Extension."
- "[DEBUG] Finalized group specifier footer text: %{public}s, invocationSource: %{public}s"
- "[Deep Links] Unsupported path component: \"%{public}s\" (expected: \"ExternalAIModel\")"
- "[INTERNAL] Proceed to V2"
- "[Settings] External AI hard disabled, not showing Apple Intelligence Extension settings"
- "agentIntentOptInStatusDidChange invoked"
- "agentIntentOptInStatusDidChange(optedInAppBundleIDs:)"
- "apple.intelligence"
- "availabilityDidChange(for:availability:)"
- "changeNotification invoked"
- "changeNotification(_:)"
- "init(parentController:settings:)"
- "isSoftRestrictedDueToIPCountryCode"
- "mdmExternalIntelligenceSignInRequired"
- "parentController is nil when attempting to present onboarding sheet"
- "reasons: %{public}s"
- "receivedActiveProviderUpdate()"
- "receivedUseConfirmationPromptsUpdate()"
- "showOnboardingSelectionSheet(preselectedPartnerID:)"
- "updateVisibility(needsReload:debugInvocationSourceString:)"
- "workspaceAllowed(workspaceId:)"
```
