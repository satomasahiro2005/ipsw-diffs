## com.apple.driver.AudioDMAFamily

> `com.apple.driver.AudioDMAFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x200` | **`+0x200`** |
| `__TEXT_EXEC.__text` | `0x58c0` | `0x58e8` | **`+0x28`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ __ZN17AudioDMAEvolution20ADMAChannelInterface5startEP9IOService : 3512 -> 3516
~ ____ZN17AudioDMAEvolution20ADMAChannelInterface25setAudioStreamDescriptionERNS_20ChannelConfiguration6StreamE_block_invoke : 1024 -> 1028
~ __ZNK17AudioDMAEvolution20ADMAChannelInterface28translateStreamConfigurationERKNS_20ChannelConfiguration6StreamEPS1_ : 920 -> 924
~ __ZN17AudioDMAEvolution22fetchIndexAndDirectionEP15IORegistryEntryPNS_24ADMAChannelInterfaceImplEb : 428 -> 456
CStrings:
+ "19:55:59"
+ "Jun 18 2026"
- "02:47:27"
- "Jun  5 2026"
```
