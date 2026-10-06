## CarPlayWallpaper

> `/Applications/CarPlayWallpaper.app/CarPlayWallpaper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9064` | `0x9b34` | **`+0xad0`** |
| `__TEXT.__oslogstring` | `0x45c` | `0x6ac` | **`+0x250`** |
| `__DATA_CONST.__cfstring` | `0x160` | `0x2e0` | **`+0x180`** |
| `__TEXT.__objc_stubs` | `0x11c0` | `0x1280` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x1f12` | `0x1fb2` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x218` | `0x298` | **`+0x80`** |
| `__DATA.__objc_const` | `0x15b0` | `0x15f0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x7b8` | `0x7e0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x508` | `0x530` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x310` | `0x338` | **`+0x28`** |
| `__TEXT.__const` | `0x1f4` | `0x214` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xa0c` | `0xa24` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xa70` | `0xa80` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x44` | `0x4c` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x548` | `0x550` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-581.7.2.0.0
+591.2.0.0.0

-  Functions: 250
-  Symbols:   271
-  CStrings:  480
+  Functions: 262
+  Symbols:   272
+  CStrings:  510
Symbols:
+ _CACurrentMediaTime
CStrings:
+ "!("
+ "%@ -> %@"
+ "%@:%@"
+ "(nil)"
+ "(none)"
+ "<no-wallpaper>"
+ "HIT"
+ "MISS"
+ "NOT-CACHEABLE"
+ "[Appearance-Flip] %{public}@ ABORT provider-not-ready"
+ "[Appearance-Flip] %{public}@ BEGIN reason=%{public}@ %{public}@"
+ "[Appearance-Flip] %{public}@ READY total %.1fms"
+ "[Appearance-Flip] %{public}@ SKIP resolve, view swaps state itself"
+ "[Appearance-Flip] %{public}@ step=cacheLookup %{public}@ key=%{public}@ %.1fms"
+ "[Appearance-Flip] %{public}@ step=firstFrame %.1fms (commit->frame) total %.1fms since flip"
+ "[Appearance-Flip] %{public}@ step=generateCacheImage %.1fms"
+ "[Appearance-Flip] %{public}@ step=resolve %.1fms"
+ "[Appearance-Flip] %{public}@ step=saveCacheImage %.1fms key=%{public}@"
+ "_beginAppearanceFlip:detail:"
+ "_flipStartTime"
+ "_logTag"
+ "_uncachedViewHandlesAppearance"
+ "d"
+ "displayID"
+ "layoutID"
+ "provider-ready"
+ "trait-change"
+ "unspecified"
+ "viewHandlesAppearanceChanges"
+ "wallpaper-change"
```
