## PhotosFace

> `/System/Library/PrivateFrameworks/PhotosFace.framework/PhotosFace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcf1f4` | `0xcf858` | **`+0x664`** |
| `__TEXT.__cstring` | `0x400c` | `0x40fc` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0xab68` | `0xab80` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x328` | `0x340` | **`+0x18`** |
| `__TEXT.__const` | `0x7c18` | `0x7c28` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x720` | `0x730` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4100` | `0x4108` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x3fc` | `0x400` | **`+0x4`** |

### Other Changes

```diff

-96.0.0.0.0
+98.0.0.0.0

-  Functions: 4283
+  Functions: 4284
Symbols:
+ ___swift_closure_destructor.203Tm
+ ___swift_closure_destructor.238Tm
- ___swift_closure_destructor.201Tm
- ___swift_closure_destructor.236Tm
CStrings:
+ "    DELETE FROM tracked_album_photos\n    WHERE\n        CASE WHEN day > ? THEN day/? ELSE day END >= ?      -- rdar://145093387\n        AND CASE WHEN day > ? THEN day/? ELSE day END <= ?  -- rdar://145093387\n        AND album_id = ?"
+ "    DELETE FROM tracked_gallery_photos\n    WHERE\n        CASE WHEN day > ? THEN day/? ELSE day END >= ?      -- rdar://145093387\n        AND CASE WHEN day > ? THEN day/? ELSE day END <= ?  -- rdar://145093387\n        AND gallery_id = ?"
+ "    DELETE FROM tracked_shuffle_photos\n    WHERE\n        CASE WHEN day > ? THEN day/? ELSE day END >= ?      -- rdar://145093387\n        AND CASE WHEN day > ? THEN day/? ELSE day END <= ?  -- rdar://145093387\n        AND shuffle_id = ?"
- "    DELETE FROM tracked_album_photos\n    WHERE\n        CASE WHEN day > ? THEN day/? ELSE day END < ?  -- rdar://145093387\n        AND album_id = ?"
- "    DELETE FROM tracked_gallery_photos\n    WHERE\n        CASE WHEN day > ? THEN day/? ELSE day END < ?  -- rdar://145093387\n        AND gallery_id = ?"
- "    DELETE FROM tracked_shuffle_photos\n    WHERE\n        CASE WHEN day > ? THEN day/? ELSE day END < ?  -- rdar://145093387\n        AND shuffle_id = ?"
```
