## DockKitMapping

> `/System/Library/PrivateFrameworks/DockKitMapping.framework/DockKitMapping`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x31f60` | `0x40760` | **`+0xe800`** |
| `__TEXT.__text` | `0x40c4` | `0x4da8` | **`+0xce4`** |
| `__TEXT.__const` | `0x4d8` | `0x508` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xc8` | `0xe0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x68` | `0x70` | **`+0x8`** |

### Other Changes

```diff

-414.0.0.0.0
+431.0.0.0.0

-  Functions: 24
-  Symbols:   70
+  Functions: 28
+  Symbols:   80
Symbols:
+ ___memcpy_chk
+ _kv_rotation
+ _kv_solve_translation
+ _pnp_score_pose
+ _pnp_solve_ransac_known_vertical
+ _pnp_solve_ransac_known_vertical.s_kv_inliers
+ _s_guard_mask
+ _s_inlier_img
+ _s_inlier_obj
+ _s_lo_errors
Functions:
~ _fm_match_features : 3496 -> 3476
~ _pnp_solve_ransac : 1436 -> 2076
```
