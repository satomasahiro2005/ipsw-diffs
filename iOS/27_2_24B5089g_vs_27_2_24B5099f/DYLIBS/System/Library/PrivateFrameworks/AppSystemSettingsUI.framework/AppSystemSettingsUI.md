## AppSystemSettingsUI

> `/System/Library/PrivateFrameworks/AppSystemSettingsUI.framework/AppSystemSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25040` | `0x260b4` | **`+0x1074`** |
| `__TEXT.__cstring` | `0x237c` | `0x263c` | **`+0x2c0`** |
| `__TEXT.__oslogstring` | `0x855` | `0xa75` | **`+0x220`** |
| `__AUTH_CONST.__objc_const` | `0x1738` | `0x18b0` | **`+0x178`** |
| `__DATA_CONST.__const` | `0x508` | `0x620` | **`+0x118`** |
| `__AUTH_CONST.__cfstring` | `0x1600` | `0x16c0` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0xd04` | `0xd7c` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0xf30` | `0xf98` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x9a8` | `0xa08` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x2f8` | `0x348` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x384` | `0x3a4` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x84` | `0xa0` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x720` | `0x730` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xb70` | `0xb78` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x70` | `0x78` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x30` | `0x38` | **`+0x8`** |

### Other Changes

```diff

-2027.1.3.0.0
+2027.1.4.0.0

+  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 741
-  Symbols:   1043
-  CStrings:  329
+  Functions: 760
+  Symbols:   1082
+  CStrings:  352
Symbols:
+ -[AUSiriPolicyController .cxx_destruct]
+ -[AUSiriPolicyController applyUseWithSiriEnabled:]
+ -[AUSiriPolicyController initWithAppBundleID:reloadSpecifiersHandler:presentViewControllerHandler:]
+ -[AUSiriPolicyController isUseWithSiriEnabled:]
+ -[AUSiriPolicyController reconcileUseWithSiriEnabled]
+ -[AUSiriPolicyController refreshUseWithSiriState]
+ -[AUSiriPolicyController setUseWithSiriEnabled:specifier:]
+ -[AUSiriPolicyController specifiers]
+ -[AUSystemSettingsSpecifiersProvider useWithSiriSpecifiers]
+ GCC_except_table144
+ _OBJC_CLASS_$_AFPreferences
+ _OBJC_CLASS_$_AUSiriPolicyController
+ _OBJC_IVAR_$_AUSiriPolicyController._bundleID
+ _OBJC_IVAR_$_AUSiriPolicyController._presentViewControllerHandler
+ _OBJC_IVAR_$_AUSiriPolicyController._reloadSpecifiersHandler
+ _OBJC_IVAR_$_AUSiriPolicyController._useWithSiriAvailable
+ _OBJC_IVAR_$_AUSiriPolicyController._useWithSiriEnabled
+ _OBJC_IVAR_$_AUSiriPolicyController._writeQueue
+ _OBJC_IVAR_$_AUSystemSettingsSpecifiersProvider._siriPrivacyController
+ _OBJC_METACLASS_$_AUSiriPolicyController
+ _PSResetCachedSiriKitTCCEnabledAppIds
+ __OBJC_$_INSTANCE_METHODS_AUSiriPolicyController
+ __OBJC_$_INSTANCE_VARIABLES_AUSiriPolicyController
+ __OBJC_CLASS_RO_$_AUSiriPolicyController
+ __OBJC_METACLASS_RO_$_AUSiriPolicyController
+ ___49-[AUSiriPolicyController refreshUseWithSiriState]_block_invoke
+ ___50-[AUSiriPolicyController applyUseWithSiriEnabled:]_block_invoke
+ ___53-[AUSiriPolicyController reconcileUseWithSiriEnabled]_block_invoke
+ ___53-[AUSiriPolicyController reconcileUseWithSiriEnabled]_block_invoke_2
+ ___58-[AUSiriPolicyController setUseWithSiriEnabled:specifier:]_block_invoke
+ ___59-[AUSystemSettingsSpecifiersProvider useWithSiriSpecifiers]_block_invoke
+ ___59-[AUSystemSettingsSpecifiersProvider useWithSiriSpecifiers]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e11_v16?0B8B12ls32l8
+ ___block_descriptor_40_e8_32s_e8_v12?0B8ls32l8
+ ___block_descriptor_40_e8_32w_e29_v20?0"UIViewController"8B16lw32l8
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_41_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40s_e23_v16?0"UIAlertAction"8ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e5_v8?0ls32l8s40l8
CStrings:
+ "%{public}s: Confirming Use with Siri turn-off for %{public}@, which announces notifications"
+ "%{public}s: Turning Use with Siri %{public}s for %{public}@"
+ "%{public}s: Turning off Announce Notifications for %{public}@ alongside Use with Siri"
+ "%{public}s: Use with Siri does not apply to %{public}@, leaving the row hidden"
+ "%{public}s: Use with Siri is %{public}s for %{public}@"
+ "%{public}s: Use with Siri left on for %{public}@, the turn-off alert was cancelled"
+ "%{public}s: Use with Siri write for %{public}@ did not take effect, reverting the switch"
+ "-[AUSiriPolicyController applyUseWithSiriEnabled:]_block_invoke"
+ "-[AUSiriPolicyController reconcileUseWithSiriEnabled]_block_invoke_2"
+ "-[AUSiriPolicyController refreshUseWithSiriState]_block_invoke"
+ "-[AUSiriPolicyController setUseWithSiriEnabled:specifier:]"
+ "-[AUSiriPolicyController setUseWithSiriEnabled:specifier:]_block_invoke"
+ "Apps you use with Siri may send information like your contacts and other data to Apple to process your requests."
+ "Turn Off Use with Siri"
+ "Turning off Use with Siri will also turn off Announce Notifications with Siri"
+ "USE_WITH_SIRI"
+ "USE_WITH_SIRI_GROUP"
+ "Use with Siri Requests"
+ "com.apple.Settings.AppSystemSettingsUI.useWithSiri"
+ "off"
+ "on"
+ "v12@?0B8"
+ "v16@?0B8B12"
+ "v20@?0@\"UIViewController\"8B16"
+ "\xb1"
- "&'"
- "\x91"
```
