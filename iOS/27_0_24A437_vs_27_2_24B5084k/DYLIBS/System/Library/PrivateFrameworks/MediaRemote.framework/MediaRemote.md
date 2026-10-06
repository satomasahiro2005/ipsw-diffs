## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x317a30` | `0x317c84` | **`+0x254`** |
| `__TEXT.__cstring` | `0x2df00` | `0x2de64` | **`-0x9c`** |
| `__TEXT.__objc_methlist` | `0x2c818` | `0x2c888` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x47f48` | `0x47fa8` | **`+0x60`** |
| `__TEXT.__const` | `0x6b0` | `0x650` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0xeaed` | `0xeb44` | **`+0x57`** |
| `__AUTH_CONST.__cfstring` | `0x24a80` | `0x24a40` | **`-0x40`** |
| `__DATA_CONST.__const` | `0xbb58` | `0xbb98` | **`+0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0x4f8` | `0x528` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xf978` | `0xf9a0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x14d0` | `0x14d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbe18` | `0xbe20` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x33ec` | `0x33f0` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x6368` | `0x6364` | **`-0x4`** |

### Other Changes

```diff

-4026.110.4.0.0
+4026.200.11.0.0

-  Functions: 21030
-  Symbols:   30262
-  CStrings:  6776
+  Functions: 21037
+  Symbols:   30276
+  CStrings:  6775
Symbols:
+ +[MRCBProductInfo isWXDeviceWithModelID:]
+ -[MRAVConcreteOutputDevice supportsDiscoveredIsPlaying]
+ -[MRAVConcreteRoutingDiscoverySession detailsList]
+ -[MRAVDistantOutputDevice supportsDiscoveredIsPlaying]
+ -[MRAVEndpoint supportsDiscoveredIsPlaying]
+ -[MRAVOutputDevice isWXDevice]
+ -[MRAVOutputDevice supportsDiscoveredIsPlaying]
+ -[MRCompanionLinkClientEvent setStatusFlags:]
+ -[MRCompanionLinkClientEvent statusFlags]
+ GCC_except_table222
+ GCC_except_table252
+ GCC_except_table321
+ _MRAVVolumeClientEndpointVolumeCategoryDidChangeNotification
+ _MRRequestDetailsInitiatorCorianderLockScreen
+ _MRRequestDetailsInitiatorNowPlayingPlatter
+ _OBJC_IVAR_$_MRCompanionLinkClientEvent._statusFlags
+ _RPOptionStatusFlags
+ ___50-[MRAVConcreteRoutingDiscoverySession detailsList]_block_invoke
- GCC_except_table102
- GCC_except_table221
- GCC_except_table250
- GCC_except_table320
CStrings:
+ "-[MRAVOutputDevice supportsDiscoveredIsPlaying]"
+ "CorianderLockScreen"
+ "MRAVVolumeClientEndpointVolumeCategoryDidChangeNotification"
+ "NowPlayingPlatter"
+ "Update: %{public}@<%{public}@> localGroupID detected. Substituting picked localDevice "
- "MRAudioDataBlock.m"
- "MRDeviceInfo *MRMediaRemoteServiceCopyDeviceInfo(MRMediaRemoteServiceRef, MRPlayerPath *__strong)"
- "Trying to call CopyDeviceInfo from Daemon"
- "invalid buffer size for decoding voice input message (%lu > (%lu * %lu))"
- "iphone"
- "packet descriptions exceed maximum packet capacity (%lu > %lu)"
```
