## MediaPlayer

> `/System/Library/Frameworks/MediaPlayer.framework/MediaPlayer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38df44` | `0x38df00` | **`-0x44`** |
| `__DATA_CONST.__got` | `0x30d0` | `0x30c8` | **`-0x8`** |

### Other Changes

```diff

-4026.110.1.0.0
+4026.110.2.0.0

-  Symbols:   32446
+  Symbols:   32445
Symbols:
+ __MRMediaRemoteNowPlayingMediaTypeForMPNowPlayingMediaType
+ _kMRMediaRemoteMediaTypeAudioBook
+ _kMRMediaRemoteMediaTypeITunesRadio
+ _kMRMediaRemoteMediaTypeITunesU
+ _kMRMediaRemoteMediaTypeMusic
+ _kMRMediaRemoteMediaTypePodcast
+ _kMRMediaRemoteNowPlayingInfoMediaType
+ _kMRMediaRemoteNowPlayingInfoTypeAudio
+ _kMRMediaRemoteNowPlayingInfoTypeVideo
- _MRNowPlayingInfoContentTypeBook
- _MRNowPlayingInfoContentTypeGeneric
- _MRNowPlayingInfoContentTypeMusic
- _MRNowPlayingInfoContentTypePodcast
- _MRNowPlayingInfoContentTypeRadio
- _MRNowPlayingInfoMediaTypeAudio
- _MRNowPlayingInfoMediaTypeVideo
- __MRMediaRemoteStrictMediaTypeForMPNowPlayingMediaType
- _kMRMediaRemoteNowPlayingInfoContentType
- _kMRMediaRemoteNowPlayingInfoStrictMediaType
Functions:
~ ____MPNowPlayingInfoPropertyToMRMediaRemoteNowPlayingInfoPropertyMapping_block_invoke : 2092 -> 2072
~ __MRMediaRemoteStrictMediaTypeForMPNowPlayingMediaType -> __MRMediaRemoteNowPlayingMediaTypeForMPNowPlayingMediaType : 100 -> 52
```
