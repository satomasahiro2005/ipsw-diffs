## CTMessagingSettings

> `/System/Library/PrivateFrameworks/CTMessagingSettings.framework/CTMessagingSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x255ec` | `0x2af2c` | **`+0x5940`** |
| `__TEXT.__oslogstring` | `0x44b` | `0x114b` | **`+0xd00`** |
| `__TEXT.__cstring` | `0x1071` | `0x11b1` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x1666` | `0x170e` | **`+0xa8`** |
| `__TEXT.__eh_frame` | `0x4c0` | `0x530` | **`+0x70`** |
| `__TEXT.__const` | `0xe94` | `0xee4` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x6c0` | `0x6f0` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x9b0` | `0x9d8` | **`+0x28`** |
| `__DATA.__data` | `0x7b0` | `0x7d0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x468` | `0x480` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x8f0` | `0x8e0` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x318` | `0x328` | **`+0x10`** |
| `__AUTH.__data` | `0x318` | `0x320` | **`+0x8`** |

### Other Changes

```diff

-13496.3.0.0.0
+13498.0.0.0.0

-  Functions: 575
-  Symbols:   467
-  CStrings:  106
+  Functions: 595
+  Symbols:   469
+  CStrings:  152
Symbols:
+ ___swift_closure_destructor.76Tm
+ ___swift_destroy_boxed_opaque_existential_0
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA5GroupVyAA7SectionVyAA9EmptyViewVACyAA6ToggleVyAA4TextVGAA32_EnvironmentKeyTransformModifierVySbGGAMGSgGAA017_AppearanceActionN0VGAA0H0HPAuaYHPAtaYHpAsaYHPAiaYHPyHC_AraYHPAnaYHPyHC_AqA0hN0HPyHCHCAmaYHPyHCHC_HC_HC_AwaZHPyHCHC
+ _symbolic _____y_____4slot_Sb12isRCSEnabledSb0B11DisplayabletG s23_ContiguousArrayStorageC So18CTSubscriptionSlotV
+ _symbolic _____y_____y__________y_____y_____G_____ySbGGAFGSgG 7SwiftUI5GroupV AA7SectionV AA9EmptyViewV AA15ModifiedContentV AA6ToggleV AA4TextV AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____y_____y_____y_____AAy_____y_____G_____ySbGGAFGSgG_____G 7SwiftUI15ModifiedContentV AA5GroupV AA7SectionV AA9EmptyViewV AA6ToggleV AA4TextV AA32_EnvironmentKeyTransformModifierV AA017_AppearanceActionN0V
- ___swift_closure_destructor.73Tm
- _get_witness_table 7SwiftUI7SectionVyAA9EmptyViewVAA15ModifiedContentVyAA6ToggleVyAA4TextVGAA32_EnvironmentKeyTransformModifierVySbGGAKGSgAA0E0HpAqaSHPAeaSHPyHC_ApaSHPAlaSHPyHC_AoA0eM0HPyHCHCAkaSHPyHCHC_HC
- _swift_retain_x22
- _swift_retain_x26
CStrings:
+ "%{public}s failed for slot %{public}ld: %{public}@"
+ ", cellularDataRequirement="
+ ", disablementReason="
+ ", enabledByDefault="
+ ", quickSwitchRole="
+ ", supportsComposingIndicator="
+ ", userPreferenceForSwitch="
+ "Active subscription changing for slot %{public}ld: slotDropped=%{bool,public}d, labelChanged=%{bool,public}d, phoneNumberChanged=%{bool,public}d"
+ "Active subscription count changing: %{public}ld -> %{public}ld, slots [%{public}s] -> [%{public}s]"
+ "Cannot reload RCS specifiers: userInfo is not a CTMessagingSettingsProvider"
+ "Could not notify observers of MMS enabled change: no Darwin notify center"
+ "Creating MMS specifier as a link pane for %{public}ld subscriptions, slots: %{public}s"
+ "Creating MMS specifier as a single switch for slot %{public}ld"
+ "Creating RCS specifier as a link pane for %{public}ld subscription(s)"
+ "Dismissing RCS pane: no displayable content. partiallyActiveSimSupported=%{bool,public}d, subscription slots=[%{public}s]"
+ "Dropping MMS enabled write for key %{public}s: could not open %{public}s defaults suite"
+ "Dropping MMS enabled=%{bool,public}d write: specifier userInfo is not a CTXPCContextInfo"
+ "First RCS system configuration observed for slot %{public}ld: operationStatus=[%{public}s], encryption=[%{public}s], business=[%{public}s]"
+ "MMS default disabled for slot %{public}ld: carrier bundle MMS value is not a dictionary"
+ "MMS default disabled for slot %{public}ld: no MMS key in carrier bundle"
+ "MMS default enabled for slot %{public}ld: carrier bundle has no MMSDefaultEnabled key"
+ "MMS default for slot %{public}ld from carrier bundle: %{bool,public}d"
+ "MMS pane loaded"
+ "MMS pane title not set: specifier userInfo is not a CTMessagingSettingsProvider"
+ "MMS pane will be blank: hosting controller has no view"
+ "MMS pane will be blank: specifier userInfo is not a CTMessagingSettingsProvider"
+ "Not creating MMS specifier: no MMS-capable subscriptions"
+ "Not creating RCS specifier: RCSOnPartiallyActiveSim is enabled and no subscription is displayable"
+ "Not creating RCS specifier: no RCS-capable subscriptions"
+ "RCS business messages switch: displayed=%{bool,public}d, enabled=%{bool,public}d, interactive=%{bool,public}d"
+ "RCS business messaging capabilities changing for slot %{public}ld: [%{public}s] -> [%{public}s]"
+ "RCS enabled changing for slot %{public}ld: %{bool,public}d -> %{bool,public}d"
+ "RCS encryption capabilities changing for slot %{public}ld: [%{public}s] -> [%{public}s]"
+ "RCS encryption switch: displayed=%{bool,public}d, enabled=%{bool,public}d, interactive=%{bool,public}d"
+ "RCS messaging capabilities changing for slot %{public}ld: [%{public}s] -> [%{public}s]"
+ "RCS operation status changing for slot %{public}ld: [%{public}s] -> [%{public}s]"
+ "RCS pane loaded"
+ "RCS pane rendered %{public}ld toggle(s) (multi-subscription layout) for slots [%{public}s], from %{public}ld RCS subscription(s)"
+ "RCS pane rendered 1 toggle (single-subscription layout) for slot %{public}ld"
+ "RCS pane title not set: specifier userInfo is not a CTMessagingSettingsProvider"
+ "RCS pane will be blank: hosting controller has no view"
+ "RCS pane will be blank: specifier userInfo is not a CTMessagingSettingsProvider"
+ "RCS specifier displayability for slot %{public}ld: rcsEnabled=%{bool,public}d, displayable=%{bool,public}d"
+ "Reloading MMS specifiers"
+ "Reloading RCS specifiers"
+ "Reporting MMS as disabled: specifier userInfo is not a CTXPCContextInfo"
+ "Setting MMS enabled: %{bool,public}d for key: %{public}s, slot: %{public}ld"
+ "Setting RCS business messages enabled: %{bool,public}d"
+ "Setting RCS enabled: %{bool,public}d for slot: %{public}ld"
+ "Setting RCS encryption enabled: %{bool,public}d"
+ "disableBusinessMessaging"
+ "enableBusinessMessaging"
+ "notificationDisplay="
+ "registrationState="
+ "setLazuliEncryption(%{bool,public}d) failed for slot %{public}ld: %{public}@"
- "Active contexts have changed to: %@"
- "RCS business messaging capabilities have changed"
- "RCS enabled changing %{bool}d -> %{bool}d"
- "RCS encryption capabilities have changed"
- "RCS messaging capabilities have changed"
- "RCS operation status has changed"
- "RCS system configuration has changed to: %s"
- "Setting MMS enabled: %{bool}d for key: %s"
- "Setting RCS enabled: %{bool}d for: %@"
```
