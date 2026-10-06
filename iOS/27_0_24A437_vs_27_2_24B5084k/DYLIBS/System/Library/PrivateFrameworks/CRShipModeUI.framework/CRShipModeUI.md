## CRShipModeUI

> `/System/Library/PrivateFrameworks/CRShipModeUI.framework/CRShipModeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bf50` | `0x2e264` | **`+0x2314`** |
| `__TEXT.__cstring` | `0x32e0` | `0x38a0` | **`+0x5c0`** |
| `__AUTH_CONST.__const` | `0x1240` | `0x13c0` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x1019` | `0x1139` | **`+0x120`** |
| `__DATA.__bss` | `0x600` | `0x700` | **`+0x100`** |
| `__DATA.__data` | `0xc90` | `0xd60` | **`+0xd0`** |
| `__TEXT.__const` | `0xcc0` | `0xd40` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x650` | `0x6a4` | **`+0x54`** |
| `__TEXT.__eh_frame` | `0xe60` | `0xea0` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x538` | `0x56c` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0x475` | `0x4a5` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0xd30` | `0xd5c` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0x940` | `0x968` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x5e2` | `0x608` | **`+0x26`** |
| `__AUTH.__objc_data` | `0xbb0` | `0xbc0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x670` | `0x680` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x838` | `0x840` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x34` | `0x3c` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xc4` | `0xbc` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x94` | `0x98` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x40` | `0x44` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x4c` | `0x50` | **`+0x4`** |

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Functions: 818
+  Functions: 850

-  CStrings:  260
+  CStrings:  285
CStrings:
+ "%s: presenting prepare-for-shipping confirmation (named recipient: %{bool,public}d)"
+ "Apple will make the ship status of your iPhone available to any recipient with the device serial number."
+ "Body of the confirmation alert shown when the user taps Cancel on the discharge progress screen"
+ "Body of the confirmation alert shown when the user taps Continue on the partner confirmation screen and no recipient was reported by the server."
+ "Button in the confirmation alert that dismisses it and leaves the battery discharging"
+ "Button in the confirmation alert that drops the in-progress shipping preparation"
+ "CRShipMode.cancelPreparationAction"
+ "CRShipMode.cancelPreparationConfirmationMessage"
+ "CRShipMode.cancelPreparationConfirmationTitle"
+ "CRShipMode.continuePreparing"
+ "CRShipMode.prepareForShippingConfirmationMessageNoRecipient"
+ "CRShipMode.prepareForShippingConfirmationTitleNoRecipient"
+ "Cancel Preparation"
+ "Cancel shipping preparation?"
+ "Continue Preparing"
+ "Continue without recipient?"
+ "Ship to Unknown Recipient"
+ "Title of the confirmation alert shown when the user taps Cancel on the discharge progress screen"
+ "Title of the confirmation alert shown when the user taps Continue on the partner confirmation screen and no recipient was reported by the server."
+ "Your iPhone will be locked in ship mode for %@."
+ "Your iPhone will be locked in ship mode."
+ "Your iPhone will not be prepared to ship."
+ "cancelPreparationAction"
+ "cancelPreparationAlert"
+ "continuePreparingAction"
+ "presentCancelPreparationConfirmation: cancel confirmed — discarding the shipping preparation"
+ "presentCancelPreparationConfirmation: continue preparing — leaving the discharge running"
+ "presentPrepareForShippingConfirmation()"
+ "shipModeHeaderIcon"
- "Continue without a recipient?"
- "Your iPhone will be locked in Ship Mode for %@."
- "Your iPhone will be locked in Ship Mode."
- "checkmark.circle.badge.airplane"
```
