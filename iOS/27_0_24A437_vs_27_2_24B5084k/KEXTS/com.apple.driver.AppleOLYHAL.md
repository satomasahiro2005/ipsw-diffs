## com.apple.driver.AppleOLYHAL

> `com.apple.driver.AppleOLYHAL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1e000` | `0x1df60` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x4ee4` | `0x4f28` | **`+0x44`** |

### Other Changes

```diff

-530.9.4.2.0
+536.4.0.0.0

-  CStrings:  531
+  CStrings:  532
CStrings:
+ "%s::%s: Dext is unavailable. skip PreparePCIeError\n"
+ "%s::%s: Recovering dext crash (FLR: %u, 0x%08x, %p)\n"
+ "%s::%s: allowing external full reset to proceed with missing wifi dext\n"
- "%s::%s: Dext recovery is paused. skip PreparePCIeError\n"
- "%s::%s: Recovering dext crash (FLR: %u, 0x%08x, %p\n)"
```
