## RemoteManagementModel

> `/System/Library/PrivateFrameworks/RemoteManagementModel.framework/RemoteManagementModel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_arrayobj` | `0x4fb0` | `0x4e00` | **`-0x1b0`** |
| `__DATA_CONST.__objc_arraydata` | `0x32f0` | `0x3220` | **`-0xd0`** |
| `__TEXT.__text` | `0x56ef4` | `0x56f9c` | **`+0xa8`** |
| `__AUTH_CONST.__objc_intobj` | `0x2a60` | `0x29d0` | **`-0x90`** |
| `__AUTH_CONST.__objc_const` | `0xf068` | `0xf008` | **`-0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x33e0` | `0x3390` | **`-0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2298` | `0x22b8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4b85` | `0x4b75` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x880` | `0x878` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x610` | `0x608` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x540` | `0x538` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1488` | `0x1480` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x8a4` | `0x8a8` | **`+0x4`** |

### Other Changes

```diff

-624.0.10.0.0
+624.2.3.0.0

-  Functions: 2729
-  Symbols:   5042
-  CStrings:  999
+  Functions: 2730
+  Symbols:   5037
+  CStrings:  998
Symbols:
+ -[RMModelConfigurationSchemaDynamicSetting defaultValue]
+ -[RMModelConfigurationSchemaDynamicSetting initWithDynamicSetting:keyPath:valueType:invertBoolean:defaultValue:managedSettingScope:supportedOSOverride:parentSchema:]
+ -[RMModelPayloadBase loadArrayFromDictionary:usingKey:forKeyPath:transform:isRequired:defaultValue:error:]
+ -[RMModelPayloadBase loadData:withType:]
+ -[RMModelPayloadBase serializeData:withType:]
+ _OBJC_IVAR_$_RMModelConfigurationSchemaDynamicSetting._defaultValue
- +[RMModelStatusManagementPushToken statusItemType]
- +[RMModelStatusManagementPushToken supportedOS]
- -[RMModelConfigurationSchemaDynamicSetting initWithDynamicSetting:keyPath:valueType:invertBoolean:managedSettingScope:supportedOSOverride:parentSchema:]
- -[RMModelStatusManagementPushToken isArrayValue]
- _OBJC_CLASS_$_RMModelStatusManagementPushToken
- _OBJC_METACLASS_$_RMModelStatusManagementPushToken
- _RMModelStatusItemManagementPushToken
- __OBJC_$_CLASS_METHODS_RMModelStatusManagementPushToken
- __OBJC_$_INSTANCE_METHODS_RMModelStatusManagementPushToken
- __OBJC_CLASS_RO_$_RMModelStatusManagementPushToken
- __OBJC_METACLASS_RO_$_RMModelStatusManagementPushToken
CStrings:
+ "default"
- "a"
- "management.push-token"
```
