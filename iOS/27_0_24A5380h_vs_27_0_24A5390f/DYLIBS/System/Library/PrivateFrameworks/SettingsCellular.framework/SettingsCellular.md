## SettingsCellular

> `/System/Library/PrivateFrameworks/SettingsCellular.framework/SettingsCellular`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x1410` | `0x1638` | **`+0x228`** |
| `__TEXT.__text` | `0xa5d8` | `0xa700` | **`+0x128`** |
| `__AUTH.__objc_data` | `0xf0` | `0x190` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xe34` | `0xeac` | **`+0x78`** |
| `__DATA.__data` | `0x308` | `0x368` | **`+0x60`** |
| `__TEXT.__cstring` | `0x74c` | `0x76f` | **`+0x23`** |
| `__AUTH_CONST.__const` | `0x100` | `0x120` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x210` | `0x220` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xbb0` | `0xbc0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x320` | `0x328` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x64` | `0x68` | **`+0x4`** |

### Other Changes

```diff

-746.0.0.0.0
+750.0.0.0.0

-  Functions: 244
-  Symbols:   605
-  CStrings:  147
+  Functions: 250
+  Symbols:   634
+  CStrings:  149
Symbols:
+ +[SettingsCellularFeatureFlagManager sharedManager]
+ -[SettingsCellularFeatureFlagManager .cxx_destruct]
+ -[SettingsCellularFeatureFlagManager init]
+ -[SettingsCellularFeatureFlagManager isEnabled:]
+ -[SettingsCellularLiveFeatureFlagProvider isEnabled:]
+ _OBJC_CLASS_$_SettingsCellularFeatureFlagManager
+ _OBJC_CLASS_$_SettingsCellularLiveFeatureFlagProvider
+ _OBJC_IVAR_$_SettingsCellularFeatureFlagManager._liveProvider
+ _OBJC_METACLASS_$_SettingsCellularFeatureFlagManager
+ _OBJC_METACLASS_$_SettingsCellularLiveFeatureFlagProvider
+ __OBJC_$_CLASS_METHODS_SettingsCellularFeatureFlagManager
+ __OBJC_$_INSTANCE_METHODS_SettingsCellularFeatureFlagManager
+ __OBJC_$_INSTANCE_METHODS_SettingsCellularLiveFeatureFlagProvider
+ __OBJC_$_INSTANCE_VARIABLES_SettingsCellularFeatureFlagManager
+ __OBJC_$_PROP_LIST_SettingsCellularFeatureFlagManager
+ __OBJC_$_PROP_LIST_SettingsCellularLiveFeatureFlagProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SettingsCellularFeatureFlagProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SettingsCellularFeatureFlagProviding
+ __OBJC_$_PROTOCOL_REFS_SettingsCellularFeatureFlagProviding
+ __OBJC_CLASS_PROTOCOLS_$_SettingsCellularFeatureFlagManager
+ __OBJC_CLASS_PROTOCOLS_$_SettingsCellularLiveFeatureFlagProvider
+ __OBJC_CLASS_RO_$_SettingsCellularFeatureFlagManager
+ __OBJC_CLASS_RO_$_SettingsCellularLiveFeatureFlagProvider
+ __OBJC_LABEL_PROTOCOL_$_SettingsCellularFeatureFlagProviding
+ __OBJC_METACLASS_RO_$_SettingsCellularFeatureFlagManager
+ __OBJC_METACLASS_RO_$_SettingsCellularLiveFeatureFlagProvider
+ __OBJC_PROTOCOL_$_SettingsCellularFeatureFlagProviding
+ ___51+[SettingsCellularFeatureFlagManager sharedManager]_block_invoke
+ __os_feature_enabled_impl
CStrings:
+ "CarrierAppInSettings"
+ "CoreTelephony"
```
