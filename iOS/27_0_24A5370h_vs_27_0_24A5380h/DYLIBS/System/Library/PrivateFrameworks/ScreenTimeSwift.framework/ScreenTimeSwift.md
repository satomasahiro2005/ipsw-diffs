## ScreenTimeSwift

> `/System/Library/PrivateFrameworks/ScreenTimeSwift.framework/ScreenTimeSwift`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x82a58` | `0x83ad8` | **`+0x1080`** |
| `__DATA_DIRTY.__data` | `0x868` | `0x1488` | **`+0xc20`** |
| `__AUTH.__data` | `0x9b8` | `0x98` | **`-0x920`** |
| `__TEXT.__oslogstring` | `0x28bf` | `0x225f` | **`-0x660`** |
| `__DATA.__data` | `0x1140` | `0xf40` | **`-0x200`** |
| `__AUTH_CONST.__auth_got` | `0x11a8` | `0x13a0` | **`+0x1f8`** |
| `__TEXT.__cstring` | `0xf47` | `0xe37` | **`-0x110`** |
| `__AUTH_CONST.__const` | `0x2da0` | `0x2c98` | **`-0x108`** |
| `__AUTH.__objc_data` | `0xf0` | `—` | **`-0xf0`** |
| `__AUTH_CONST.__objc_const` | `0xed8` | `0xfc8` | **`+0xf0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0xf0` | **`+0xf0`** |
| `__TEXT.__const` | `0x436c` | `0x442c` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x1c6b` | `0x1cfb` | **`+0x90`** |
| `__DATA.__bss` | `0x5930` | `0x59b0` | **`+0x80`** |
| `__DATA_DIRTY.__bss` | `0x200` | `0x280` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0xd58` | `0xdc8` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x1304` | `0x1350` | **`+0x4c`** |
| `__TEXT.__swift5_typeref` | `0x16fe` | `0x1748` | **`+0x4a`** |
| `__TEXT.__objc_methlist` | `0x200` | `0x248` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x374` | `0x394` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x10ac` | `0x10c8` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x2b0` | `0x2c8` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x198` | `0x1b0` | **`+0x18`** |
| `__DATA.__common` | `0x70` | `0x68` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x310` | `0x318` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1778` | `0x1780` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x12c` | `0x130` | **`+0x4`** |

### Other Changes

```diff

-640.0.100.0.0
+645.1.100.0.0

-  Functions: 2130
-  Symbols:   868
-  CStrings:  234
+  Functions: 2148
+  Symbols:   881
+  CStrings:  218
Symbols:
+ _OBJC_CLASS_$_NSCalendar
+ _OBJC_CLASS_$_STOrganizationSettingsRestrictionUtility
+ _OBJC_CLASS_$_STRegulatoryIntelligenceSiriPolicy
+ _OBJC_CLASS_$_STRestrictionPayloadUtility
+ _STLocalDateFromUTCErasedDate
+ ___swift_closure_destructor.20Tm
+ ___swift_closure_destructor.82Tm
+ ___swift_memcpy4_1
+ _objc_autoreleaseReturnValue
+ _symbolic So28STAdminPersistenceControllerC
+ _symbolic _____ 15ScreenTimeSwift0aB16SettingsMigratorV32ResolvedIntelligenceRestrictionsV
+ _symbolic _____Sg 26ScreenTimeSettingsServices0abC0C31IntelligenceAndSiriRestrictionsV0G6PolicyO
+ _symbolic _____Sg 26ScreenTimeSettingsServices0abC0C8DowntimeV16EnablementPolicyO
+ _symbolic _____Sg_ABt 26ScreenTimeSettingsServices0abC0C31IntelligenceAndSiriRestrictionsV0G6PolicyO
+ _symbolic _____So8NSNumberCc 15ScreenTimeSwift0aB16SettingsMigratorV32ResolvedIntelligenceRestrictionsV
+ _type_layout_string 15ScreenTimeSwift0aB16SettingsMigratorV32ResolvedIntelligenceRestrictionsV
- ___swift_closure_destructor.14Tm
- ___swift_closure_destructor.71Tm
- _symbolic _____y_____G s23_ContiguousArrayStorageC 26ScreenTimeSettingsServices0deF0C16PermissionPolicyO
CStrings:
+ "Failed to resolve Intelligence & Siri restriction: %{public}s. Falling back to the more restrictive value."
+ "STRegulatoryUIPolicy.%{public}s: creating fallback policy"
- "STRegulatoryUIPolicy.%{public}s: Adult verification regulation=%{bool,public}d"
- "STRegulatoryUIPolicy.%{public}s: Adult verification required regulation: unknown. Using fallback values."
- "STRegulatoryUIPolicy.%{public}s: Communication Safety regulation for local child/teen: unknown. Using fallback values."
- "STRegulatoryUIPolicy.%{public}s: Communication Safety regulation for remote child/teen: unknown. Keeping permissive values."
- "STRegulatoryUIPolicy.%{public}s: Communication Safety regulation=%{bool,public}d, policy: forcedToEnabled=%{bool,public}d, editable=%{bool,public}d, connectToFamilyBanner=%{bool,public}d, commSafetyValueChangePrompts=%{public}s"
- "STRegulatoryUIPolicy.%{public}s: Fallback policy created"
- "STRegulatoryUIPolicy.%{public}s: Revoke access regulation: not found in regulations dictionary"
- "STRegulatoryUIPolicy.%{public}s: Revoke access regulation=%{bool,public}d, policy: changePrompts=%{public}s, showsFullList=%{bool,public}d, appsRatingEditable=%{bool,public}d"
- "STRegulatoryUIPolicy.%{public}s: Top-level restrictions policy: changePrompts=%{public}s"
- "STRegulatoryUIPolicy.%{public}s: Web Content Filter regulation for local child/teen: unknown. Using fallback values."
- "STRegulatoryUIPolicy.%{public}s: Web Content Filter regulation for remote child/teen: unknown. Keeping permissive values."
- "STRegulatoryUIPolicy.%{public}s: Web Content Filter regulation=%{bool,public}d, policy: forcedToLimitAdultWebsites=%{bool,public}d, editable=%{bool,public}d, connectToFamilyBanner=%{bool,public}d, changePrompts=%{public}s"
- "STRegulatoryUIPolicy.%{public}s: context has unknown account type. Assuming signed-out user."
- "STRegulatoryUIPolicy.%{public}s: for signed-out user, using permissive policy by not making any changes."
- "updatePolicyForChildOrTeen(_:withConfiguration:context:)"
- "updatePolicyWithAdultVerification(_:withConfiguration:context:)"
- "updatePolicyWithRevokeAccess(_:withConfiguration:context:)"
- "updatePolicyWithTopLevelRestrictions(_:withConfiguration:context:)"
```
