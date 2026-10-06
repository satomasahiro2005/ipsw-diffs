## HybridSearch

> `/System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x489850` | `0x48f650` | **`+0x5e00`** |
| `__DATA.__bss` | `0x8c520` | `0x8d3a0` | **`+0xe80`** |
| `__TEXT.__unwind_info` | `0x14b48` | `0x13e00` | **`-0xd48`** |
| `__TEXT.__const` | `0x51870` | `0x520d0` | **`+0x860`** |
| `__AUTH_CONST.__const` | `0x400f0` | `0x40578` | **`+0x488`** |
| `__TEXT.__oslogstring` | `0x1c4e` | `0x1e5e` | **`+0x210`** |
| `__TEXT.__swift5_typeref` | `0x10e76` | `0x1106c` | **`+0x1f6`** |
| `__TEXT.__eh_frame` | `0x1c5a4` | `0x1c78c` | **`+0x1e8`** |
| `__DATA.__data` | `0xfdf8` | `0xff68` | **`+0x170`** |
| `__TEXT.__swift5_fieldmd` | `0x174ec` | `0x17620` | **`+0x134`** |
| `__TEXT.__constg_swiftt` | `0xc530` | `0xc638` | **`+0x108`** |
| `__TEXT.__swift5_assocty` | `0x5ba0` | `0x5c70` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x13864` | `0x13924` | **`+0xc0`** |
| `__TEXT.__swift5_proto` | `0x48ec` | `0x4964` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x15b8` | `0x1608` | **`+0x50`** |
| `__TEXT.__cstring` | `0x6fb3` | `0x7003` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x4768` | `0x47b4` | **`+0x4c`** |
| `__DATA_CONST.__got` | `0x648` | `0x690` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x530` | `0x550` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x13d4` | `0x13f0` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0xd64` | `0xd74` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x83c` | `0x84c` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x7f8` | `0x804` | **`+0xc`** |
| `__AUTH.__data` | `0xc708` | `0xc700` | **`-0x8`** |

### Other Changes

```diff

-62.1.0.0.0
+67.0.0.0.0

-  Functions: 34284
-  Symbols:   279
-  CStrings:  1112
+  Functions: 34501
+  Symbols:   280
+  CStrings:  1121
Symbols:
+ _OBJC_CLASS_$_NSPersonNameComponentsFormatter
+ _swift_unknownObjectRetain_n
- _swift_release_x11
CStrings:
+ "ActivationGatedLiveQueryTrigger activation changed to %{public}s"
+ "ActivationGatedLiveQueryTrigger activation stream ended"
+ "ActivationGatedLiveQueryTrigger flushing pending event on activation"
+ "ActivationGatedLiveQueryTrigger started"
+ "ActivationGatedLiveQueryTrigger suppressing event while inactive"
+ "ActivationGatedLiveQueryTrigger terminated"
+ "ActivationGatedLiveQueryTrigger wrapped stream ended"
+ "CoalescingLiveQueryTrigger sleeping for cooldown %{public}s"
+ "CoalescingLiveQueryTrigger started with dynamic cooldown"
+ "Down-casted Array element failed to match the target type\nExpected "
- "CoalescingLiveQueryTrigger started with cooldown %{public}s"
```
