## IMAP

> `/System/Library/PrivateFrameworks/VisualVoicemail.framework/IMAP.framework/IMAP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1540` | `0x1360` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x15e0` | `0x17c0` | **`+0x1e0`** |
| `__DATA.__bss` | `0x350` | `0x278` | **`-0xd8`** |
| `__DATA_DIRTY.__bss` | `0x190` | `0x250` | **`+0xc0`** |
| `__DATA_DIRTY.__data` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__text` | `0xb123c` | `0xb1244` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x43a0` | `0x43a8` | **`+0x8`** |

### Other Changes

```diff

-952.0.0.0.0
+954.0.0.0.0
Functions:
~ -[MFMimeEnrichedReader beginCommand:] : 432 -> 440
~ -[MFMimeEnrichedReader endCommand:] : 224 -> 220
~ -[MFIMAPConnection _readDataOfLength:] : 340 -> 336
~ -[IMAP_Account setStoreMailboxType:onServer:] : 252 -> 260
~ _IMAPMessageFlagsFromArray : 472 -> 476
~ __ZL15status_responseP18MFIMAPParseContext : 944 -> 952
~ __ZL13list_responseP18MFIMAPParseContext : 696 -> 692
~ __ZL14fetch_responseP18MFIMAPParseContext : 3580 -> 3584
~ __ZNSt3__16vectorI21IMAPCommandParametersNS_9allocatorIS1_EEE22__base_destruct_at_endB9fqe220106EPS1_ : 96 -> 84
```
