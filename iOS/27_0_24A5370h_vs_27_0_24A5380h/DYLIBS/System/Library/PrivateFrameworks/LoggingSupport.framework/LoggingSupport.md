## LoggingSupport

> `/System/Library/PrivateFrameworks/LoggingSupport.framework/LoggingSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6391c` | `0x63870` | **`-0xac`** |
| `__DATA_CONST.__got` | `0x308` | `0x330` | **`+0x28`** |
| `__DATA.__bss` | `0x268` | `0x258` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0xd0` | `0xe0` | **`+0x10`** |
| `__TEXT.__const` | `0x586` | `0x576` | **`-0x10`** |

### Other Changes

```diff

-1958.0.0.0.1
+1965.0.0.0.0
Functions:
~ _os_trace_blob_add_unsafe_bytes : 1016 -> 1020
~ __timesync_repair : 1088 -> 1064
~ ___OTRStartLegacyStreaming_block_invoke : 900 -> 904
~ _ctf_lookup_by_name : 744 -> 688
~ __ctf_member_info : 1076 -> 1024
~ _ctf_enum_name : 356 -> 348
~ _ctf_type_rvisit : 980 -> 940
```
