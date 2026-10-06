## livefiles_hfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_hfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d360` | `0x3d480` | **`+0x120`** |
| `__TEXT.__cstring` | `0x26fb` | `0x270a` | **`+0xf`** |
| `__TEXT.__oslogstring` | `0x5ecc` | `0x5ed7` | **`+0xb`** |

### Other Changes

```diff

-750.0.0.0.0
+751.0.0.0.0

-  CStrings:  747
+  CStrings:  751
Functions:
~ _replay_journal : 6220 -> 6368
~ _HeadTruncateFile : 1300 -> 1440
CStrings:
+ "\n"
+ "%s"
+ "0x%.8x"
+ "HeadTruncateFile: too many tail extents, marking volume inconsistent.\n"
+ "jnl: "
- "jnl: 0x%.8x 0x%.8x 0x%.8x 0x%.8x  0x%.8x 0x%.8x 0x%.8x 0x%.8x\n"
```
