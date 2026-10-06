## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1c6a50` | `0x1c9b10` | **`+0x30c0`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x7b0` | **`+0x7b0`** |
| `__TEXT.__os_log` | `0x5b67f` | `0x5bc39` | **`+0x5ba`** |
| `__TEXT.__cstring` | `0x46e4a` | `0x4736f` | **`+0x525`** |
| `__TEXT.__const` | `0x4b240` | `0x4b760` | **`+0x520`** |
| `__DATA_CONST.__const` | `0xaff0` | `0xb020` | **`+0x30`** |

### Other Changes

```diff

-912.89.1.0.0
+913.8.0.0.0

-  CStrings:  9727
+  CStrings:  9759
CStrings:
+ "%lld %d AVE %s: %p %lld MCTFEnableFeedback %d"
+ "%lld %d AVE %s: %p %lld MCTFEnableFeedback %d\n"
+ "%lld %d AVE %s: %p %lld MCTFEnableGating %d"
+ "%lld %d AVE %s: %p %lld MCTFEnableGating %d\n"
+ "%lld %d AVE %s: %p MCTFEnableFeedback %d"
+ "%lld %d AVE %s: %p MCTFEnableFeedback %d\n"
+ "%lld %d AVE %s: %p MCTFEnableGating %d"
+ "%lld %d AVE %s: %p MCTFEnableGating %d\n"
+ "%lld %d AVE %s: %s:%d %s | invalid DMV2 HiRes compressed input %p %d %p %lld | 0x%llx %d"
+ "%lld %d AVE %s: %s:%d %s | invalid DMV2 HiRes compressed input %p %d %p %lld | 0x%llx %d\n"
+ "%lld %d AVE %s: %s:%d %s | invalid DMV2 HiRes linear %p %d %p %lld | 0x%llx 0x%llx %d %d"
+ "%lld %d AVE %s: %s:%d %s | invalid DMV2 HiRes linear %p %d %p %lld | 0x%llx 0x%llx %d %d\n"
+ "%lld %d AVE %s: %s:%d %s | invalid DMV2 LoRes compressed input %p %d %p %lld | 0x%llx %d"
+ "%lld %d AVE %s: %s:%d %s | invalid DMV2 LoRes compressed input %p %d %p %lld | 0x%llx %d\n"
+ "%lld %d AVE %s: %s:%d %s | invalid DMV2 LoRes linear %p %d %p %lld | 0x%llx 0x%llx %d %d"
+ "%lld %d AVE %s: %s:%d %s | invalid DMV2 LoRes linear %p %d %p %lld | 0x%llx 0x%llx %d %d\n"
+ "%lld %d AVE %s: %s:%d DMV2 HiResInput %p %d %lld %p %lld | compress=%d"
+ "%lld %d AVE %s: %s:%d DMV2 HiResInput %p %d %lld %p %lld | compress=%d\n"
+ "%lld %d AVE %s: %s:%d DMV2 LoResInput %p %d %lld %p %lld | compress=%d"
+ "%lld %d AVE %s: %s:%d DMV2 LoResInput %p %d %lld %p %lld | compress=%d\n"
+ "%p %lld MCTFEnableFeedback %d"
+ "%p %lld MCTFEnableFeedback %d\n"
+ "%p %lld MCTFEnableGating %d"
+ "%p %lld MCTFEnableGating %d\n"
+ "%p MCTFEnableFeedback %d"
+ "%p MCTFEnableFeedback %d\n"
+ "%p MCTFEnableGating %d"
+ "%p MCTFEnableGating %d\n"
+ "111211111111111111122222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222121222222222222222222222222222222222222222222222222222222222222222222"
+ "19:40:52"
+ "913.8.0"
+ "DMVHiResInput"
+ "DMVLoResInput"
+ "Jun 18 2026"
+ "pComp->saCPBuf[AVE_BufIdx_Luma].sCIBuf.saIBuf[AVE_BufIdx_Data].iAddr != 0 && pComp->saCPBuf[AVE_BufIdx_Luma].sCPInfo.iHeaderStride != 0"
+ "pLin->saCIBuf[AVE_BufIdx_Luma].saIBuf[AVE_BufIdx_Data].iAddr != 0 && pLin->saCIBuf[AVE_BufIdx_Luma].saIBuf[AVE_BufIdx_Data].iSize != 0 && pLin->saCIBuf[AVE_BufIdx_Luma].saIBuf[AVE_BufIdx_Data].iStride != 0 && (pLin->saCIBuf[AVE_BufIdx_Luma].saIBuf[AVE_BufIdx_Data].iStride % 64 == 0) && (pLin->saCIBuf[AVE_BufIdx_Chroma].saIBuf[AVE_BufIdx_Data].iStride % 64 == 0)"
- "1112111111111111122222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222121222222222222222222222222222222222222222222222222222222222222222222"
- "21:27:09"
- "912.89.1"
- "Jun  1 2026"
```
