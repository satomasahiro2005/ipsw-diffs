## FlowToolsRegistry

> `/System/Library/PrivateFrameworks/FlowToolsRegistry.framework/FlowToolsRegistry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__common` | `0x68` | `0xe0` | **`+0x78`** |
| `__DATA_DIRTY.__common` | `0x13d8` | `0x1360` | **`-0x78`** |
| `__TEXT.__cstring` | `0x4d44` | `0x4db4` | **`+0x70`** |
| `__TEXT.__text` | `0xa4948` | `0xa494c` | **`+0x4`** |

### Other Changes

```diff

-3600.65.18.1.1
+3600.65.26.1.1

-  Functions: 4014
+  Functions: 4013
CStrings:
+ "MapsUpdateNavigationWaypointsIntent"
+ "Replace the active navigation session's waypoints with the provided list."
+ "The active navigation session to update."
+ "The full desired set of waypoints for the navigation session. The session's existing stops are replaced with this list."
+ "Update Navigation Waypoints"
+ "UpdateNavigationWaypoints"
+ "UpdateWayPointsFlowTool"
- "Add waypoints to Navigation"
- "Add waypoints to existing navigation session"
- "AddNavigationWaypointsIntent"
- "AddWayPointsFlowTool"
- "MapsAddNavigationWaypointsIntent"
- "The places to add as waypoints to existing navigation session"
- "existing navigation session"
```
