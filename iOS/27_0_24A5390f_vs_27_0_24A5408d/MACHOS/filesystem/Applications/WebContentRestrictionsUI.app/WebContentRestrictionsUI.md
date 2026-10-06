## WebContentRestrictionsUI

> `/Applications/WebContentRestrictionsUI.app/WebContentRestrictionsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f64` | `0x7080` | **`+0x11c`** |
| `__TEXT.__objc_methtype` | `0x384` | `0x3f2` | **`+0x6e`** |
| `__TEXT.__objc_methname` | `0xe67` | `0xec4` | **`+0x5d`** |
| `__DATA.__objc_const` | `0x978` | `0x9b8` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1020` | `0x1040` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x2b8` | `0x2a0` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x510` | `0x520` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x7e0` | `0x7d0` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x400` | `0x3f8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2b8` | `0x2b0` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0xbd` | `0xc3` | **`+0x6`** |
| `__TEXT.__swift5_capture` | `0xb0` | `0xb4` | **`+0x4`** |
| `__TEXT.__oslogstring` | `0x5f` | `0x5e` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-70.0.0.0.0
+73.0.0.0.2

-  Functions: 163
-  Symbols:   211
-  CStrings:  284
+  Functions: 161
+  Symbols:   210
+  CStrings:  290
Symbols:
+ _$s26ScreenTimeSettingsServices0abC0C11askToBrowse9webDomain11isSensitiveyAC03WebI0V_SbtYaKF
+ _$s26ScreenTimeSettingsServices0abC0C11askToBrowse9webDomain11isSensitiveyAC03WebI0V_SbtYaKFTu
+ _$s26ScreenTimeSettingsServices0abC0C9WebDomainV09highLevelF05titleAE10Foundation3URLV_SSSgtcfC
- _$s26ScreenTimeSettingsServices0abC0C11askToBrowse9webDomainyAC03WebI0V_tYaKF
- _$s26ScreenTimeSettingsServices0abC0C11askToBrowse9webDomainyAC03WebI0V_tYaKFTu
- _$s26ScreenTimeSettingsServices0abC0C9WebDomainV3url5titleAE10Foundation3URLV_SSSgtcfC
- _swift_release_x19
CStrings:
+ "@36@0:8@16B24@?28"
+ "_isSensitive"
+ "clearColor"
+ "configureWithURL:symbol:title:subtitle:displayURL:showBadge:shieldType:isSensitive:overridePolicy:iframe:"
+ "deviceApprovalViewControllerForURL:isSensitive:withCompletion:"
+ "remoteApprovalForURL:isSensitive:withCompletion:"
+ "setURL:isSensitive:"
+ "userRequestedDeviceApproval:isSensitive:"
+ "v28@0:8@\"NSURL\"16B24"
+ "v28@0:8@16B24"
+ "v36@0:8@\"NSURL\"16B24@?<v@?@\"NSError\">28"
+ "v84@0:8@\"NSURL\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48B56@\"NSString\"60B68@\"NSString\"72B80"
+ "v84@0:8@16@24@32@40@48B56@60B68@72B80"
- "@32@0:8@16@?24"
- "configureWithURL:symbol:title:subtitle:displayURL:showBadge:shieldType:overridePolicy:iframe:"
- "deviceApprovalViewControllerForURL:withCompletion:"
- "remoteApprovalForURL:withCompletion:"
- "userRequestedDeviceApproval"
- "v80@0:8@\"NSURL\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@\"NSString\"48B56@\"NSString\"60@\"NSString\"68B76"
- "v80@0:8@16@24@32@40@48B56@60@68B76"
```
