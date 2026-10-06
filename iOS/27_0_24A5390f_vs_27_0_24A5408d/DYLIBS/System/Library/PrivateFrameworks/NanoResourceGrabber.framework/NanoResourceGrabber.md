## NanoResourceGrabber

> `/System/Library/PrivateFrameworks/NanoResourceGrabber.framework/NanoResourceGrabber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c48` | `0x3de8` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x79d` | `0x8b7` | **`+0x11a`** |
| `__AUTH_CONST.__objc_intobj` | `0x348` | `0x390` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x340` | `0x380` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0xc0` | `0x100` | **`+0x40`** |
| `__DATA.__bss` | `0x10` | `0x30` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__const` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b8` | `0x3a8` | **`-0x10`** |
| `__TEXT.__cstring` | `0x3fe` | `0x40a` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1a0` | **`+0x8`** |

### Other Changes

```diff

-117.0.0.0.0
+118.0.0.0.0

-  Functions: 105
-  Symbols:   237
-  CStrings:  75
+  Functions: 109
+  Symbols:   240
+  CStrings:  81
Symbols:
+ +[NanoResourceGrabber liIconVariantsSyncedToPhone]
+ +[NanoResourceGrabber liIconVariantsSyncedToWatch]
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_NSSet
+ ___50+[NanoResourceGrabber liIconVariantsSyncedToPhone]_block_invoke
+ ___50+[NanoResourceGrabber liIconVariantsSyncedToWatch]_block_invoke
+ ___block_descriptor_68_e8_32s40s48bs56w_e20_v20?0"UIImage"8B16ls32l8s48l8s40l8w56l8
+ _liIconVariantsSyncedToPhone.onceToken
+ _liIconVariantsSyncedToPhone.variants
+ _liIconVariantsSyncedToWatch.onceToken
+ _liIconVariantsSyncedToWatch.variants
- +[NanoResourceGrabber liIconVariants]
- +[NanoResourceGrabber nrgIconVariants]
- _OBJC_CLASS_$_NSMutableArray
- ___99-[NanoResourceGrabber getCachedIconForBundleID:iconVariant:outIconImage:queue:updateBlock:timeout:]_block_invoke_2
- ___99-[NanoResourceGrabber getCachedIconForBundleID:iconVariant:outIconImage:queue:updateBlock:timeout:]_block_invoke_3
- ___block_descriptor_68_e8_32s40s48bs56w_e20_v20?0"UIImage"8B16ls48l8s32l8w56l8s40l8
- _objc_enumerationMutation
- _objc_release_x25
CStrings:
+ "getCachedIconForBundleID: caching icon for %{public}@ variant %ld"
+ "getCachedIconForBundleID: delivering icon for %{public}@ variant %ld (image %@, cache %d)"
+ "invalidatePairedDevice: clearing cache for pairedDeviceStorePath=%@"
+ "nil"
+ "present"
+ "setIcon: cached icon for %@ variant %ld (%lu bytes) at %@"
```
