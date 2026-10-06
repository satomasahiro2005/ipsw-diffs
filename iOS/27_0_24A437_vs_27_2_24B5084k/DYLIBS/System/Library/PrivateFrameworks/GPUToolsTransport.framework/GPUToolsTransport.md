## GPUToolsTransport

> `/System/Library/PrivateFrameworks/GPUToolsTransport.framework/GPUToolsTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58540` | `0x58984` | **`+0x444`** |
| `__AUTH_CONST.__objc_const` | `0x15198` | `0x15208` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x1048` | `0x1098` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x962c` | `0x966c` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x12fd` | `0x132e` | **`+0x31`** |
| `__DATA_CONST.__objc_selrefs` | `0x2fb0` | `0x2fd8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x4c60` | `0x4c80` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x16a8` | `0x16c8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4767` | `0x4784` | **`+0x1d`** |
| `__DATA.__objc_ivar` | `0xb80` | `0xb88` | **`+0x8`** |

### Other Changes

```diff

-2027.0.37.0.0
+2027.0.44.0.0

-  Functions: 2960
-  Symbols:   6632
-  CStrings:  814
+  Functions: 2969
+  Symbols:   6646
+  CStrings:  816
Symbols:
+ -[GTServiceProperties accessLevel]
+ -[GTServiceProperties setAccessLevel:]
+ -[GTServiceProvider accessLevelForPort:]
+ -[GTServiceProviderObserver originatorUntrusted]
+ -[GTServiceProviderObserver setOriginatorUntrusted:]
+ _MessageOriginatorIsUntrusted
+ _OBJC_IVAR_$_GTServiceProperties._accessLevel
+ _OBJC_IVAR_$_GTServiceProviderObserver._originatorUntrusted
+ __OBJC_$_INSTANCE_VARIABLES_GTServiceProviderObserver
+ __OBJC_$_PROP_LIST_GTServiceProviderObserver
+ ___block_descriptor_104_8_32s40s48s56s64s72s80bs88r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8r88l8s72l8s80l8
+ ___block_descriptor_49_8_32s40s_e15_v16?0"NSURL"8ls32l8s40l8
+ ___block_descriptor_49_8_32s40s_e27_v24?0"NSURL"8"NSError"16ls32l8s40l8
+ _hideDeviceUDIDInURLIfUntrusted
+ _servicesVisibleToOriginator
- ___block_descriptor_96_8_32s40s48s56s64s72s80bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
CStrings:
+ "<%@: protocolName=%@ protocolMethods=%@ servicePort=%llu platform=%u deviceUDID=%@ version=%llu accessLevel=%llu>"
+ "accessLevel"
+ "failed to issue sandbox extension for %{public}@"
- "<%@: protocolName=%@ protocolMethods=%@ servicePort=%llu platform=%u deviceUDID=%@ version=%llu>"
```
