## FMFindingUI

> `/System/Library/PrivateFrameworks/FMFindingUI.framework/FMFindingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x190bac` | `0x1a6f60` | **`+0x163b4`** |
| `__TEXT.__oslogstring` | `0x7010` | `0x7de0` | **`+0xdd0`** |
| `__AUTH_CONST.__const` | `0xed79` | `0xf999` | **`+0xc20`** |
| `__TEXT.__cstring` | `0x5655` | `0x6065` | **`+0xa10`** |
| `__DATA.__bss` | `0xbac0` | `0xbf40` | **`+0x480`** |
| `__TEXT.__const` | `0xe104` | `0xe4b4` | **`+0x3b0`** |
| `__TEXT.__swift5_capture` | `0x35e0` | `0x3990` | **`+0x3b0`** |
| `__TEXT.__swift5_reflstr` | `0x6fb2` | `0x7302` | **`+0x350`** |
| `__TEXT.__constg_swiftt` | `0x8510` | `0x879c` | **`+0x28c`** |
| `__TEXT.__eh_frame` | `0x2934` | `0x2b94` | **`+0x260`** |
| `__AUTH.__objc_data` | `0x7f68` | `0x81a0` | **`+0x238`** |
| `__TEXT.__swift5_fieldmd` | `0x54cc` | `0x56e0` | **`+0x214`** |
| `__TEXT.__unwind_info` | `0x3e00` | `0x4010` | **`+0x210`** |
| `__AUTH.__data` | `0x32d0` | `0x34d0` | **`+0x200`** |
| `__AUTH_CONST.__objc_const` | `0x11a40` | `0x11bc0` | **`+0x180`** |
| `__DATA.__data` | `0x4b10` | `0x4c88` | **`+0x178`** |
| `__TEXT.__swift5_typeref` | `0xb592` | `0xb6e6` | **`+0x154`** |
| `__DATA_CONST.__objc_selrefs` | `0x1dd0` | `0x1e88` | **`+0xb8`** |
| `__DATA_CONST.__got` | `0xb58` | `0xbd8` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x2594` | `0x25fc` | **`+0x68`** |
| `__DATA.__common` | `0x9f8` | `0xa28` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x644` | `0x668` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x1778` | `0x1798` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x3ec` | `0x408` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0xf8` | `0x114` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x950` | `0x968` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x280` | `0x294` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x258` | `0x268` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x310` | `0x300` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x60` | `0x6c` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x80` | `0x84` | **`+0x4`** |

### Other Changes

```diff

-104.31.6.16.13
+104.31.6.16.16

