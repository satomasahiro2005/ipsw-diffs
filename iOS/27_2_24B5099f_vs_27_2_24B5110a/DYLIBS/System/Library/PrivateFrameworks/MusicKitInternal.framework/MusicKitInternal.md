## MusicKitInternal

> `/System/Library/PrivateFrameworks/MusicKitInternal.framework/MusicKitInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x927e98` | `0x929314` | **`+0x147c`** |
| `__TEXT.__oslogstring` | `0xe2c7` | `0xe3f7` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x3fcd0` | `0x3fd10` | **`+0x40`** |
| `__TEXT.__const` | `0x73044` | `0x73074` | **`+0x30`** |
| `__DATA.__data` | `0x13b80` | `0x13b98` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2a0c` | `0x2a24` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x9fc8` | `0x9fd8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2438` | `0x2448` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1a120` | `0x1a130` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x23f40` | `0x23f50` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6fe8` | `0x6ff0` | **`+0x8`** |

### Other Changes

```diff

-4026.200.27.0.0
+4026.210.2.0.0

-  Functions: 61547
-  Symbols:   12523
-  CStrings:  3151
+  Functions: 61562
+  Symbols:   12526
+  CStrings:  3154
Symbols:
+ -[MusicKit_SoftLinking_MPCPlaybackIntent setSiriAssetInfo:]
+ -[MusicKit_SoftLinking_MPCPlaybackIntent siriAssetInfo]
+ _symbolic ___________p 8MusicKit38UnderlyingLegacyModelObjectConvertibleP 0aB8Internal08PlayableA9ContainerP
CStrings:
+ "Attached %{public}ld bytes of Siri asset info for %{public}s."
+ "Expected at most one album needing an updated payload for playback, found %{public}ld. Attaching the payload for %{public}s only."
+ "Failed to serialize %{public}s as Siri asset info: %{public}@. Playing without it."
```
