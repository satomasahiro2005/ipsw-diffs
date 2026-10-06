## AccessibilityUIService

> `/System/Library/PrivateFrameworks/AccessibilityUIService.framework/AccessibilityUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1eb2c` | `0x1f2e4` | **`+0x7b8`** |
| `__AUTH.__objc_data` | `0x530` | `0x260` | **`-0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0x370` | `0x640` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x1216` | `0x13c4` | **`+0x1ae`** |
| `__TEXT.__objc_methlist` | `0x1bec` | `0x1c04` | **`+0x18`** |
| `__DATA.__bss` | `0x920` | `0x910` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x4f8` | `0x508` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1858` | `0x1868` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x38` | `0x48` | **`+0x10`** |
| `__TEXT.__const` | `0x840` | `0x850` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x898` | `0x8a8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x880` | `0x888` | **`+0x8`** |

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

-  Functions: 735
-  Symbols:   1462
-  CStrings:  212
+  Functions: 739
+  Symbols:   1469
+  CStrings:  216
Symbols:
+ -[AXUIDisplayManager _attemptFlushOfQueuedAddBlocksForSceneClientIdentifier:requireActiveScene:]
+ -[AXUIDisplayManager _postAccessibilityShortcutBannerWithTitle:subtitleText:]
+ GCC_except_table418
+ GCC_except_table435
+ _AXProcessIsSpringBoard
+ _AXSpringBoardActionKeyAccessibilityShortcutBannerSubtitle
+ _AXSpringBoardActionKeyAccessibilityShortcutBannerTitle
+ ___77-[AXUIDisplayManager _postAccessibilityShortcutBannerWithTitle:subtitleText:]_block_invoke
+ ___96-[AXUIDisplayManager _attemptFlushOfQueuedAddBlocksForSceneClientIdentifier:requireActiveScene:]_block_invoke
- GCC_except_table414
- GCC_except_table431
CStrings:
+ "Deferring add-block flush for client '%{public}@' — %lu queued, no active scene yet (best scene: %p, activationState: %ld)"
+ "Fallback flush timer fired for client '%{public}@' but blocks already drained (likely by activation early-flush)"
+ "Fallback flush timer fired for client '%{public}@' — flushing %lu queued block(s) without active scene check"
+ "Flushing %lu queued add block(s) for client '%{public}@' (requireActiveScene=%d)"
```
