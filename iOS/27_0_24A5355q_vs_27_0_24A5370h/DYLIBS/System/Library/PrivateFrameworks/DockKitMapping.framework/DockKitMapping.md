## DockKitMapping

> `/System/Library/PrivateFrameworks/DockKitMapping.framework/DockKitMapping`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4124` | `0x40a0` | **`-0x84`** |
| `__TEXT.__unwind_info` | `0xd0` | `0xc8` | **`-0x8`** |

### Other Changes

```diff

-410.1.0.0.0
-  - /System/Library/PrivateFrameworks/ObjectUnderstanding.framework/ObjectUnderstanding
-  - /System/Library/PrivateFrameworks/RoomScanCore.framework/RoomScanCore
+411.0.0.0.0
Functions:
~ _orb_init : 600 -> 604
~ _orb_extract_features : 3832 -> 3796
~ _orb_hamming_distance : 68 -> 64
~ _orb_serialize_features : 200 -> 220
~ _orb_deserialize_features : 184 -> 236
~ _fm_match_features : 3504 -> 3488
~ _fm_get_match : 64 -> 68
~ _pnp_compute_reprojection_errors : 164 -> 180
~ _pnp_solve_dlt : 2672 -> 2520
~ _solve_6x6 : 464 -> 456
~ _pnp_refine_iterative : 1356 -> 1380
~ _pnp_solve_ransac : 1472 -> 1436
```
