## RemotePairingDevice

> `/System/Library/PrivateFrameworks/RemotePairingDevice.framework/RemotePairingDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe74ec` | `0xe8ca4` | **`+0x17b8`** |
| `__AUTH.__objc_data` | `0x2e0` | `0x680` | **`+0x3a0`** |
| `__DATA_DIRTY.__objc_data` | `0x640` | `0x2a0` | **`-0x3a0`** |
| `__TEXT.__const` | `0x11cb0` | `0x11f60` | **`+0x2b0`** |
| `__TEXT.__cstring` | `0x5c6c` | `0x5f0c` | **`+0x2a0`** |
| `__AUTH_CONST.__const` | `0xf240` | `0xf438` | **`+0x1f8`** |
| `__AUTH_CONST.__objc_const` | `0x4a00` | `0x4b68` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x446c` | `0x45cc` | **`+0x160`** |
| `__AUTH.__data` | `0x748` | `0x880` | **`+0x138`** |
| `__TEXT.__constg_swiftt` | `0x423c` | `0x4348` | **`+0x10c`** |
| `__TEXT.__unwind_info` | `0x48a8` | `0x4968` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x3c08` | `0x3cb0` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x41ec` | `0x4288` | **`+0x9c`** |
| `__DATA.__data` | `0x28c0` | `0x2940` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x2f80` | `0x2ff0` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0x3be0` | `0x3c30` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x2cdc` | `0x2d18` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x1890` | `0x18a8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x208` | `0x21c` | **`+0x14`** |
| `__TEXT.__swift5_mpenum` | `0x178` | `0x18c` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x490` | `0x4a4` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x118` | `0x128` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x788` | `0x790` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x480` | `0x488` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xce0` | `0xce8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x58` | `0x5c` | **`+0x4`** |

### Other Changes

```diff

-280.0.0.0.0
+280.0.5.0.0

-  Functions: 9239
-  Symbols:   2559
-  CStrings:  753
+  Functions: 9299
+  Symbols:   2580
+  CStrings:  767
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ __DATA__TtC19RemotePairingDevice35AlwaysApprovePairingPolicyValidator
+ __DATA__TtC19RemotePairingDevice35AlwaysDeclinePairingPolicyValidator
+ __IVARS__TtC19RemotePairingDevice35AlwaysDeclinePairingPolicyValidator
+ __METACLASS_DATA__TtC19RemotePairingDevice35AlwaysApprovePairingPolicyValidator
+ __METACLASS_DATA__TtC19RemotePairingDevice35AlwaysDeclinePairingPolicyValidator
+ ___swift_closure_destructor.184Tm
+ ___swift_closure_destructor.320Tm
+ ___swift_closure_destructor.362Tm
+ _get_enum_tag_for_layout_string 19RemotePairingDevice0B23PolicyValidationOutcomeO
+ _strerror
+ _swift_release_x4
+ _symbolic $s19RemotePairingDevice0B15PolicyValidatorP
+ _symbolic Sb14promptRequired_t
+ _symbolic _____ 19RemotePairingDevice013AlwaysApproveB15PolicyValidatorC
+ _symbolic _____ 19RemotePairingDevice013AlwaysDeclineB15PolicyValidatorC
+ _symbolic _____ 19RemotePairingDevice04CoreC19AuditLoggingStringsO
+ _symbolic _____ 19RemotePairingDevice0B23PolicyValidationOutcomeO
+ _symbolic _____ 19RemotePairingDevice19DeveloperModeStatusO
+ _symbolic _____Iegn_Sg 19RemotePairingDevice0B7OutcomeO
+ _symbolic _____Sg 19RemotePairingDevice0B4DataV
+ _symbolic _____Sg18initialPairingData_t 19RemotePairingDevice0B4DataV
+ _symbolic ______p 19RemotePairingDevice0B15PolicyValidatorP
+ _type_layout_string 19RemotePairingDevice0B23PolicyValidationOutcomeO
+ _type_layout_string Sb14promptRequired_t
- ___swift_closure_destructor.179Tm
- ___swift_closure_destructor.221Tm
- ___swift_closure_destructor.330Tm
- _type_layout_string 19RemotePairingDevice24ControlChannelConnectionC7OptionsO4HostV
CStrings:
+ "%{public}s: Pairing policy allowed; configuring pairing session"
+ "%{public}s: Pairing policy validation completed but connection is no longer in correct state to handle response"
+ "%{public}s: Rejecting PairSetup because ManagedConfiguration requires a challenge response and this flow has no return path to deliver one"
+ "%{public}s: Rejecting PairSetup because pairing policy rejected the attempt: %{public}s"
+ "%{public}s: _doConfigureNewPairingSession"
+ "Developer mode must be enabled on the device."
+ "Display name of the audit activity that is shown to the user for a recent screen viewing session"
+ "Display name of the audit activity that is shown to the user for a screenshot capture"
+ "Screen viewing session"
+ "Screenshot captured"
+ "Subtitle of the notification that is shown to make the user aware of a recent screen viewing session"
+ "This device was viewed remotely from Mac"
+ "Title of the notification that is shown to make the user aware of a recent screen viewing session"
+ "developermodestatus"
+ "security.mac.amfi.developer_mode_status.changed"
- "%{public}s: Not requesting user consent for pairing attempt as requireUserConsentForPairing is set to false"
```
