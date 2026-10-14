## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x318190` | `0x318b64` | **`+0x9d4`** |
| `__AUTH_CONST.__cfstring` | `0x24b40` | `0x24c60` | **`+0x120`** |
| `__TEXT.__cstring` | `0x2deda` | `0x2df91` | **`+0xb7`** |
| `__TEXT.__const` | `0x650` | `0x700` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x48050` | `0x480b0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xbbe0` | `0xbc18` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x2c8c8` | `0x2c900` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0xf9d0` | `0xfa00` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x63b4` | `0x63d8` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x14d8` | `0x14e8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x33fc` | `0x3404` | **`+0x8`** |

### Other Changes

```diff

-4026.200.23.0.0
+4026.210.2.0.0

-  Functions: 21045
-  Symbols:   30285
-  CStrings:  6784
+  Functions: 21052
+  Symbols:   30299
+  CStrings:  6793
Symbols:
+ -[MRGroupComposition addHomeAccessoryWithModelIdentifier:]
+ -[MRGroupComposition homeAccessoryCount]
+ -[MRGroupComposition setHomeAccessoryCount:]
+ -[MRGroupComposition setWalledHomeAccessoryCount:]
+ -[MRGroupComposition walledHomeAccessoryCount]
+ _AVOutputContextPredictedOutputDevicesDidChangeNotification
+ _MRAVOutputDeviceB525ModelID
+ _MRAVOutputDeviceB525ModelIDPrefix
+ _MRAVOutputDeviceJ490ModelID
+ _MRAVOutputDeviceJ491ModelID
+ _OBJC_CLASS_$_AVOutputContextPredictedDevicesOptions
+ _OBJC_IVAR_$_MRGroupComposition._homeAccessoryCount
+ _OBJC_IVAR_$_MRGroupComposition._walledHomeAccessoryCount
+ __MRDeviceClassFromMGDeviceClass
+ ___block_descriptor_184_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r160r168r176r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24lr32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8r104l8r112l8r120l8r128l8r136l8r144l8r152l8r160l8r168l8r176l8
- ___block_descriptor_176_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r160r168r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24lr32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8r104l8r112l8r120l8r128l8r136l8r144l8r152l8r160l8r168l8
CStrings:
+ "AudioAccessory11,"
+ "AudioAccessory11,1"
+ "GROUPSESSION_ROUTE_HOMEACCESSORY"
+ "HomeAccessory"
+ "HomeAccessory17,1"
+ "HomeAccessory17,2"
+ "Localizable-J490"
+ "OB"
+ "homeAccessory: %lu;"
+ "walledHomeAccessory: %lu;"
- "OA"
```
