## appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7681c` | `0x7c7a0` | **`+0x5f84`** |
| `__TEXT.__eh_frame` | `0x5c20` | `0x5ef0` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x42f3` | `0x4593` | **`+0x2a0`** |
| `__DATA_CONST.__const` | `0x1790` | `0x19e8` | **`+0x258`** |
| `__TEXT.__swift5_capture` | `0x5b8` | `0x6d8` | **`+0x120`** |
| `__TEXT.__const` | `0x2f3c` | `0x304c` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x1958` | `0x19d8` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1281` | `0x12f1` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x1180` | `0x11c0` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x4fc` | `0x530` | **`+0x34`** |
| `__TEXT.__objc_methname` | `0x138d` | `0x13bd` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x4e7` | `0x517` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x868` | `0x894` | **`+0x2c`** |
| `__DATA.__objc_const` | `0xa00` | `0xa20` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1fd0` | `0x1ff0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x700` | `0x718` | **`+0x18`** |
| `__TEXT.__swift5_acfuncs` | `0x230` | `0x244` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x4ec` | `0x500` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x300` | `0x314` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x578` | `0x588` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xff0` | `0x1000` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xb6f` | `0xb7d` | **`+0xe`** |
| `__DATA.__common` | `0x70` | `0x68` | **`-0x8`** |
| `__DATA.__data` | `0x14a0` | `0x14a8` | **`+0x8`** |
| `__DATA.__objc_data` | `0x478` | `0x480` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7a8` | `0x7b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-46.0.5.0.0
+46.0.7.0.0

-  Functions: 1389
-  Symbols:   947
-  CStrings:  675
+  Functions: 1422
+  Symbols:   952
+  CStrings:  690
Symbols:
+ _$s18AppManagedFeatures11ConfiguringP27effectiveManagementProviderAA13CodableResultOyAA0fG0VSgAA0abC5ErrorOGyYaFTq
+ _$s18AppManagedFeatures11ConfiguringP27effectiveManagementProviderAA13CodableResultOyAA0fG0VSgAA0abC5ErrorOGyYaKFTqTE
+ _$s18AppManagedFeatures11RestrictingP4lock13configurationAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGAA17LockConfigurationV_tYaFTq
+ _$s18AppManagedFeatures11RestrictingP4lock13configurationAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGAA17LockConfigurationV_tYaKFTqTE
+ _$s18AppManagedFeatures15InstallProgressV5PhaseO7skippedyA2EmFWC
+ _$s18AppManagedFeatures17LockConfigurationV09excludingA17BundleIdentifiersSaySSGvg
+ _$s18AppManagedFeatures17LockConfigurationV09includingA17BundleIdentifiersSaySSGvg
+ _$s18AppManagedFeatures17LockConfigurationV19excludingWebDomainsSaySSGvg
+ _$s18AppManagedFeatures17LockConfigurationVMa
+ _$s18AppManagedFeatures17LockConfigurationVMn
+ _$s18AppManagedFeatures17LockConfigurationVSEAAMc
+ _$s18AppManagedFeatures17LockConfigurationVSeAAMc
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
- _$s18AppManagedFeatures11RestrictingP4lock12restrictionsAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGAA12RestrictionsV_tYaFTq
- _$s18AppManagedFeatures11RestrictingP4lock12restrictionsAA13CodableResultOyAA13EmptyResponseVAA0abC5ErrorOGAA12RestrictionsV_tYaKFTqTE
- _$s18AppManagedFeatures12RestrictionsV13excludingAppsSaySSGvg
- _$s18AppManagedFeatures12RestrictionsV13includingAppsSaySSGvg
- _$s18AppManagedFeatures12RestrictionsV19excludingWebDomainsSaySSGvg
- _$s18AppManagedFeatures12RestrictionsVMa
- _$s18AppManagedFeatures12RestrictionsVMn
- _$s18AppManagedFeatures12RestrictionsVSEAAMc
- _$s18AppManagedFeatures12RestrictionsVSeAAMc
CStrings:
+ "App Managed Features Error while getting current-or-pending configuration: %{public}@"
+ "AppManagedFeatures Error while deactivating: %{public}@"
+ "AppManagedFeatures Error while getting configuration: %{public}@"
+ "AppManagedFeatures Error while handling heartbeat: %{public}@"
+ "AppleLanguagePreferencesChangedNotification"
+ "Cannot deactivate: no current configuration on disk"
+ "CurrentOrPendingConfiguration"
+ "Error calling checkIn: %{public}@"
+ "Exiting appmanagedfeaturesd due to language change"
+ "ExtensionController"
+ "Failed to clear pending after promotion (current is live): %{public}@"
+ "Promoting Pending to Current"
+ "Skipping AppManagedFeatures lock removal (findMY)"
+ "There is no current or pending App Managed Features configuration on the device"
+ "There was an unknown error reading the current-or-pending App Managed Features configuration on the device: %{public}@"
+ "appmanagedfeaturesd-effective-configuration"
+ "com.apple.appmanagedfeatures.deactivation.notification"
+ "com.apple.appmanagedfeatures.enrollment"
+ "provider"
+ "removeObjectForKey:"
+ "setDouble:forKey:"
+ "totalLockDuration"
- "SafeFinancing Error while deactivating: %{public}@"
- "SafeFinancing Error while getting configuration: %{public}@"
- "SafeFinancing Error while handling heartbeat: %{public}@"
- "activationDurationDays"
- "com.apple.appmanagedfeatures.activate"
- "com.apple.appmanagedfeatures.deactivate"
- "com.apple.safefinancing.deactivation.notification"
```
