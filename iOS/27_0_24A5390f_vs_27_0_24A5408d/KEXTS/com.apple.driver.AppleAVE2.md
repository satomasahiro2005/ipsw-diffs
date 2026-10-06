## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1cd2a0` | `0x1cdec0` | **`+0xc20`** |
| `__TEXT.__os_log` | `0x5c7be` | `0x5cabd` | **`+0x2ff`** |
| `__TEXT.__cstring` | `0x47f24` | `0x4804a` | **`+0x126`** |
| `__TEXT.__const` | `0x4b680` | `0x4b6f0` | **`+0x70`** |

### Other Changes

```diff

-913.29.1.0.0
-  Functions: 2994
+913.43.1.0.0
+  Functions: 2995

-  CStrings:  9847
+  CStrings:  9867
CStrings:
+ "%lld %d AVE %s: %p %lld MCTFGatingType %d"
+ "%lld %d AVE %s: %p %lld MCTFGatingType %d\n"
+ "%lld %d AVE %s: %p %lld MCTFPreFiltAdjType %d"
+ "%lld %d AVE %s: %p %lld MCTFPreFiltAdjType %d\n"
+ "%lld %d AVE %s: %p MCTFFnumChangeResetMCTF %d"
+ "%lld %d AVE %s: %p MCTFFnumChangeResetMCTF %d\n"
+ "%lld %d AVE %s: %p MCTFGatingType %d"
+ "%lld %d AVE %s: %p MCTFGatingType %d\n"
+ "%lld %d AVE %s: %p MCTFPreFiltAdjType %d"
+ "%lld %d AVE %s: %p MCTFPreFiltAdjType %d\n"
+ "%p %lld MCTFGatingType %d"
+ "%p %lld MCTFGatingType %d\n"
+ "%p %lld MCTFPreFiltAdjType %d"
+ "%p %lld MCTFPreFiltAdjType %d\n"
+ "%p MCTFFnumChangeResetMCTF %d"
+ "%p MCTFFnumChangeResetMCTF %d\n"
+ "%p MCTFGatingType %d"
+ "%p MCTFGatingType %d\n"
+ "%p MCTFPreFiltAdjType %d"
+ "%p MCTFPreFiltAdjType %d\n"
+ "21:52:03"
+ "913.43.1"
+ "AVE_SVESched_ClearOrder"
+ "Aug  5 2026"
- "21:36:33"
- "913.29.1"
- "Jul 14 2026"
- "pCHM != nullptr && pSurface != nullptr && pSize != nullptr && psCBufInfo != nullptr"
```
