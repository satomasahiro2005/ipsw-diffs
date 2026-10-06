## GAXSpringboardServer

> `/System/Library/AccessibilityBundles/GAXSpringboardServer.bundle/GAXSpringboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x151ec` | `0x1549c` | **`+0x2b0`** |
| `__DATA_CONST.__cfstring` | `0x4a80` | `0x4b80` | **`+0x100`** |
| `__TEXT.__cstring` | `0x4ef0` | `0x4f96` | **`+0xa6`** |
| `__TEXT.__objc_methtype` | `0xf26` | `0xf7a` | **`+0x54`** |
| `__DATA.__objc_const` | `0x3df0` | `0x3db8` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0x18b0` | `0x18de` | **`+0x2e`** |
| `__TEXT.__auth_stubs` | `0x6c0` | `0x6b0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1edc` | `0x1eec` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6b0` | `0x6c0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x5862` | `0x5855` | **`-0xd`** |
| `__TEXT.__gcc_except_tab` | `0x400` | `0x40c` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x1490` | `0x1498` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x370` | `0x368` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x1130` | `0x1138` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x58` | `0x54` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1054.0.0.0.0
+1057.0.0.0.0

-  Functions: 538
+  Functions: 540

-  CStrings:  1559
+  CStrings:  1569
Symbols:
+ _GAXUIMessageKeyDisplayIdentifier
- _objc_retain_x27
CStrings:
+ "B40@0:8@\"_AXSpringBoardServerInstance\"16@\"NSString\"24@\"NSString\"32"
+ "B40@0:8@16@24@32"
+ "CategoryChange"
+ "Refreshed cached volume for category %@ to %f"
+ "RouteChange"
+ "SBHIconImageCache"
+ "_refreshCachedActiveCategoryVolume"
+ "appSwitcherHeaderIconImageCache"
+ "display identifier"
+ "notificationIconImageCache"
+ "purgeAllCachedImages"
+ "serverInstance:performArrangementSplitWithLeftBundleIdentifier:rightBundleIdentifier:"
+ "tableUIIconImageCache"
- "TB,N,S_gaxSetShouldSuppressBottomGrabber:,V__gaxShouldSuppressBottomGrabber"
- "__gaxShouldSuppressBottomGrabber"
- "sharedAVSystemController"
```
