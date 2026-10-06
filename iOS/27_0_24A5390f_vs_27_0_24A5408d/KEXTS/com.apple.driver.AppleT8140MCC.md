## com.apple.driver.AppleT8140MCC

> `com.apple.driver.AppleT8140MCC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x5a3d` | `0x5ba5` | **`+0x168`** |
| `__TEXT_EXEC.__text` | `0x16894` | `0x169dc` | **`+0x148`** |
| `__TEXT.__os_log` | `0x2671` | `0x266f` | **`-0x2`** |

### Other Changes

```diff

-127.0.1.0.0
+127.0.3.0.0

-  CStrings:  921
+  CStrings:  926
Functions:
~ __ZN11MemCacheCIP5startEP9IOService : 4804 -> 5132
CStrings:
+ "\"%s: \" \"Per-die DCS channel count %u exceeds 32 bits\" @%s:%d"
+ "\"%s: \" \"Per-die dcs-channel-enable-mask 0x%llx has bits beyond dcsPerDie=%u\" @%s:%d"
+ "\"%s: \" \"Total DCS channel count %u exceeds width of _dcsChannelEnableMask\" @%s:%d"
+ "\"%s: \" \"dcs-count-per-amcc %u * amccsPerDie %u overflows uint32_t\" @%s:%d"
+ "\"%s: \" \"dcsPerDie %u * _dieNum %u overflows uint32_t\" @%s:%d"
+ "%s:%d: dcs-channel-enable-mask (per-die from EDT): 0x%llx\n\n"
+ "%s:%d: dcs-channel-enable-mask not in EDT; defaulting to 0x%llx\n"
+ "dcs-channel-enable-mask (per-die from EDT): 0x%llx\n"
+ "dcs-channel-enable-mask not in EDT; defaulting to 0x%llx"
- "%s:%d: dcs-channel-enable-mask is not set in EDT. Setting dcs channel mask to 0x%llx\n"
- "%s:%d: dcs-channel-enable-mask: 0x%llx\n\n"
- "dcs-channel-enable-mask is not set in EDT. Setting dcs channel mask to 0x%llx"
- "dcs-channel-enable-mask: 0x%llx\n"
```
