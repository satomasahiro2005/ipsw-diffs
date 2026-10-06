## IMCore

> `/System/Library/PrivateFrameworks/IMCore.framework/IMCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fd5d4` | `0x2fde34` | **`+0x860`** |
| `__AUTH.__objc_data` | `0x4110` | `0x4700` | **`+0x5f0`** |
| `__DATA_DIRTY.__objc_data` | `0x1e38` | `0x1848` | **`-0x5f0`** |
| `__TEXT.__oslogstring` | `0x23dbb` | `0x2409b` | **`+0x2e0`** |
| `__DATA_DIRTY.__data` | `0x3f8` | `0x298` | **`-0x160`** |
| `__AUTH.__data` | `0x2d20` | `0x2e40` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x11928` | `0x1196c` | **`+0x44`** |
| `__DATA_DIRTY.__bss` | `0x348` | `0x310` | **`-0x38`** |
| `__DATA.__bss` | `0x1e870` | `0x1e8a0` | **`+0x30`** |
| `__DATA.__data` | `0x65b8` | `0x65e0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x72c0` | `0x72e8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xc348` | `0xc358` | **`+0x10`** |

### Other Changes

```diff

-1491.200.63.2.1
+1491.200.73.0.0

-  Functions: 15190
+  Functions: 15196

-  CStrings:  5014
+  CStrings:  5024
CStrings:
+ "Attempting to update display name for chat GUID: %@"
+ "Chat %p is not registered under any GUID; attempting to send display name update to %@ rather than dropping it"
+ "Ignoring group identity update for chat guid: %@"
+ "Skipping display name update: chat style %ld does not allow rename (not business/Stewie/RCS) name=%@"
+ "Skipping display name update: current chat has no name and the incoming name is empty/whitespace."
+ "Skipping display name update: string-equal to current name %@"
+ "Skipping display name update: unchanged (name=%@ style=%ld)"
+ "Suppressing group-title breadcrumb (coalesced): title=%@ prevTitle=%@ sender=%@"
+ "We found fallback chat guids: %@"
+ "We have attempted to re-find the current chat but were unable to. Failed to set display name."
```
