## FlowToolsRegistry

> `/System/Library/PrivateFrameworks/FlowToolsRegistry.framework/FlowToolsRegistry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa5028` | `0xa8098` | **`+0x3070`** |
| `__DATA.__common` | `0x140` | `0x3c8` | **`+0x288`** |
| `__TEXT.__cstring` | `0x4d54` | `0x4e94` | **`+0x140`** |
| `__DATA_DIRTY.__common` | `0x1330` | `0x1290` | **`-0xa0`** |
| `__DATA_DIRTY.__bss` | `0x3f90` | `0x4020` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x3730` | `0x36a8` | **`-0x88`** |
| `__DATA_CONST.__const` | `0x208` | `0x248` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x169c` | `0x1664` | **`-0x38`** |
| `__DATA.__data` | `0x660` | `0x690` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x920` | `0x950` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1ef8` | `0x1f20` | **`+0x28`** |
| `__TEXT.__const` | `0x5828` | `0x5808` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0xd14` | `0xd24` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x27f0` | `0x27fc` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xce8` | `0xcf0` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0xf08` | `0xf10` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x16d0` | `0x16c8` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x4cc` | `0x4c4` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x18b4` | `0x18bc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x26c` | `0x264` | **`-0x8`** |

### Other Changes

```diff

-3600.65.34.0.0
+3605.23.1.1.1

-  Functions: 4026
+  Functions: 4079

-  CStrings:  530
+  CStrings:  545
CStrings:
+ "Create Incoming Geofence"
+ "Create Outgoing Geofence"
+ "Create an incoming geofence notification for a person at a location."
+ "Create an outgoing geofence notification for a person at a location."
+ "CreateIncomingGeofenceIntent"
+ "CreateIncomingGeofenceTool"
+ "CreateOutgoingGeofenceIntent"
+ "CreateOutgoingGeofenceTool"
+ "Crisis-support categories to look up"
+ "CrisisResourceCategory"
+ "Find Item Location"
+ "Find the location of a Find My item."
+ "FindItemLocationIntent"
+ "FindItemLocationTool"
+ "Get Crisis Resources"
+ "GetCrisisResources"
+ "GetCrisisResourcesFlowTool"
+ "Offline lookup of verified crisis-support resources"
+ "Play a sound on a Find My item."
+ "PlayItemSoundIntent"
+ "PlayItemSoundTool"
+ "Resource Categories"
+ "SiriFindMyFlowTools"
+ "SiriVideoPersonEntity"
+ "The item to find the location of"
+ "The item to play a sound on"
+ "The location for the geofence"
+ "The person to create a geofence for"
+ "The trigger condition for the geofence"
+ "Whether the geofence notification is recurring"
+ "com.apple.siri.findmy.SiriFindMyFlowTools"
+ "resourceCategories"
- "A standalone tool to interactively install or update marketplace applications."
- "CrisisDialogFlowTool"
- "CrisisDialogSituation"
- "Display interactive UI for installing or updating marketplace applications with rich metadata and user interaction support. Shows app cards with artwork, ratings, reviews, and install/update buttons."
- "Handle crisis dialog"
- "Handles crisis dialog for emergency and CSAM situations"
- "Interactive Install Application"
- "InteractiveInstallApplication"
- "InteractiveInstallApplicationTool"
- "List of marketplace applications to install or update"
- "SiriAppLaunchFlowTools"
- "SiriAppLaunchFlowTools.framework"
- "The crisis or CSAM situation"
- "Whether this is an update operation"
- "_MarketplaceKit_AppIntents.DisplayableMarketplaceApplication"
- "com.apple.siri.-MarketplaceIntents-AppIntents"
- "com.apple.siri.SiriAppLaunchFlowTools"
```
