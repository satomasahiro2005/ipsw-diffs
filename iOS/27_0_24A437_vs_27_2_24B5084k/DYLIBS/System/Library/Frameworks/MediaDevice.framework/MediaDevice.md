## MediaDevice

> `/System/Library/Frameworks/MediaDevice.framework/MediaDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31818` | `0x31ec0` | **`+0x6a8`** |
| `__TEXT.__oslogstring` | `0xf7b` | `0x100b` | **`+0x90`** |
| `__TEXT.__const` | `0x1242` | `0x1258` | **`+0x16`** |
| `__DATA.__data` | `0x5c8` | `0x5d8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x8f0` | `0x8f8` | **`+0x8`** |

### Other Changes

```diff

-360.75.1.2.0
+385.6.1.0.0

-  Functions: 812
+  Functions: 819

-  CStrings:  158
+  CStrings:  159
CStrings:
+ "MediaOutputDevice '%{private}s' declares realtimeVideoStreaming without realtimeAudioStreaming, which is not a supported combination."
```
