## HomeUI

> `/System/Library/PrivateFrameworks/HomeUI.framework/HomeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80a518` | `0x80cbd0` | **`+0x26b8`** |
| `__AUTH_CONST.__objc_const` | `0x91180` | `0x91a00` | **`+0x880`** |
| `__TEXT.__objc_methlist` | `0x50644` | `0x50a3c` | **`+0x3f8`** |
| `__AUTH_CONST.__cfstring` | `0x22a40` | `0x22ca0` | **`+0x260`** |
| `__TEXT.__cstring` | `0x42d03` | `0x42edc` | **`+0x1d9`** |
| `__AUTH.__objc_data` | `0x1c8c0` | `0x1ca50` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x223b0` | `0x224f8` | **`+0x148`** |
| `__TEXT.__unwind_info` | `0x1c1f8` | `0x1c2b8` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x8c10` | `0x8c94` | **`+0x84`** |
| `__DATA.__data` | `0x15590` | `0x155f0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xf568` | `0xf5b8` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x1b3a8` | `0x1b3e8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x70a8` | `0x70e0` | **`+0x38`** |
| `__DATA_DIRTY.__objc_ivar` | `0x3b2c` | `0x3b60` | **`+0x34`** |
| `__DATA_CONST.__objc_classlist` | `0x2930` | `0x2958` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f00` | `0x1f28` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1950` | `0x1968` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x5030` | `0x5028` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1260` | `0x1268` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 44095
-  Symbols:   47250
-  CStrings:  9701
+  Functions: 44169
+  Symbols:   47382
+  CStrings:  9720
Symbols:
+ -[HUCameraController diagnosticsController]
+ -[HUCameraController setDiagnosticsController:]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController .cxx_destruct]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController cameraClip]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController eventTableView]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController initWithCameraClip:]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController numberOfSectionsInTableView:]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController setCameraClip:]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController setEventTableView:]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController tableView:cellForRowAtIndexPath:]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController tableView:numberOfRowsInSection:]
+ -[HUDiagnosticsCameraClipSignificantEventsViewController viewDidLoad]
+ -[HUDiagnosticsCameraClipViewController .cxx_destruct]
+ -[HUDiagnosticsCameraClipViewController cameraClip]
+ -[HUDiagnosticsCameraClipViewController cameraProfile]
+ -[HUDiagnosticsCameraClipViewController eventTableView]
+ -[HUDiagnosticsCameraClipViewController initWithRecordingEvent:cameraProfile:]
+ -[HUDiagnosticsCameraClipViewController numberOfSectionsInTableView:]
+ -[HUDiagnosticsCameraClipViewController setCameraClip:]
+ -[HUDiagnosticsCameraClipViewController setCameraProfile:]
+ -[HUDiagnosticsCameraClipViewController setEventTableView:]
+ -[HUDiagnosticsCameraClipViewController tableView:cellForRowAtIndexPath:]
+ -[HUDiagnosticsCameraClipViewController tableView:didSelectRowAtIndexPath:]
+ -[HUDiagnosticsCameraClipViewController tableView:numberOfRowsInSection:]
+ -[HUDiagnosticsCameraClipViewController viewDidLoad]
+ -[HUDiagnosticsCameraPlayerController .cxx_destruct]
+ -[HUDiagnosticsCameraPlayerController cameraPlayerViewController]
+ -[HUDiagnosticsCameraPlayerController cameraProfile]
+ -[HUDiagnosticsCameraPlayerController clipScrubberDataSource]
+ -[HUDiagnosticsCameraPlayerController contextMenuInteraction:configurationForMenuAtLocation:]
+ -[HUDiagnosticsCameraPlayerController diagnosticsView]
+ -[HUDiagnosticsCameraPlayerController dismissDetailsViewController]
+ -[HUDiagnosticsCameraPlayerController dismissDiagnosticDetails]
+ -[HUDiagnosticsCameraPlayerController displayDiagnosticDetails]
+ -[HUDiagnosticsCameraPlayerController displayTimelapseDetails]
+ -[HUDiagnosticsCameraPlayerController initWithCameraPlayerViewController:playbackEngine:clipScrubberDataSource:cameraProfile:]
+ -[HUDiagnosticsCameraPlayerController launchPlaybackEngineDiagnosticsView]
+ -[HUDiagnosticsCameraPlayerController playbackEngine]
+ -[HUDiagnosticsCameraPlayerController setCameraPlayerViewController:]
+ -[HUDiagnosticsCameraPlayerController setCameraProfile:]
+ -[HUDiagnosticsCameraPlayerController setClipScrubberDataSource:]
+ -[HUDiagnosticsCameraPlayerController setDiagnosticsView:]
+ -[HUDiagnosticsCameraPlayerController setPlaybackEngine:]
+ -[HUDiagnosticsCameraPlayerController updateWithPlaybackEngine:]
+ -[HUDiagnosticsCameraTimelineView .cxx_destruct]
+ -[HUDiagnosticsCameraTimelineView cameraStatusLabel]
+ -[HUDiagnosticsCameraTimelineView currentEventLabel]
+ -[HUDiagnosticsCameraTimelineView currentPositionLabel]
+ -[HUDiagnosticsCameraTimelineView currentTimelineStateLabel]
+ -[HUDiagnosticsCameraTimelineView initWithFrame:]
+ -[HUDiagnosticsCameraTimelineView moreButton]
+ -[HUDiagnosticsCameraTimelineView setCameraStatusLabel:]
+ -[HUDiagnosticsCameraTimelineView setCurrentEventLabel:]
+ -[HUDiagnosticsCameraTimelineView setCurrentPositionLabel:]
+ -[HUDiagnosticsCameraTimelineView setCurrentTimelineStateLabel:]
+ -[HUDiagnosticsCameraTimelineView setMoreButton:]
+ -[HUDiagnosticsCameraTimelineView updateWithPlaybackEngine:]
+ -[HUDiagnosticsReachabilityEventViewController .cxx_destruct]
+ -[HUDiagnosticsReachabilityEventViewController cameraProfile]
+ -[HUDiagnosticsReachabilityEventViewController container]
+ -[HUDiagnosticsReachabilityEventViewController eventTableView]
+ -[HUDiagnosticsReachabilityEventViewController initWithReachabilityEvent:cameraProfile:]
+ -[HUDiagnosticsReachabilityEventViewController numberOfSectionsInTableView:]
+ -[HUDiagnosticsReachabilityEventViewController setCameraProfile:]
+ -[HUDiagnosticsReachabilityEventViewController setContainer:]
+ -[HUDiagnosticsReachabilityEventViewController setEventTableView:]
+ -[HUDiagnosticsReachabilityEventViewController tableView:cellForRowAtIndexPath:]
+ -[HUDiagnosticsReachabilityEventViewController tableView:didSelectRowAtIndexPath:]
+ -[HUDiagnosticsReachabilityEventViewController tableView:numberOfRowsInSection:]
+ -[HUDiagnosticsReachabilityEventViewController viewDidLoad]
+ _HUCameraSignificantEventsBrowserCellIdentifier
+ _HUDiagnosticsHomeKitSettingsPath
+ _HUDiagnosticsHomeSettingsPath
+ _HUDiagnosticsReachabilityEventCellIdentifier
+ _HUDiagnosticsRecordingCellEventIdentifier
+ _OBJC_CLASS_$_AVURLAsset
+ _OBJC_CLASS_$_HUDiagnosticsCameraClipSignificantEventsViewController
+ _OBJC_CLASS_$_HUDiagnosticsCameraClipViewController
+ _OBJC_CLASS_$_HUDiagnosticsCameraPlayerController
+ _OBJC_CLASS_$_HUDiagnosticsCameraTimelineView
+ _OBJC_CLASS_$_HUDiagnosticsReachabilityEventViewController
+ _OBJC_CLASS_$_UIContextMenuInteraction
+ _OBJC_IVAR_$_HUCameraController._diagnosticsController
+ _OBJC_IVAR_$_HUDiagnosticsCameraPlayerController._cameraPlayerViewController
+ _OBJC_IVAR_$_HUDiagnosticsCameraPlayerController._cameraProfile
+ _OBJC_IVAR_$_HUDiagnosticsCameraPlayerController._clipScrubberDataSource
+ _OBJC_IVAR_$_HUDiagnosticsCameraPlayerController._diagnosticsView
+ _OBJC_IVAR_$_HUDiagnosticsCameraPlayerController._playbackEngine
+ _OBJC_METACLASS_$_HUDiagnosticsCameraClipSignificantEventsViewController
+ _OBJC_METACLASS_$_HUDiagnosticsCameraClipViewController
+ _OBJC_METACLASS_$_HUDiagnosticsCameraPlayerController
+ _OBJC_METACLASS_$_HUDiagnosticsCameraTimelineView
+ _OBJC_METACLASS_$_HUDiagnosticsReachabilityEventViewController
+ __OBJC_$_INSTANCE_METHODS_HUDiagnosticsCameraClipSignificantEventsViewController
+ __OBJC_$_INSTANCE_METHODS_HUDiagnosticsCameraClipViewController
+ __OBJC_$_INSTANCE_METHODS_HUDiagnosticsCameraPlayerController
+ __OBJC_$_INSTANCE_METHODS_HUDiagnosticsCameraTimelineView
+ __OBJC_$_INSTANCE_METHODS_HUDiagnosticsReachabilityEventViewController
+ __OBJC_$_INSTANCE_VARIABLES_HUDiagnosticsCameraClipSignificantEventsViewController
+ __OBJC_$_INSTANCE_VARIABLES_HUDiagnosticsCameraClipViewController
+ __OBJC_$_INSTANCE_VARIABLES_HUDiagnosticsCameraPlayerController
+ __OBJC_$_INSTANCE_VARIABLES_HUDiagnosticsCameraTimelineView
+ __OBJC_$_INSTANCE_VARIABLES_HUDiagnosticsReachabilityEventViewController
+ __OBJC_$_PROP_LIST_HUDiagnosticsCameraClipSignificantEventsViewController
+ __OBJC_$_PROP_LIST_HUDiagnosticsCameraClipViewController
+ __OBJC_$_PROP_LIST_HUDiagnosticsCameraPlayerController
+ __OBJC_$_PROP_LIST_HUDiagnosticsCameraTimelineView
+ __OBJC_$_PROP_LIST_HUDiagnosticsReachabilityEventViewController
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIContextMenuInteractionDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UIContextMenuInteractionDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UIContextMenuInteractionDelegate
+ __OBJC_$_PROTOCOL_REFS_UIContextMenuInteractionDelegate
+ __OBJC_CLASS_PROTOCOLS_$_HUDiagnosticsCameraClipSignificantEventsViewController
+ __OBJC_CLASS_PROTOCOLS_$_HUDiagnosticsCameraClipViewController
+ __OBJC_CLASS_PROTOCOLS_$_HUDiagnosticsCameraPlayerController
+ __OBJC_CLASS_PROTOCOLS_$_HUDiagnosticsReachabilityEventViewController
+ __OBJC_CLASS_RO_$_HUDiagnosticsCameraClipSignificantEventsViewController
+ __OBJC_CLASS_RO_$_HUDiagnosticsCameraClipViewController
+ __OBJC_CLASS_RO_$_HUDiagnosticsCameraPlayerController
+ __OBJC_CLASS_RO_$_HUDiagnosticsCameraTimelineView
+ __OBJC_CLASS_RO_$_HUDiagnosticsReachabilityEventViewController
+ __OBJC_LABEL_PROTOCOL_$_UIContextMenuInteractionDelegate
+ __OBJC_METACLASS_RO_$_HUDiagnosticsCameraClipSignificantEventsViewController
+ __OBJC_METACLASS_RO_$_HUDiagnosticsCameraClipViewController
+ __OBJC_METACLASS_RO_$_HUDiagnosticsCameraPlayerController
+ __OBJC_METACLASS_RO_$_HUDiagnosticsCameraTimelineView
+ __OBJC_METACLASS_RO_$_HUDiagnosticsReachabilityEventViewController
+ __OBJC_PROTOCOL_$_UIContextMenuInteractionDelegate
+ ___93-[HUDiagnosticsCameraPlayerController contextMenuInteraction:configurationForMenuAtLocation:]_block_invoke
+ ___93-[HUDiagnosticsCameraPlayerController contextMenuInteraction:configurationForMenuAtLocation:]_block_invoke_2
+ ___93-[HUDiagnosticsCameraPlayerController contextMenuInteraction:configurationForMenuAtLocation:]_block_invoke_3
+ ___93-[HUDiagnosticsCameraPlayerController contextMenuInteraction:configurationForMenuAtLocation:]_block_invoke_4
+ ___block_descriptor_40_e8_32w_e25_"UIMenu"16?0"NSArray"8lw32l8
- _objc_retain_x12
CStrings:
+ "!!\xf0\x92\xe1"
+ "Can ask for feedback: %@"
+ "Complete: %@"
+ "Duration: %.2f"
+ "Event Details"
+ "HUCameraSignificantEventsBrowserCellIdentifier"
+ "HUDiagnosticsReachabilityEventCellIdentifier"
+ "HUDiagnosticsRecordingCellEventIdentifier"
+ "Hide Inspector"
+ "Home Settings"
+ "HomeKit Settings"
+ "Show Inspector"
+ "Significant Events: %lu"
+ "Start Date: %@"
+ "Target Fragment Duration: %.2f"
+ "UUID: %@"
+ "magnifyingglass.circle"
+ "magnifyingglass.circle.fill"
+ "prefs:root=INTERNAL_SETTINGS&path=Home"
+ "prefs:root=INTERNAL_SETTINGS&path=HomeKit"
- "!!\xf0\x92\xd1"
```
