## AEBookPlugins

> `/private/var/staged_system_apps/Books.app/Frameworks/AEBookPlugins.framework/AEBookPlugins`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1332d8` | `0x132784` | **`-0xb54`** |
| `__DATA.__objc_data` | `0x5ce0` | `0x5ac0` | **`-0x220`** |
| `__TEXT.__cstring` | `0x92a7` | `0x9147` | **`-0x160`** |
| `__DATA.__objc_const` | `0x20420` | `0x202e0` | **`-0x140`** |
| `__TEXT.__objc_stubs` | `0x29440` | `0x29520` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0xad4` | `0xa0c` | **`-0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x60a` | `0x54a` | **`-0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x5f8` | `0x554` | **`-0xa4`** |
| `__DATA.__data` | `0x41a8` | `0x4108` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x37ef9` | `0x37f89` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x182f4` | `0x1834c` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x2690` | `0x2640` | **`-0x50`** |
| `__TEXT.__const` | `0x17f8` | `0x17a8` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0x2bed` | `0x2b9d` | **`-0x50`** |
| `__TEXT.__objc_methtype` | `0xa2ad` | `0xa2fd` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x702` | `0x6b8` | **`-0x4a`** |
| `__TEXT.__unwind_info` | `0x53b0` | `0x5368` | **`-0x48`** |
| `__DATA.__objc_selrefs` | `0xd6a0` | `0xd6d8` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x1360` | `0x1338` | **`-0x28`** |
| `__DATA_CONST.__const` | `0x4368` | `0x4390` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x9260` | `0x9280` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x143c` | `0x1454` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x168` | `0x180` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x808` | `0x7f8` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1b0` | `0x1a8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x48` | `0x40` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6655.0.0.0.0
+6713.0.0.0.0

-  Functions: 8423
-  Symbols:   2308
-  CStrings:  12174
+  Functions: 8415
+  Symbols:   2303
+  CStrings:  12169
Symbols:
- _CGRectGetCenter
- _OBJC_CLASS_$_AEMarkupBarButtonItem
- _OBJC_METACLASS_$_AEMarkupBarButtonItem
- _OBJC_METACLASS_$_UIBarButtonItem
- _swift_unknownObjectRelease_n
CStrings:
+ "@\"UIBarButtonItemGroup\""
+ "@\"UIScreen\""
+ "@\"UIWindowScene\""
+ "T@\"NSNumber\",&,N,V_lastKnownScreenBrightness"
+ "T@\"UIScreen\",W,N,V_observedScreen"
+ "T@\"UIWindowScene\",W,N,V_observedScene"
+ "_addReadingModeBottomToolbarItems:animated:"
+ "_lastKnownScreenBrightness"
+ "_observedScene"
+ "_observedScreen"
+ "_rightBarButtonItemGroup"
+ "_sampleScreenBrightnessForAnalytics"
+ "effectiveGeometry"
+ "interactionShouldReceiveTouchesInDescendantViews:"
+ "isInAlternativeBarLayout"
+ "lastKnownScreenBrightness"
+ "observeBrightnessChanges"
+ "observeSceneGeometryChanges"
+ "observedScene"
+ "observedScreen"
+ "screen"
+ "setBarButtonItems:"
+ "setHidesSharedBackground:"
+ "setLastKnownScreenBrightness:"
+ "setObservedScene:"
+ "setObservedScreen:"
+ "setToolbarItems:animated:"
+ "shareSelectedAnnotationsFromSourceItem:"
+ "stopObservingBrightnessChanges"
+ "stopObservingSceneGeometryChanges"
+ "tocViewController:shareAnnotations:sourceItem:"
+ "v40@0:8@\"BKDirectoryContent\"16@\"NSArray\"24@\"<UIPopoverPresentationControllerSourceItem>\"32"
- ":16@0:8"
- "AEBookPlugins/MarkupBarButtonItem.swift"
- "AEBookPlugins/MarkupButtonContainerView.swift"
- "AEMarkupBarButtonItem"
- "Accessibility string for the markup button being in an 'off' state."
- "Accessibility string for the markup button being in an 'on' state."
- "Accessibility string for the markup feature."
- "T:,N"
- "T@,N,W"
- "_TtC13AEBookPlugins25MarkupButtonContainerView"
- "_luminance"
- "_selected"
- "_setPrefersNoPlatter:"
- "_traitCollectionDidChangeWithSender:previousTraitCollection:"
- "buttonPadding"
- "closeButtonAction:"
- "compactButtonPadding"
- "compactImage"
- "enabled"
- "init(coder:) has not been implemented"
- "intrinsicHeight"
- "intrinsicWidthPadding"
- "luminanceThreshold"
- "regularButtonPadding"
- "regularImage"
- "selected"
- "setAttributedTitle:"
- "setCustomView:"
- "setDisableActions:"
- "setPinnedTrailingGroup:"
- "setToolbarItems:"
- "shareSelectedAnnotationsFromSourceView:"
- "supportsAlernativeBarLayout"
- "toggleView"
- "updateForMiniBarState:"
- "v24@0:8:16"
- "\x81"
```
