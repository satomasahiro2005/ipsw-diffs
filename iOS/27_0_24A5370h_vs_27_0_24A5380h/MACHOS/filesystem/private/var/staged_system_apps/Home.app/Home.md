## Home

> `/private/var/staged_system_apps/Home.app/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbf8dc` | `0xc1dec` | **`+0x2510`** |
| `__TEXT.__oslogstring` | `0x7003` | `0x7233` | **`+0x230`** |
| `__TEXT.__eh_frame` | `0x2980` | `0x2a50` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x70e0` | `0x71a8` | **`+0xc8`** |
| `__TEXT.__objc_methname` | `0x13191` | `0x1310b` | **`-0x86`** |
| `__TEXT.__swift5_typeref` | `0x4612` | `0x4694` | **`+0x82`** |
| `__TEXT.__cstring` | `0x7022` | `0x7092` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0xbaa0` | `0xbb00` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x33e0` | `0x3430` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x126c` | `0x12bc` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2ae8` | `0x2b30` | **`+0x48`** |
| `__TEXT.__const` | `0x3324` | `0x3364` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1280` | `0x12b0` | **`+0x30`** |
| `__DATA.__data` | `0x542c` | `0x5454` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x1a00` | `0x1a28` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x44d8` | `0x44f8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x5a2c` | `0x5a44` | **`+0x18`** |
| `__DATA.__objc_data` | `0x1620` | `0x1630` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x1304` | `0x1314` | **`+0x10`** |
| `__DATA.__objc_const` | `0x7948` | `0x7950` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xb28` | `0xb30` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1a8` | `0x1ac` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xb8` | `0xbc` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xb4` | `0xb8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1227.0.0.0.1
+1232.3.0.0.0

-  Functions: 3979
-  Symbols:   1783
-  CStrings:  4458
+  Functions: 3996
+  Symbols:   1791
+  CStrings:  4472
Symbols:
+ _$s10Foundation12URLQueryItemV4name5valueACSSh_SSSghtcfC
+ _$s10Foundation12URLQueryItemVMa
+ _$s10Foundation12URLQueryItemVMn
+ _$s13HomeDataModel27CoreSpotlightSearchProviderC6clipID04fromE8Activity10Foundation4UUIDVSgSo06NSUserK0C_tFZ
+ _$s13HomeDataModel27CoreSpotlightSearchProviderCMa
+ _$s13HomeDataModel6CameraO5EventO18clipNavigationInfo9forClipID10Foundation4UUIDV013cameraProfileK0_AH4DateV4datetSgAJ_tYaFZ
+ _$s13HomeDataModel6CameraO5EventO18clipNavigationInfo9forClipID10Foundation4UUIDV013cameraProfileK0_AH4DateV4datetSgAJ_tYaFZTu
+ _HFForceNativeMatter
+ _OBJC_CLASS_$_NSISO8601DateFormatter
- _swift_willThrowTypedImpl
CStrings:
+ "%s-%s Could not resolve clip %{public}s in store or Spotlight index; staying on dashboard"
+ "%s-%s Redirecting Spotlight tap to camera clip %{public}s on camera profile %{public}s, startDate %{public}s"
+ "%s-%s Scene is %ld; handling URL directly to avoid silent drop"
+ "%s-%s Unknown activation state %ld; handling URL directly"
+ "%s-%s applicationActiveFuture is nil while foregroundInactive; handling URL directly"
+ "<%s: %s> Skipping home sidebar selection. No home group or no home group selection."
+ "HFPreferencesForceNativeMatterKey = %{BOOL}d"
+ "activationState"
+ "homeKitObjectURLForDestination:secondaryDestination:UUID:queryItems:"
+ "openCameraClipFromSpotlight(_:scene:)"
+ "openURL(_:whenActiveIn:)"
+ "selectHomeSidebarDestination"
+ "selectHomeSidebarDestination()"
+ "setFormatOptions:"
```
