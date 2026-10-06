## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/GameCenterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x177630` | `0x177e20` | **`+0x7f0`** |
| `__TEXT.__oslogstring` | `0xdf4b` | `0xe0eb` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x19190` | `0x192b0` | **`+0x120`** |
| `__DATA_DIRTY.__bss` | `0xe20` | `0xf30` | **`+0x110`** |
| `__DATA.__bss` | `0x82f0` | `0x81f0` | **`-0x100`** |
| `__TEXT.__eh_frame` | `0x5968` | `0x59f0` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x6928` | `0x6978` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x11640` | `0x11680` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x61d8` | `0x6218` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x24cd8` | `0x24d08` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x12614` | `0x1263c` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x6d28` | `0x6d48` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8588` | `0x85a0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x12dc` | `0x12f4` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x748` | `0x758` | **`+0x10`** |
| `__DATA.__data` | `0x3a60` | `0x3a58` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1120` | `0x1118` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xfd4` | `0xfd8` | **`+0x4`** |

### Other Changes

```diff

-821.1.8.0.0
+821.1.16.0.0

-  Functions: 11343
-  Symbols:   12465
-  CStrings:  4213
+  Functions: 11358
+  Symbols:   12478
+  CStrings:  4222
Symbols:
+ -[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]
+ -[GKMatch pendingPlayerIdentityResolutionGroup]
+ -[GKMatch setPendingPlayerIdentityResolutionGroup:]
+ GCC_except_table160
+ GCC_except_table167
+ GCC_except_table173
+ GCC_except_table174
+ GCC_except_table175
+ GCC_except_table179
+ GCC_except_table181
+ GCC_except_table188
+ _GKOverlayBundleIDs
+ _GKOverlayBundleIDs.onceToken
+ _GKOverlayBundleIDs.sOverlayBundleIDs
+ _OBJC_IVAR_$_GKMatch._pendingPlayerIdentityResolutionGroup
+ ___58-[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]_block_invoke
+ ___58-[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]_block_invoke_2
+ ___GKOverlayBundleIDs_block_invoke
+ ___block_descriptor_48_e8_32bs40r_e5_v8?0lr40l8s32l8
+ _kUnshippedOverlayBundleIDs
- GCC_except_table164
- GCC_except_table168
- GCC_except_table170
- GCC_except_table172
- GCC_except_table176
- GCC_except_table178
- GCC_except_table185
CStrings:
+ "%@ (completion != ((void*)0))\n[%s (%s:%d)]"
+ "-[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]"
+ "GKLocalPlayer.setInternal: nil write, substituting unauthenticated sentinel as this                     violates a class invariant. Stack trace:%@"
+ "Y29tLmFwcGxlLkdhbWVMYXllclVJ"
+ "Y29tLmFwcGxlLkdhbWVMYXllclVJLlNvbW1lbGllcg=="
+ "Y29tLmFwcGxlLkdhbWVPdmVybGF5VUkuR2FtZUNlbnRlckV4dGVuc2lvbg=="
+ "com.apple.gamecenter.match.pendingplayeridentityresolution"
+ "handleUnresolvedConnectedPlayersWithCompletion: timed out after %.1fs waiting for player identity resolution, proceeding with a possibly-incomplete roster"
+ "handleUnresolvedConnectedPlayersWithCompletion: waiting up to %.1fs for any in-flight player identity resolution"
```
