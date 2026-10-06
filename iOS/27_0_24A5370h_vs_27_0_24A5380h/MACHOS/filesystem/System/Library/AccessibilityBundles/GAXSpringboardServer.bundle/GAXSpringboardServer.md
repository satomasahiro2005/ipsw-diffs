## GAXSpringboardServer

> `/System/Library/AccessibilityBundles/GAXSpringboardServer.bundle/GAXSpringboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1549c` | `0x15800` | **`+0x364`** |
| `__TEXT.__oslogstring` | `0x18de` | `0x19d7` | **`+0xf9`** |
| `__DATA_CONST.__const` | `0x1138` | `0x1188` | **`+0x50`** |
| `__DATA.__objc_const` | `0x3db8` | `0x3df8` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x5855` | `0x5885` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x4b80` | `0x4ba0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x40c` | `0x42c` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2e60` | `0x2e40` | **`-0x20`** |
| `__TEXT.__cstring` | `0x4f96` | `0x4fb1` | **`+0x1b`** |
| `__TEXT.__auth_stubs` | `0x6b0` | `0x6c0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x54` | `0x5c` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x368` | `0x370` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__const` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6c0` | `0x6c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-1057.0.0.0.0
+1059.0.0.0.0

-  Functions: 540
-  Symbols:   545
-  CStrings:  1569
+  Functions: 542
+  Symbols:   546
+  CStrings:  1575
Symbols:
+ _objc_retain_x27
CStrings:
+ "(nil)"
+ "B="
+ "GAXVolumeAccessQueue"
+ "_gaxVolumeAccessQueue"
+ "_handleUpdateHostedApplicationState: _windowsToHost count=%lu targetScene=%{public}@"
+ "_handleUpdateHostedApplicationState: app=%{public}@ scaleFactor=%.3f center={%.1f,%.1f} duration=%.2f"
+ "_observingEffectiveVolume"
+ "_updateStateOfHostedApplicationWithIdentifier: targetScene is nil (windowsToHost count=%lu), hosted app preview will not be built"
- "A-"
- "Guided Access allowing DismissCoverSheet capability for profile SAM"
```
