## MessagesViewService

> `/Applications/MessagesViewService.app/MessagesViewService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a0` | `0x1ec` | **`+0x4c`** |
| `__TEXT.__auth_stubs` | `0xf0` | `0x120` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x40` | `0x60` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x80` | `0x98` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x28` | `0x30` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 3
-  Symbols:   28
+  Functions: 4
+  Symbols:   32
Symbols:
+ _OBJC_CLASS_$_IMBalloonPluginManager
+ _dispatch_async
+ _dispatch_get_global_queue
+ _objc_unsafeClaimAutoreleasedReturnValue
Functions:
~ sub_100000c20 : 184 -> 220
+ sub_100000d44
```
