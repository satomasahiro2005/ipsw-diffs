## CarPlay

> `/System/Library/Frameworks/CarPlay.framework/CarPlay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x20a0` | `0x48` | **`-0x2058`** |
| `__DATA_DIRTY.__objc_data` | `0x6e0` | `0x2738` | **`+0x2058`** |
| `__TEXT.__text` | `0x6ed40` | `0x6f144` | **`+0x404`** |
| `__DATA_DIRTY.__data` | `—` | `0x248` | **`+0x248`** |
| `__AUTH.__data` | `0x230` | `—` | **`-0x230`** |
| `__TEXT.__objc_methlist` | `0x99d0` | `0x9a40` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x21490` | `0x214e0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x4310` | `0x4350` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1ef0` | `0x1f18` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x5620` | `0x5640` | **`+0x20`** |
| `__DATA.__data` | `0x2070` | `0x2050` | **`-0x20`** |
| `__TEXT.__cstring` | `0x5996` | `0x59b6` | **`+0x20`** |
| `__DATA.__common` | `0x28` | `0x18` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1f68` | `0x1f78` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa30` | `0xa34` | **`+0x4`** |

### Other Changes

```diff

-534.3.0.0.0
+537.3.0.0.0

-  Functions: 3364
-  Symbols:   6310
-  CStrings:  1089
+  Functions: 3374
+  Symbols:   6322
+  CStrings:  1090
Symbols:
+ -[CPListImageRowItem _registerThumbnailUpdaterForElements:]
+ -[CPListSection replaceItem:]
+ -[CPListTemplate setUseAlternativeCollectionView:]
+ -[CPListTemplate useAlternativeCollectionView]
+ -[CPMapPanelItem _allowedPanelItemObjectClasses]
+ -[CPPanelItem _allowedPanelItemObjectClasses]
+ -[CPPanelItem _initWithObject:interactionAllowed:]
+ -[CPPanelItem initWithGridButtons:]
+ -[CPPanelItem initWithListItem:]
+ -[CPPanelItem interactionAllowed]
+ -[CPPanelItem panelItemObject]
+ -[CPPanelItem setInteractionAllowed:]
+ -[CPPanelItem setPanelItemObject:]
+ _OBJC_IVAR_$_CPListTemplate._useAlternativeCollectionView
+ _OBJC_IVAR_$_CPPanelItem._interactionAllowed
+ _OBJC_IVAR_$_CPPanelItem._panelItemObject
+ ___29-[CPListSection replaceItem:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48s_e37_v32?0"<CPListTemplateItem>"8Q16^B24ls32l8s40l8s48l8
- -[CPMapPanelItem initWithGridButtons:]
- -[CPMapPanelItem initWithListItem:]
- -[CPMapPanelItem interactionAllowed]
- -[CPMapPanelItem setInteractionAllowed:]
- _OBJC_IVAR_$_CPMapPanelItem._interactionAllowed
- _OBJC_IVAR_$_CPMapPanelItem._mapTemplateItemObject
CStrings:
+ "kCPListTemplateUseAlternativeCollectionViewKey"
+ "kCPPanelItemInteractionAllowedKey"
+ "kCPPanelItemObjectKey"
- "kCPMapPanelItemInteractionAllowedKey"
- "kCPMapPanelItemWrappedObjectKey"
```
