## IMDaemonCore

> `/System/Library/PrivateFrameworks/IMDaemonCore.framework/IMDaemonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c7708` | `0x3c79f4` | **`+0x2ec`** |
| `__TEXT.__oslogstring` | `0x55c42` | `0x55d42` | **`+0x100`** |
| `__TEXT.__gcc_except_tab` | `0x1faac` | `0x1facc` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x113e0` | `0x113f0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3920` | `0x3928` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 15253
-  Symbols:   3304
-  CStrings:  8576
+  Functions: 15255
+  Symbols:   3305
+  CStrings:  8579
Symbols:
+ _OBJC_CLASS_$_IMIDSUtilities
CStrings:
+ "%s fromID %@ doesn't match supplied account (matchStatus: 0x%X), checking all gelato accounts"
+ "%s: Dropping receive notice action. Sender is not one of our accounts (matchStatus: 0x%X, fromHandle: %@)"
+ "%s: message matches one of our accounts, processing"
```
