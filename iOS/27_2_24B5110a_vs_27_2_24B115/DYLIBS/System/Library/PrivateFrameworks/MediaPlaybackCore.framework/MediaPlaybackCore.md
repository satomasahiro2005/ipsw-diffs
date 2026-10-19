## MediaPlaybackCore

> `/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/MediaPlaybackCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4aec08` | `0x4aed6c` | **`+0x164`** |
| `__AUTH_CONST.__cfstring` | `0x1ee00` | `0x1ede0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x3488` | `0x34a0` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x290` | `0x288` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xcc10` | `0xcc18` | **`+0x8`** |
| `__TEXT.__cstring` | `0x26068` | `0x26063` | **`-0x5`** |

### Other Changes

```diff

-  Symbols:   18715
-  CStrings:  8300
+  Symbols:   18718
+  CStrings:  8299
Symbols:
+ _kMXSessionProperty_HostProcessAttribution
+ _kMXSession_HostProcessAttributionKey_AuditToken
+ _kMXSession_HostProcessAttributionKey_BundleID
Functions:
~ -[_MPCPlaybackEnginePlayer updateAudioSession] : 324 -> 680
CStrings:
- "SEED"
```
