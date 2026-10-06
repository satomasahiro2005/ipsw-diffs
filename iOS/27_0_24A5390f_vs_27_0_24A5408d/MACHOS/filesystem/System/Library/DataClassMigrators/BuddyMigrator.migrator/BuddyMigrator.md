## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27edc` | `0x2b034` | **`+0x3158`** |
| `__DATA.__objc_const` | `0x3748` | `0x3ac0` | **`+0x378`** |
| `__TEXT.__objc_methname` | `0x4985` | `0x4cf3` | **`+0x36e`** |
| `__TEXT.__const` | `0xce8` | `0xf38` | **`+0x250`** |
| `__DATA_CONST.__const` | `0x1068` | `0x12a0` | **`+0x238`** |
| `__DATA.__objc_data` | `0x1738` | `0x1958` | **`+0x220`** |
| `__TEXT.__eh_frame` | `0xdfc` | `0x1014` | **`+0x218`** |
| `__TEXT.__oslogstring` | `0x2c11` | `0x2df1` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x1a70` | `0x1c30` | **`+0x1c0`** |
| `__DATA.__bss` | `0x650` | `0x7d0` | **`+0x180`** |
| `__TEXT.__objc_stubs` | `0x2f80` | `0x30e0` | **`+0x160`** |
| `__DATA.__data` | `0x1018` | `0x1170` | **`+0x158`** |
| `__TEXT.__constg_swiftt` | `0x998` | `0xab4` | **`+0x11c`** |
| `__TEXT.__unwind_info` | `0xbc8` | `0xcc0` | **`+0xf8`** |
| `__TEXT.__swift5_capture` | `0x3cc` | `0x4b4` | **`+0xe8`** |
| `__TEXT.__auth_stubs` | `0x10a0` | `0x1180` | **`+0xe0`** |
| `__TEXT.__cstring` | `0xfc5` | `0x10a2` | **`+0xdd`** |
| `__TEXT.__swift5_typeref` | `0xac0` | `0xb9c` | **`+0xdc`** |
| `__TEXT.__objc_classname` | `0xcea` | `0xd9a` | **`+0xb0`** |
| `__TEXT.__objc_methtype` | `0xcd4` | `0xd75` | **`+0xa1`** |
| `__DATA.__objc_selrefs` | `0x1078` | `0x1118` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x486` | `0x4f7` | **`+0x71`** |
| `__DATA_CONST.__auth_got` | `0x860` | `0x8d0` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x578` | `0x5e4` | **`+0x6c`** |
| `__DATA_CONST.__auth_ptr` | `0x180` | `0x1b0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x480` | `0x4a8` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x88` | `0xa8` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x128` | `0x140` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0x78` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x84` | `0x9c` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x88` | `0xa0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x64` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x158` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0xb0` | `0xc0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x38` | `0x44` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x78` | `0x84` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x110` | `0x114` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-5409.0.0.0.0
+5411.0.0.0.0

+  - /System/Library/PrivateFrameworks/LockdownMode.framework/LockdownMode

-  Functions: 906
-  Symbols:   416
-  CStrings:  1239
+  Functions: 989
+  Symbols:   421
+  CStrings:  1289
Symbols:
+ _OBJC_CLASS_$__TtC13BuddyMigrator37BuddyCameraControlHardwareEligibility
+ _OBJC_METACLASS_$__TtC13BuddyMigrator37BuddyCameraControlHardwareEligibility
+ _swift_initStackObject
+ _swift_release_x22
+ _swift_setDeallocating
CStrings:
+ "$__lazy_storage_$_manager"
+ ";"
+ "@\"<_TtP13BuddyMigrator20LockdownModeProvider_>\""
+ "@\"BYChronicle\"16@0:8"
+ "BYDeviceConfiguration"
+ "BuddyLockdownModeManager"
+ "BuddyMigrator.BuddyCameraControlHardwareEligibility"
+ "BuddyMigrator.LockdownModeManager"
+ "BuddyMigrator: Lockdown mode is on post restore with no chronicle record. Creating chronicle baseline for lockdown mode confirmation."
+ "BuddyMigrator: Lockdown mode is on with no chronicle record and not an A or E release. Creating chronicle baseline for lockdown."
+ "BuddyMigrator: Queueing mini-buddy for Lockdown Mode confirmation"
+ "BuddyMigrator: Skip Visual Intelligence / Camera Control upsell"
+ "Somehow have empty first supported OS release"
+ "Somehow have nil first supported OS release"
+ "T@\"<_TtP13BuddyMigrator20LockdownModeProvider_>\",&,N,V_lockdownModeProvider"
+ "T@\"BYChronicle\",N,&"
+ "T@\"BYChronicle\",N,&,Vchronicle"
+ "TB,N,VhasStagedEnablement"
+ "Tq,N,R"
+ "_TtC13BuddyMigrator37BuddyCameraControlHardwareEligibility"
+ "_TtP13BuddyMigrator20LockdownModeProvider_"
+ "_lockdownModeProvider"
+ "_suppressLockdownModeConfirmationForRestore"
+ "accountState"
+ "acknowledgeWithCompletionHandler:"
+ "acknowledgementOnly"
+ "beginServicesTermsRequirementCheck"
+ "buildVersion"
+ "deviceConfiguration"
+ "deviceState"
+ "enable(strategy:)"
+ "enableWithStrategy:completionHandler:"
+ "fetchAccountState()"
+ "fetchAccountStateWithCompletionHandler:"
+ "hasCrossedAOrEBoundary"
+ "hasStagedEnablement"
+ "hasThreatNotification"
+ "inStoreDemoMode"
+ "initWithChronicle:deviceConfiguration:"
+ "initWithDeviceProvider:"
+ "isIntroductoryHardware"
+ "lockdownModeProvider"
+ "lockdownModeUpgradeVariantNeedsToShow"
+ "osVersionIsAorERelease:"
+ "requireAuthentication"
+ "setHasStagedEnablement:"
+ "setLockdownModeProvider:"
+ "v24@0:8@\"BYChronicle\"16"
+ "v24@0:8@?<v@?>16"
+ "v32@0:8q16@?24"
+ "v32@0:8q16@?<v@?@\"NSError\">24"
- ":"
```
