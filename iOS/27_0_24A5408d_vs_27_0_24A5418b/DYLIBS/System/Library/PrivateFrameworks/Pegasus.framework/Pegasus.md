## Pegasus

> `/System/Library/PrivateFrameworks/Pegasus.framework/Pegasus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4404c` | `0x44284` | **`+0x238`** |
| `__AUTH_CONST.__objc_const` | `0xada0` | `0xadd0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1c60` | `0x1c88` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x4674` | `0x469c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d30` | `0x2d48` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x5e4` | `0x5e8` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-310.0.0.0.0
+310.100.0.0.0

-  Functions: 1764
-  Symbols:   3167
+  Functions: 1768
+  Symbols:   3174
Symbols:
+ -[PGButtonGroupView _shouldHitTest]
+ -[PGPictureInPictureViewController hostedContentSizeOverride]
+ -[PGPictureInPictureViewController setHostedContentSizeOverride:]
+ GCC_except_table5
+ _OBJC_IVAR_$_PGPictureInPictureViewController._hostedContentSizeOverride
+ ___58-[PGPictureInPictureViewController viewWillLayoutSubviews]_block_invoke
+ ___block_descriptor_88_e8_32s_e5_v8?0ls32l8
```
