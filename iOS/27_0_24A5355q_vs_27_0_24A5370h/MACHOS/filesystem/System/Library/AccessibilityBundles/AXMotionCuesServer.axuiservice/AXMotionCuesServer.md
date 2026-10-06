## AXMotionCuesServer

> `/System/Library/AccessibilityBundles/AXMotionCuesServer.axuiservice/AXMotionCuesServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31c74` | `0x2e82c` | **`-0x3448`** |
| `__TEXT.__eh_frame` | `0x12e8` | `0x10f8` | **`-0x1f0`** |
| `__TEXT.__auth_stubs` | `0x1760` | `0x1680` | **`-0xe0`** |
| `__TEXT.__unwind_info` | `0xb68` | `0xae8` | **`-0x80`** |
| `__DATA_CONST.__const` | `0x1360` | `0x12e8` | **`-0x78`** |
| `__DATA_CONST.__auth_got` | `0xbc0` | `0xb50` | **`-0x70`** |
| `__TEXT.__swift5_typeref` | `0x9ce` | `0x95e` | **`-0x70`** |
| `__TEXT.__objc_methname` | `0x282d` | `0x288d` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1240` | `0x12a0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xc5a` | `0xcba` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x3bc` | `0x374` | **`-0x48`** |
| `__DATA.__objc_data` | `0xcf8` | `0xd20` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0xf8` | `0xd4` | **`-0x24`** |
| `__DATA.__objc_const` | `0x24b8` | `0x24d8` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x6f0` | `0x710` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x128c` | `0x12ac` | **`+0x20`** |
| `__DATA.__data` | `0x1e30` | `0x1e18` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x330` | `0x348` | **`+0x18`** |
| `__TEXT.__const` | `0x1f70` | `0x1f60` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xf20` | `0xf10` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xc90` | `0xc9c` | **`+0xc`** |
| `__TEXT.__objc_methlist` | `0x650` | `0x658` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x6c` | `0x70` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__vfx_script_tby`
- `__TEXT.__cstring`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 899
-  Symbols:   316
-  CStrings:  721
+  Functions: 858
+  Symbols:   315
+  CStrings:  725
Symbols:
+ _OBJC_CLASS_$_NSNotificationCenter
+ _UISceneDidActivateNotification
+ _UISceneDidEnterBackgroundNotification
+ _swift_release_x9
- _objc_retain_x1
- _objc_retain_x9
- _swift_bridgeObjectRetain_n
- _swift_release_x1
- _swift_retain_x24
CStrings:
+ "Attached Motion Cues UI for preferred scene %@"
+ "Called removeMainDisplayViewController but view controller is already nil."
+ "Failed to attach Motion Cues for preferred scene: %@"
+ "Got nil device motion but motion manager is not active. Cleaning up mainDisplayViewController %@."
+ "Moving Motion Cues view controller to active scene %@"
+ "No active scene available; tearing down Motion Cues view controller"
+ "Re-running setup for new scene size %s"
+ "Scene connected %s"
+ "Scene disconnected %s"
+ "_lastActiveScene"
+ "_mainDisplayViewController"
+ "_motionCuesModel"
+ "_windowScenes"
+ "activationState"
+ "addObserver:selector:name:object:"
+ "defaultCenter"
+ "firstNilModelOutputTime"
+ "handleSceneDidChange viewSize=%s lastSetupSize=%s"
+ "lastSetupSize"
+ "model output nil for %f seconds; requesting reset"
+ "moveContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:userInterfaceStyle:toWindowScene:completion:"
+ "sceneActivationStateDidChange:"
- "Attached Motion Cues UI for connected scene"
- "Coordinator did not show Motion cues main screen %@"
- "Failed to attach Motion Cues for connected scene: %@"
- "Failed to detach Motion Cues for disconnected scene: %@"
- "Got nil device motion but motion manager is not active. Cleaning up view controllers %s"
- "Motion Cues UI started on scene"
- "Removed Motion Cues UI for disconnected scene"
- "Scene already has a view controller, skipping"
- "Scene already known, skipping"
- "Scene connected"
- "Scene disconnected"
- "_knownScenes"
- "_registeredForSceneUpdates"
- "_sceneModels"
- "_sceneViewControllers"
- "got 50 nil model outputs in a row"
- "nilModelOutputCount"
- "removeContentViewController:withUserInteractionEnabled:forService:context:completion:"
```
