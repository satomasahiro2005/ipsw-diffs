## ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/XPCServices/ACCHWComponentAuthService.xpc/ACCHWComponentAuthService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39b64` | `0x39d14` | **`+0x1b0`** |
| `__TEXT.__oslogstring` | `0x66e6` | `0x6768` | **`+0x82`** |
| `__DATA_CONST.__const` | `0x6a68` | `0x6aa8` | **`+0x40`** |
| `__DATA.__bss` | `0x130` | `0x140` | **`+0x10`** |
| `__TEXT.__const` | `0x1e213` | `0x1e223` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x828` | `0x830` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1219.40.5.0.0
+1219.40.7.0.0

-  Functions: 1228
-  Symbols:   2805
-  CStrings:  1262
+  Functions: 1234
+  Symbols:   2816
+  CStrings:  1264
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/TempContent/Objects/CoreAccessories.build/ACCHWComponentAuthService.build/Objects-normal/arm64e/acc_internal_settings.o
+ ___acc_internalSettings_isInternalBuild_block_invoke
+ _acc_internalSettings_boolForKey
+ _acc_internalSettings_integerForKey
+ _acc_internalSettings_isInternalBuild
+ acc_internalSettings_boolForKey
+ acc_internalSettings_integerForKey
+ acc_internalSettings_isInternalBuild
+ acc_internalSettings_isInternalBuild.isInternalBuild
+ acc_internalSettings_isInternalBuild.onceToken
+ acc_internal_settings.c
CStrings:
+ "acc_internalSettings: internal-only setting %{public}@ active"
+ "acc_internalSettings: internal-only setting %{public}@ active (%ld)"
```
