## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/AVConference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e6e00` | `0x7e6df4` | **`-0xc`** |
| `__TEXT.__oslogstring` | `0x144e5d` | `0x144e55` | **`-0x8`** |

### Other Changes

```diff
Functions:
~ ___48-[VCMediaStreamManager registerBlocksForService]_block_invoke.289 : 524 -> 548
~ -[VCSwitchManager initializeLocalSwitches] : 704 -> 668
CStrings:
+ " [%s] %s:%d SwitchManager: Non-seed build - using master local switch: %08X"
- " [%s] %s:%d SwitchManager: A/B testing turned off - using master local switch: %08X"
```
