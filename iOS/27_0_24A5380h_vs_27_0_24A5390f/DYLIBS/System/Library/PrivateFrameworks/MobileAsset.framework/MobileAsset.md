## MobileAsset

> `/System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xb965` | `0xb975` | **`+0x10`** |
| `__DATA.__bss` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x1f0` | `0x1e8` | **`-0x8`** |
| `__TEXT.__text` | `0x8c4f8` | `0x8c500` | **`+0x8`** |

### Other Changes

```diff

-2215.0.13.0.0
+2215.0.16.0.0
Symbols:
+ -[MAAutoAssetSet _readLockedSetStatusFromSharedLockFile:fileDescriptor:error:]
+ ___78-[MAAutoAssetSet _readLockedSetStatusFromSharedLockFile:fileDescriptor:error:]_block_invoke
+ __readLockedSetStatusFromSharedLockFile:fileDescriptor:error:.readSetStatusSetupDispatchOnce
+ __readLockedSetStatusFromSharedLockFile:fileDescriptor:error:.recordArray
+ _fcntl
- -[MAAutoAssetSet _readLockedSetStatusFromSharedLockFile:error:]
- ___63-[MAAutoAssetSet _readLockedSetStatusFromSharedLockFile:error:]_block_invoke
- __readLockedSetStatusFromSharedLockFile:error:.readSetStatusSetupDispatchOnce
- __readLockedSetStatusFromSharedLockFile:error:.recordArray
- _realpath$DARWIN_EXTSN
CStrings:
+ "[ERROR] %{public}s: Extracted object for key %{public}@ is invalid/not a dictionary"
+ "[ERROR] %{public}s: Unable to extract plist object for key %{public}@ from dict"
- "%{public}s: Extracted object for key %{public}@ is invalid/not a dictionary"
- "%{public}s: Unable to extract plist object for key %{public}@ from dict"
```