-  Functions: 7138
-  Symbols:   504
-  CStrings:  1013
+  Functions: 7438
+  Symbols:   513
+  CStrings:  1120
Symbols:
+ _OBJC_CLASS_$_NINearbyAccessoryConfiguration
+ _OBJC_CLASS_$_SPBTFindingSession
+ _OBJC_CLASS_$_SPBTFindingSessionConfig
+ _OBJC_CLASS_$__TtC11FMFindingUI27FMItemBTCSConnectionManager
+ _OBJC_METACLASS_$__TtC11FMFindingUI27FMItemBTCSConnectionManager
+ _SPBTFindingSessionErrorDomain
+ _objc_release_x10
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
CStrings:
+ ", findingDuration: "
+ ", firstDistance: "
+ ", longestDistance: "
+ ", niSessionStarts: "
+ ", shortestDistance: "
+ ", timeToFirstDirection: "
+ ", timeToFirstDistance: "
+ ".accessoryConnected("
+ ".accessoryDisconnected"
+ ".accessoryInitiatedDisconnect"
+ ".btConnectionFailed"
+ ".btReflectorModeFailed"
+ ".connectedToCompanion"
+ ".legacy(.precisionBTCS)"
+ ".motionStateUpdate("
+ "Accessory connected to a companion device"
+ "Accessory initiated a disconnect"
+ "BTCS session start: reachEnterDistance=%{public}fm, enterHereDistance=%{public}fm"
+ "BT_FINDING_ACCESSORY_DISCONNECTED_CONTINUE_BUTTON_TITLE"
+ "BT_FINDING_ACCESSORY_DISCONNECTED_MESSAGE"
+ "BT_FINDING_ACCESSORY_DISCONNECTED_STOP_BUTTON_TITLE"
+ "BT_FINDING_ACCESSORY_DISCONNECTED_TITLE"
+ "BT_FINDING_CONNECTED_TO_COMPANION_CONTINUE_BUTTON_TITLE"
+ "BT_FINDING_CONNECTED_TO_COMPANION_MESSAGE"
+ "BT_FINDING_CONNECTED_TO_COMPANION_STOP_BUTTON_TITLE"
+ "BT_FINDING_CONNECTED_TO_COMPANION_TITLE"
+ "BT_FINDING_CONNECTION_ERROR_MESSAGE"
+ "BT_FINDING_CONNECTION_ERROR_TITLE"
+ "BT_FINDING_SETUP_ERROR_MESSAGE"
+ "BT_FINDING_SETUP_ERROR_TITLE"
+ "Disabling reflector for item: %{private,mask.hash}s"
+ "Enable reflector for item: %{private,mask.hash}s"
+ "FMFindingLocalizedString BT_FINDING_ACCESSORY_DISCONNECTED_CONTINUE_BUTTON_TITLE"
+ "FMFindingLocalizedString BT_FINDING_ACCESSORY_DISCONNECTED_MESSAGE"
+ "FMFindingLocalizedString BT_FINDING_ACCESSORY_DISCONNECTED_STOP_BUTTON_TITLE"
+ "FMFindingLocalizedString BT_FINDING_ACCESSORY_DISCONNECTED_TITLE"
+ "FMFindingLocalizedString BT_FINDING_CONNECTED_TO_COMPANION_CONTINUE_BUTTON_TITLE"
+ "FMFindingLocalizedString BT_FINDING_CONNECTED_TO_COMPANION_MESSAGE"
+ "FMFindingLocalizedString BT_FINDING_CONNECTED_TO_COMPANION_STOP_BUTTON_TITLE"
+ "FMFindingLocalizedString BT_FINDING_CONNECTED_TO_COMPANION_TITLE"
+ "FMFindingLocalizedString BT_FINDING_CONNECTION_ERROR_MESSAGE"
+ "FMFindingLocalizedString BT_FINDING_CONNECTION_ERROR_TITLE"
+ "FMFindingLocalizedString BT_FINDING_SETUP_ERROR_MESSAGE"
+ "FMFindingLocalizedString BT_FINDING_SETUP_ERROR_TITLE"
+ "Failed to disable reflector mode: %{public}@"
+ "Failed to restore BTCS reflector session: %{public}@"
+ "Failure enabling reflector for item: %{private,mask.hash}s, error: %{public}@"
+ "No valid findingType in %s %{public}s."
+ "Restored BTCS reflector session after accessory reconnected"
+ "Start scanning for item: %{private,mask.hash}s"
+ "Stop scanning for item: %{private,mask.hash}s"
+ "Successfully disabled reflector for item: %{private,mask.hash}s"
+ "applicationDidEnterBackground"
+ "applicationWillEnterForeground"
+ "btcsConnectionManager"
+ "btcsHereDistanceMeters"
+ "btcsReachModeThresholdEnter"
+ "btcsSession error: %{public}@"
+ "btcsSession got .accessoryConnectedToCompanion"
+ "btcsSession got .accessoryInitiatedDisconnect"
+ "btcsSession got accessory state update: %{public}@"
+ "btcsSession invalidated, creating new session"
+ "com.apple.findmy.findingsession.metrics"
+ "connectAndEnableReflector(completion:)"
+ "deinit for items: %{private,mask.hash}s"
+ "didUpdateBTRSSIMeasurementCallback"
+ "didUpdateBTRSSIResultCallback"
+ "disableReflector()"
+ "init(findables:findingType:arSession:delegate:)"
+ "initialized for items: %{private,mask.hash}s"
+ "longest_distance"
+ "ni_session_start_count"
+ "peripheralID is nil, but expected!"
+ "precision_btcs_nearbyInteraction_"
+ "shortest_distance"
+ "startFinding error for item %{private,mask.hash}s: %{public}@"
+ "stopFinding error for item %{private,mask.hash}s: %{public}@"
+ "time_to_first_direction"
+ "time_to_first_distance"
+ "🧭 FMFindingLocalizer: accessory connected to companion device"
+ "🧭 FMFindingLocalizer: accessory initiated intentional disconnect"
+ "🧭 FMFindingViewCtrl: Not showing repeated ContinueOrStopFindingAlert"
+ "🧭 FMFindingViewCtrl: Resuming finding after accessory initiated disconnect."
+ "🧭 FMFindingViewCtrl: Resuming finding after connected to companion."
+ "🧭 FMFindingViewCtrl: Showing accessory initiated disconnect alert."
+ "🧭 FMFindingViewCtrl: Showing connected to companion alert."
+ "🧭 FMR1NIContxt%@: Accessory connected: %{public}s"
+ "🧭 FMR1NIContxt%@: Accessory disconnected"
+ "🧭 FMR1NIContxt%@: NI sent nearbyObject update, but session is reconnecting. Aborting!"
+ "🧭 FMR1NIContxt%@: failed to update accessory motion state: no accessory discovery token."
+ "🧭 FMR1NIContxt%@: failed to update accessory motion state: no session."
+ "🧭 FMR1NIContxt%@: not starting niSession: BTCS accessory not connected"
+ "🧭 FMR1NIContxt%@: updateAccessoryMotionState: %ld"
+ "🧭 FMR1NIContxt: Error configuring NIConfiguration. Item have no peripheralID"
+ "🧭 FMR1NIContxt: Error configuring NIConfiguration. Item is not FMBTCSFindable"
+ "🧭 FMR1NIMgr%s: Did not find a context for item %{private,mask.hash}s for accessoryConnected."
+ "🧭 FMR1NIMgr%s: Did not find a context for item %{private,mask.hash}s for motionStateUpdate."
+ "🧭 FMR1NIMgr%s: Did receive updateAccessoryState event: %s"
+ "🧭 FMR1NIMgr%s: no peripheralID for item: %{private,mask.hash}s"
+ "🧭 FMR1NISubscr%s: finding session metrics — %{public}s"
+ "🧭 FindingViewController: Not showing repeated ContinueOrStopFindingAlert"
+ "🧭 FindingViewController: Resuming finding after accessory initiated disconnect."
+ "🧭 FindingViewController: Resuming finding after connected to companion."
+ "🧭 FindingViewController: Showing accessory initiated disconnect alert."
+ "🧭 FindingViewController: Showing connected to companion alert."
+ "🧭 FindingViewController: btConnectionFailed error"
+ "🧭 FindingViewController: btReflectorModeFailed error"
```
