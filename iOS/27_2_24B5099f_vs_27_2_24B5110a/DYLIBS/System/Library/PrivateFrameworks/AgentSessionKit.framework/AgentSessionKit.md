## AgentSessionKit

> `/System/Library/PrivateFrameworks/AgentSessionKit.framework/AgentSessionKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92a50` | `0x958d4` | **`+0x2e84`** |
| `__DATA.__bss` | `0xd100` | `0xd410` | **`+0x310`** |
| `__TEXT.__const` | `0xbf5c` | `0xc15c` | **`+0x200`** |
| `__TEXT.__swift5_typeref` | `0x2742` | `0x2800` | **`+0xbe`** |
| `__TEXT.__swift5_capture` | `0xb14` | `0xa70` | **`-0xa4`** |
| `__TEXT.__swift5_reflstr` | `0x16f5` | `0x1785` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x1e88` | `0x1f10` | **`+0x88`** |
| `__TEXT.__cstring` | `0x1f1a` | `0x1f9a` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x63f0` | `0x6370` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x3b98` | `0x3c18` | **`+0x80`** |
| `__DATA.__data` | `0x1148` | `0x11c0` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x2d68` | `0x2ddc` | **`+0x74`** |
| `__TEXT.__oslogstring` | `0xb2c` | `0xb9c` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x83a8` | `0x8348` | **`-0x60`** |
| `__DATA_DIRTY.__data` | `0x2558` | `0x2598` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x27c` | `0x29c` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x4e4` | `0x500` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0xb50` | `0xb68` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xb34` | `0xb4c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x370` | `0x380` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x408` | `0x418` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0xa18` | `0xa20` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x328` | `0x330` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x204` | `0x20c` | **`+0x8`** |

### Other Changes

```diff

-297.12.0.1.2
+297.12.4.0.0

-  Functions: 6169
-  Symbols:   191
-  CStrings:  279
+  Functions: 6227
+  Symbols:   192
+  CStrings:  282
Symbols:
+ _swift_getKeyPath
+ _swift_readAtKeyPath
+ _swift_retain_x28
+ _swift_setAtWritableKeyPath
- _swift_asyncLet_begin
- _swift_asyncLet_finish
- _swift_asyncLet_get
CStrings:
+ "AgentEventUpdate.observationDidReset"
+ "AgentSessionStore failed to sync event forwarding: %{public}@"
+ "AgentSessionStore failed to sync session forwarding: %{public}@"
+ "AgentSessionStore not recovering forwarding: no consumer stream exists."
+ "AgentSessionStore not recovering forwarding: released, so the daemon is left to exit."
+ "AgentSessionStore release found the daemon already gone: %{public}@"
+ "AgentSessionUpdate.observationDidReset"
+ "observationDidReset"
+ "observationDidReset must not be sent over XPC"
- "AgentSessionStore failed to resubscribe to event updates: %@"
- "AgentSessionStore failed to resubscribe to session updates: %@"
- "Failed to subscribe to event updates: %s"
- "Failed to subscribe to session updates: %s"
- "Failed to unsubscribe from event updates: %s"
- "Failed to unsubscribe from session updates: %s"
```
