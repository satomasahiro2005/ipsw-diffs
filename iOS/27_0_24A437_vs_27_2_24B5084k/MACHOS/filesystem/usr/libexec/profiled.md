## profiled

> `/usr/libexec/profiled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc8fb4` | `0xc93bc` | **`+0x408`** |
| `__TEXT.__cstring` | `0xa8ea` | `0xa9ea` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x2910` | `0x2a00` | **`+0xf0`** |
| `__TEXT.__objc_methname` | `0x16c13` | `0x16b77` | **`-0x9c`** |
| `__TEXT.__objc_stubs` | `0x13480` | `0x13400` | **`-0x80`** |
| `__DATA_CONST.__auth_got` | `0x1498` | `0x1510` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x6284` | `0x620c` | **`-0x78`** |
| `__TEXT.__objc_methtype` | `0x2412` | `0x23b2` | **`-0x60`** |
| `__DATA_CONST.__got` | `0x2118` | `0x2148` | **`+0x30`** |
| `__DATA.__objc_const` | `0x70b0` | `0x7090` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x54d8` | `0x54b8` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0x86c0` | `0x86e0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xfeb0` | `0xfed0` | **`+0x20`** |
| `__DATA.__common` | `0x48` | `0x60` | **`+0x18`** |
| `__TEXT.__const` | `0x137e` | `0x138e` | **`+0x10`** |
| `__DATA.__data` | `0x8f8` | `0x900` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2483.2.6.0.0
+2483.40.14.0.0

-  Functions: 2741
-  Symbols:   1797
-  CStrings:  5764
+  Functions: 2737
+  Symbols:   1816
+  CStrings:  5766
Symbols:
+ _$s2os12OSSignpostIDV3logACSo03OS_a1_D0C_tcfC
+ _$s2os12OSSignpostIDV8rawValues6UInt64Vvg
+ _$s2os12OSSignpostIDVMa
+ _$s2os12OSSignposterV9logHandleSo03OS_a1_C0Cvg
+ _$s2os12OSSignposterV9subsystem8categoryACSS_SStcfC
+ _$s2os12OSSignposterVMa
+ _$s2os15OSSignpostErrorO9doubleEndyA2CmFWC
+ _$s2os15OSSignpostErrorOMa
+ _$s2os23OSSignpostIntervalStateC10signpostIDAA0bF0Vvg
+ _$s2os23OSSignpostIntervalStateC2id6isOpenAcA0B2IDV_Sbtcfc
+ _$s2os23OSSignpostIntervalStateCMa
+ _$s2os28checkForErrorAndConsumeState5stateAA010OSSignpostD0OAA0i8IntervalG0C_tF
+ _$sSo18os_signpost_type_ta0A0E3endABvgZ
+ _$sSo18os_signpost_type_ta0A0E5beginABvgZ
+ _$sSo9OS_os_logC0B0E16signpostsEnabledSbvg
+ _$ss12StaticStringV11descriptionSSvg
+ _MCSendAllowCloudSyncChangedNotification
+ _OBJC_CLASS_$_RMErSSOStore
+ __os_signpost_emit_with_name_impl
+ _swift_release_x27
- _swift_release_x22
CStrings:
+ "%s: shouldDoPostLoginWork: %d"
+ "%{public}s"
+ "-[MCProfileServiceServer workerQueueNotifyUserLoggedIn]"
+ "ERROR_NOT_INTERNAL_VARIANT"
+ "[Error] Interval already ended"
+ "cleanUpDirtyEnrollmentState"
+ "com.apple.ManagedConfiguration.MCProfileServicer"
+ "enableTelemetry=YES"
+ "enrollmentFlowControllerWithPresenter:managedConfigurationHelper:rmStoreHelper:"
+ "ms-synchronizer-applyEffectiveSettings"
- "appSignerIdentityForBundleID:"
- "provisiongProfileUUIDsForSignerIdentity:completion:"
- "provisioningProfileUUIDsForSignerIdentity:"
- "signerIdentityForBundleID:completion:"
- "syncTrustedCodeSigningIdentitiesWithCompletion:"
- "trustedCodeSigningIdentitiesWithCompletion:"
- "v32@0:8@\"NSString\"16@?<v@?@\"NSSet\"@\"NSError\">24"
- "v32@0:8@\"NSString\"16@?<v@?@\"NSString\"@\"NSError\">24"
```
