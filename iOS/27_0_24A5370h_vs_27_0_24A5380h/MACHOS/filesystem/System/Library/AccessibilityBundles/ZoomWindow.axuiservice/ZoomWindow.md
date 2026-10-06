## ZoomWindow

> `/System/Library/AccessibilityBundles/ZoomWindow.axuiservice/ZoomWindow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b2c4` | `0x69dc4` | **`-0x1500`** |
| `__TEXT.__objc_stubs` | `0xb960` | `0xbaa0` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x1100b` | `0x1112b` | **`+0x120`** |
| `__TEXT.__cstring` | `0x25ee` | `0x2580` | **`-0x6e`** |
| `__TEXT.__const` | `0x1fa8` | `0x1f50` | **`-0x58`** |
| `__DATA.__objc_selrefs` | `0x37a0` | `0x37f0` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x682` | `0x632` | **`-0x50`** |
| `__TEXT.__objc_methlist` | `0x4cb0` | `0x4cf0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x404` | `0x437` | **`+0x33`** |
| `__DATA_CONST.__got` | `0x918` | `0x948` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x17a8` | `0x17d0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x2cb2` | `0x2cd2` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x3a15` | `0x3a2e` | **`+0x19`** |
| `__TEXT.__swift5_fieldmd` | `0x604` | `0x5ec` | **`-0x18`** |
| `__DATA.__bss` | `0xf40` | `0xf30` | **`-0x10`** |
| `__DATA.__data` | `0x1ad0` | `0x1ac0` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x2210` | `0x2220` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1a18` | `0x1a08` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x690` | `0x698` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1118` | `0x1120` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x630` | `0x628` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x23c` | `0x240` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-902.0.0.0.0
+904.0.0.0.0

-  Functions: 2528
-  Symbols:   4936
-  CStrings:  3230
+  Functions: 2524
+  Symbols:   4959
+  CStrings:  3243
Symbols:
+ -[ZWRootViewController _resolvedDisplayIDForScreen:]
+ -[ZWUIServer _defaultDisplayController]
+ -[ZWUIServer _hideZoomWindowNow]
+ -[ZWUIServer addScene:isExternal:]
+ -[ZWUIServer controllerForDisplayID:]
+ -[ZWUIServer displayKeyForScene:]
+ -[ZWUIServer reconcileDisplays]
+ GCC_except_table1136
+ GCC_except_table1183
+ GCC_except_table1227
+ GCC_except_table1254
+ GCC_except_table1256
+ GCC_except_table1351
+ GCC_except_table1520
+ GCC_except_table664
+ GCC_except_table770
+ GCC_except_table806
+ OBJC_IVAR_$_ZWUIServer._didRequestScenes
+ OBJC_IVAR_$_ZWUIServer._displayKeyByScene
+ OBJC_IVAR_$_ZWUIServer._zoomWindowShouldBeVisible
+ _OBJC_CLASS_$_AXUIDaemonApplication
+ _OBJC_CLASS_$_NSMapTable
+ ___26-[ZWUIServer removeScene:]_block_invoke
+ ___31-[ZWUIServer reconcileDisplays]_block_invoke
+ ___31-[ZWUIServer reconcileDisplays]_block_invoke_2
+ ___block_descriptor_68_e8_32s_e5_v8?0ls32l8
+ __os_log_error_impl
+ __swift_closure_destructor.83Tm
+ _objc_msgSend$_defaultDisplayController
+ _objc_msgSend$_hideZoomWindowNow
+ _objc_msgSend$_isEmbeddedScreen
+ _objc_msgSend$_resolvedDisplayIDForScreen:
+ _objc_msgSend$activationState
+ _objc_msgSend$addScene:isExternal:
+ _objc_msgSend$contentViewControllersWithUserInteractionEnabled:forService:
+ _objc_msgSend$controllerForDisplayID:
+ _objc_msgSend$displayKeyForScene:
+ _objc_msgSend$reconcileDisplays
+ _objc_msgSend$requestScenesForService:atPreferredSceneLevel:forSceneClientIdentifier:
+ _objc_msgSend$usesScenes
+ _objc_msgSend$weakToStrongObjectsMapTable
+ _symbolic _____Iegg_ 10ZoomWindow0A13MenuViewModelC
+ _symbolic _____SgXwz_Xx 10ZoomWindow0A13MenuViewModelC
- -[ZWUIServer addScene:isExternal:isMain:]
- -[ZWUIServer sceneIdentifierForScene:]
- GCC_except_table1132
- GCC_except_table1179
- GCC_except_table1223
- GCC_except_table1244
- GCC_except_table1246
- GCC_except_table1347
- GCC_except_table1515
- GCC_except_table665
- GCC_except_table766
- GCC_except_table802
- OBJC_IVAR_$_ZWUIServer._pendingShowZoom
- ___32-[ZWUIServer _showZoomWindowNow]_block_invoke
- ___41-[ZWUIServer addScene:isExternal:isMain:]_block_invoke
- ___75-[ZWUIServer processMessage:withIdentifier:fromClientWithIdentifier:error:]_block_invoke_14
- __swift_closure_destructor.90Tm
- _objc_msgSend$addContentViewController:withUserInteractionEnabled:forService:context:userInterfaceStyle:forWindowScene:completion:
- _objc_msgSend$addScene:isExternal:isMain:
- _objc_msgSend$sceneIdentifierForScene:
CStrings:
+ "%u"
+ "@\"NSMapTable\""
+ "@20@0:8I16"
+ "Made new zoom root view controller: %@ for display %@"
+ "No zoom controller for displayID %u"
+ "_defaultDisplayController"
+ "_didRequestScenes"
+ "_displayKeyByScene"
+ "_hideZoomWindowNow"
+ "_isEmbeddedScreen"
+ "_resolvedDisplayIDForScreen:"
+ "_zoomWindowShouldBeVisible"
+ "activationState"
+ "addScene:isExternal:"
+ "contentViewControllersWithUserInteractionEnabled:forService:"
+ "controllerForDisplayID:"
+ "displayKeyForScene:"
+ "reconcileDisplays"
+ "requestScenesForService:atPreferredSceneLevel:forSceneClientIdentifier:"
+ "usesScenes"
+ "weakToStrongObjectsMapTable"
- "Attempting to add a scene we already have a reference to. ZWVC ID: %@ ZWVC hardwareID: %@ - scene hardwareID: %@"
- "Made new zoom root view controller: %@"
- "_pendingShowZoom"
- "_shouldIncludeDockPositionButton"
- "_shouldIncludeResizeLensButton"
- "addContentViewController:withUserInteractionEnabled:forService:context:userInterfaceStyle:forWindowScene:completion:"
- "addScene:isExternal:isMain:"
- "sceneIdentifierForScene:"
```
