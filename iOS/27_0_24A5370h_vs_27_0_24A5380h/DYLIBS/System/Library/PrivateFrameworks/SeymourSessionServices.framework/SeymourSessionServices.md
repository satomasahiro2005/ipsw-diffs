## SeymourSessionServices

> `/System/Library/PrivateFrameworks/SeymourSessionServices.framework/SeymourSessionServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b9620` | `0x1b9d44` | **`+0x724`** |
| `__DATA_DIRTY.__data` | `0x21f8` | `0x24f8` | **`+0x300`** |
| `__AUTH.__data` | `0x4d8` | `0x288` | **`-0x250`** |
| `__DATA.__bss` | `0x1cc0` | `0x1b40` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `0x280` | `0x400` | **`+0x180`** |
| `__DATA.__data` | `0x11e8` | `0x1148` | **`-0xa0`** |
| `__DATA.__common` | `0xe0` | `0x68` | **`-0x78`** |
| `__DATA_DIRTY.__common` | `0x260` | `0x2d8` | **`+0x78`** |
| `__AUTH.__objc_data` | `0xa0` | `0x50` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x4d0` | `0x520` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1ac6` | `0x1b0d` | **`+0x47`** |
| `__TEXT.__eh_frame` | `0xde1c` | `0xde4c` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x29e0` | `0x2a08` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x1b46` | `0x1b66` | **`+0x20`** |
| `__TEXT.__const` | `0x55e0` | `0x55f0` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x6b88` | `0x6b98` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x162c` | `0x1638` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x16a8` | `0x16a0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x250` | `0x258` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4228` | `0x4230` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x114c` | `0x1150` | **`+0x4`** |

### Other Changes

```diff

-2027.0.117.0.2
+2027.0.124.0.3

-  Functions: 2987
-  Symbols:   1151
+  Functions: 2986
+  Symbols:   1149
Symbols:
- _os_proc_available_memory
- _swift_release_x2
CStrings:
+ "[%{public}s] %{public}s begin footprint=%{public}fKB"
+ "handshakeWithParticipant(_:minimumRequiredVersion:)"
+ "handshakeWithParticipant(havingRole:minimumRequiredVersion:)"
+ "sendParticipantHandshake(to:participant:role:minimumRequiredVersion:timestampOffsetExchange:)"
- "[%{public}s] %{public}s begin mem=%{public}fKB"
- "handshakeWithParticipant(_:)"
- "handshakeWithParticipant(havingRole:)"
- "sendParticipantHandshake(to:participant:role:timestampOffsetExchange:)"
```
