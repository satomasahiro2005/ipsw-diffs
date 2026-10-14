## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c7ad0` | `0x3c7708` | **`-0x3c8`** |
| `__TEXT.__gcc_except_tab` | `0x1fb14` | `0x1faac` | **`-0x68`** |
| `__TEXT.__oslogstring` | `0x55c62` | `0x55c42` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1d92c` | `0x1d93c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3918` | `0x3920` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x113d8` | `0x113e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe510` | `0xe518` | **`+0x8`** |

### Other Changes

```diff

-1491.200.95.0.0
+1491.200.101.2.5

-  Functions: 15252
-  Symbols:   3303
+  Functions: 15253
+  Symbols:   3304
Symbols:
+ _IMChatPropertyPromotedToKnownByReply
CStrings:
+ "Not re-originating group name change %{public}@, chat already has this name"
- "Muted state inconsistency detected among merged chats. Muting %lu additional identifier(s) until %@"
```
