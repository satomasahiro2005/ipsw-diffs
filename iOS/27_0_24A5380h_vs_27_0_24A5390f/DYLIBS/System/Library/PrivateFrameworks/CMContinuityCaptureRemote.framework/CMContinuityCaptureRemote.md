## CMContinuityCaptureRemote

> `/System/Library/PrivateFrameworks/CMContinuityCaptureRemote.framework/CMContinuityCaptureRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xafa64` | `0xaf9ec` | **`-0x78`** |
| `__AUTH_CONST.__objc_const` | `0xac50` | `0xac90` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x33ec` | `0x33b8` | **`-0x34`** |
| `__TEXT.__objc_methlist` | `0x5fa4` | `0x5fb4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x834` | `0x83c` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1f28` | `0x1f30` | **`+0x8`** |

### Other Changes

```diff

-758.0.0.122.2
+761.0.0.0.3

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

-  Symbols:   4609
+  Symbols:   4612
Symbols:
+ -[CMContinuityCaptureDServer _releaseShieldUIResources]
+ -[CMContinuityCaptureRemoteServer _releaseShieldUIResources]
+ GCC_except_table65
+ GCC_except_table99
+ _OBJC_IVAR_$_CMContinuityCaptureDServer._shieldUIObserversRegistered
+ _OBJC_IVAR_$_CMContinuityCaptureRemoteServer._shieldUIObserversRegistered
+ ___55-[CMContinuityCaptureDServer _releaseShieldUIResources]_block_invoke
+ ___60-[CMContinuityCaptureRemoteServer _releaseShieldUIResources]_block_invoke
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private_$_CMContinuityCaptureRemote
- -[CMContinuityCaptureDServer teardownShieldUI]
- GCC_except_table100
- GCC_except_table89
- GCC_except_table93
- ___46-[CMContinuityCaptureDServer teardownShieldUI]_block_invoke
- ___47-[CMContinuityCaptureDServer _teardownShieldUI]_block_invoke
- ___52-[CMContinuityCaptureRemoteServer _teardownShieldUI]_block_invoke
```
