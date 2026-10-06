## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48150` | `0x4834c` | **`+0x1fc`** |
| `__TEXT.__oslogstring` | `0x6a79` | `0x6b0e` | **`+0x95`** |
| `__DATA_CONST.__const` | `0x15f0` | `0x1638` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x4aa0` | `0x4ac0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3080` | `0x3090` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1240` | `0x1230` | **`-0x10`** |
| `__TEXT.__cstring` | `0x3792` | `0x3798` | **`+0x6`** |

### Other Changes

```diff

-625.0.0.0.0
+627.0.9.0.0

-  Functions: 2136
+  Functions: 2137

-  CStrings:  1298
+  CStrings:  1301
Symbols:
+ -[TVRCDevice findMyRemoteSupport]
+ -[TVRCDeviceState findMyRemoteSupport]
+ -[TVRCDeviceState setFindMyRemoteSupport:]
+ -[TVRCMatchPointDeviceImpl findMyRemoteSupport]
+ -[TVRCRPCompanionLinkClientWrapper _findMyRemoteSupportForDevice:]
+ -[TVRCRPCompanionLinkClientWrapper findMyRemoteSupport]
+ -[TVRCRapportDeviceImpl deviceUpdatedFindMyRemoteSupport:]
+ -[TVRCRapportDeviceImpl findMyRemoteSupport]
+ -[TVRCRapportDeviceImpl isDevicePaired]
+ -[TVRXDevice _setFindMyRemoteSupport:]
+ -[TVRXDevice device:didUpdateFindMyRemoteSupport:]
+ -[TVRXDevice findMyRemoteSupport]
+ _OBJC_IVAR_$_TVRCDeviceState._findMyRemoteSupport
- -[TVRCDevice supportsFindMyRemote]
- -[TVRCDeviceState setSupportsFindMyRemote:]
- -[TVRCDeviceState supportsFindMyRemote]
- -[TVRCMatchPointDeviceImpl supportsFindMyRemote]
- -[TVRCRPCompanionLinkClientWrapper _findMyRemoteSupportedForDevice:]
- -[TVRCRPCompanionLinkClientWrapper supportsFindMyRemote]
- -[TVRCRapportDeviceImpl deviceSupportsFindMyRemote:]
- -[TVRCRapportDeviceImpl isPaired]
- -[TVRCRapportDeviceImpl supportsFindMyRemote]
- -[TVRXDevice _setDeviceSupportsFindMyRemote:]
- -[TVRXDevice device:didUpdateFindMyRemoteSupported:]
- -[TVRXDevice supportsFindMyRemote]
- _OBJC_IVAR_$_TVRCDeviceState._supportsFindMyRemote
CStrings:
+ "<TVRXDevice %p> find my remote support: %@"
+ "Find my remote support level for %@: %@, device capability: %{bool}d, paired remote support: %{bool}d"
+ "Legacy"
+ "Updated Find my remote support to: %@"
+ "Updated find my remote support for %@ - %@"
+ "findMyRemoteSupport"
- "<TVRXDevice %p> supports find my remote: %s"
- "Updated supportsFindMyRemote: %d"
- "supportsFindMyRemote"
```
