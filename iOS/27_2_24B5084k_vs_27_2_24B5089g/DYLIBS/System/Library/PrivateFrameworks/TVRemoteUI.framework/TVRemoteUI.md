## TVRemoteUI

> `/System/Library/PrivateFrameworks/TVRemoteUI.framework/TVRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd5274` | `0xd5448` | **`+0x1d4`** |
| `__DATA_CONST.__objc_selrefs` | `0x6c80` | `0x6c90` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe30` | `0xe38` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2d40` | `0x2d48` | **`+0x8`** |

### Other Changes

```diff

-627.10.45.0.0
+627.10.47.0.0

-  Symbols:   7116
+  Symbols:   7117
Symbols:
+ -[TVRAlertController initForTextPasswordType:styleProvider:]
+ _OBJC_CLASS_$_UIViewReservedRegionKind
- -[TVRAlertController initForTextPasswordType:]
Functions:
~ -[TVRAlertController initForTextPasswordType:] -> -[TVRAlertController initForTextPasswordType:styleProvider:] : 320 -> 352
~ -[TVRUINowPlayingViewController _computeAndApplyLayout] : 2036 -> 2020
~ -[TVRUIRemoteViewController _presentTextPasswordAlert] : 280 -> 312
~ -[TVRUIResizabilityLayoutManager _occlusionRegionFrame] : 20 -> 440
```
