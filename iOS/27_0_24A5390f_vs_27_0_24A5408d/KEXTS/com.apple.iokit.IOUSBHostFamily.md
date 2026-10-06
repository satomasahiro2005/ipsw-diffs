## com.apple.iokit.IOUSBHostFamily

> `com.apple.iokit.IOUSBHostFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x94240` | `0x947cc` | **`+0x58c`** |
| `__DATA_CONST.__kalloc_type` | `0x1b80` | `0x1d80` | **`+0x200`** |
| `__TEXT.__cstring` | `0xa25c` | `0xa2b9` | **`+0x5d`** |
| `__DATA_CONST.__const` | `0xc880` | `0xc8a8` | **`+0x28`** |
| `__TEXT.__os_log` | `0x85bf` | `0x85e3` | **`+0x24`** |

### Other Changes

```diff

-1617.0.9.0.0
-  Functions: 1974
+1617.0.12.0.0
+  Functions: 1977

-  CStrings:  1147
+  CStrings:  1151
CStrings:
+ "%s@%s: %s::%s: deferring power off\n"
+ "111"
+ "B16@?0^{OSSerialize=^^?i*III^{OSArray}^{OSArray}BB^v^v^{OSData}I}8"
+ "site.T"
+ "site.tPortTerminateServiceArguments"
- "B16@?0^{OSSerialize=^^?i*III^{OSArray}BB^v^v^{OSData}I}8"
```
