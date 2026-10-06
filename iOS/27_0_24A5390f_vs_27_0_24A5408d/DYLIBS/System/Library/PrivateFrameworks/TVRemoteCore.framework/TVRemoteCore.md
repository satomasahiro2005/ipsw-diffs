## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x487b4` | `0x48670` | **`-0x144`** |
| `__TEXT.__const` | `0x2a0` | `0x240` | **`-0x60`** |
| `__TEXT.__cstring` | `0x3784` | `0x372c` | **`-0x58`** |
| `__TEXT.__oslogstring` | `0x6b4c` | `0x6b90` | **`+0x44`** |
| `__AUTH_CONST.__cfstring` | `0x4aa0` | `0x4a60` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0xafc` | `0xb14` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x120` | `0x110` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x64e0` | `0x64d0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3098` | `0x3090` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1218` | `0x1210` | **`-0x8`** |

### Other Changes

```diff

-627.0.19.0.0
+627.0.28.0.0

-  Functions: 2138
-  Symbols:   3705
-  CStrings:  1301
+  Functions: 2139
+  Symbols:   3704
+  CStrings:  1299
Symbols:
+ -[TVRCRPCompanionLinkClientWrapper _toggleCaptions:completion:]
+ GCC_except_table103
+ GCC_except_table113
+ GCC_except_table118
+ GCC_except_table123
+ GCC_except_table129
+ GCC_except_table133
+ GCC_except_table140
+ GCC_except_table145
+ GCC_except_table35
+ GCC_except_table40
+ GCC_except_table87
+ GCC_except_table90
+ GCC_except_table97
+ ___63-[TVRCRPCompanionLinkClientWrapper _toggleCaptions:completion:]_block_invoke
- -[TVRCMediaEventsManager supportedCaptionEvents]
- -[TVRCRPCompanionLinkClientWrapper toggleCaptions:]
- -[TVRCRapportMediaEventsManager supportedCaptionEvents]
- GCC_except_table101
- GCC_except_table111
- GCC_except_table116
- GCC_except_table121
- GCC_except_table127
- GCC_except_table131
- GCC_except_table138
- GCC_except_table143
- GCC_except_table34
- GCC_except_table39
- GCC_except_table77
- GCC_except_table88
- GCC_except_table91
CStrings:
+ "Caption toggle send failed. error=%{public}@"
+ "Ignoring caption toggle event; current caption state is unknown. %@"
+ "toggleCaptions to: %{public,bool}d; %@"
- "%s: %{public,bool}d %@"
- "-[TVRCRPCompanionLinkClientWrapper toggleCaptions:]"
- "CaptionsAlwaysOn"
- "CaptionsForcedOnly"
- "Supported Caption Events for current settings=%s, events=\n%@"
```
