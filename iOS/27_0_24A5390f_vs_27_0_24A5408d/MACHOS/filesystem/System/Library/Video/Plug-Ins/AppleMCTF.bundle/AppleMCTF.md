## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/AppleMCTF`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x86914` | `0x87bb0` | **`+0x129c`** |
| `__TEXT.__cstring` | `0x2837c` | `0x286c9` | **`+0x34d`** |
| `__DATA_CONST.__const` | `0x53b0` | `0x5430` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x940` | `0x980` | **`+0x40`** |
| `__TEXT.__const` | `0x22a08` | `0x229e8` | **`-0x20`** |
| `__DATA.__bss` | `0x8d0` | `0x8d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-913.29.1.0.0
+913.43.1.0.0

-  Functions: 668
+  Functions: 672

-  CStrings:  3427
+  CStrings:  3444
CStrings:
+ "%lld %d AVE %s: %s Enter %d %d %p %d %d %d %p"
+ "%lld %d AVE %s: %s Enter %d %d %p %d %d %d %p\n"
+ "%lld %d AVE %s: %s Exit %d %d %p %d %d %d %p %d"
+ "%lld %d AVE %s: %s Exit %d %d %p %d %d %d %p %d\n"
+ "%lld %d AVE %s: %s fNumberChange: %.4f (%d) ->%.4f (%d), sID : %d -> %d DynamicStrength:0"
+ "%lld %d AVE %s: %s fNumberChange: %.4f (%d) ->%.4f (%d), sID : %d -> %d DynamicStrength:0\n"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x gMode %d lMode %d gating type %d"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x gMode %d lMode %d gating type %d\n"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x gMode %d lMode %d prefilt adj type %d"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x gMode %d lMode %d prefilt adj type %d\n"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x noise level %d rIdx %d/%d strength %d"
+ "%lld %d AVE %s: %s:%d %p sID 0x%x noise level %d rIdx %d/%d strength %d\n"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_DecideGatingType failed %p %p %lld %d"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_DecideGatingType failed %p %p %lld %d\n"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_DecidePreFiltAdjType failed %p %p %lld %d"
+ "%lld %d AVE %s: %s:%d %s | AVE_MCTF_DecidePreFiltAdjType failed %p %p %lld %d\n"
+ "%lld %d AVE %s: %s:%d %s | wrong params, %d %d %p %d %d %d"
+ "%lld %d AVE %s: %s:%d %s | wrong params, %d %d %p %d %d %d\n"
+ "%lld %d AVE %s: %s:%d %s | wrong params, %d %p %d %d %d"
+ "%lld %d AVE %s: %s:%d %s | wrong params, %d %p %d %d %d\n"
+ "%lld %d AVE %s: fail to send PS %p %p %d, dropping frame"
+ "%lld %d AVE %s: fail to send PS %p %p %d, dropping frame\n"
+ "21:54:42"
+ "913.43.1"
+ "AVE_MCTFFnumChangeResetMCTF"
+ "AVE_MCTFGatingType"
+ "AVE_MCTFPreFiltAdjType"
+ "AVE_MCTF_DecideGatingType"
+ "AVE_MCTF_DecidePreFiltAdjType"
+ "AVE_PROPERTY_KEY_MCTF_GATING_TYPE"
+ "AVE_PROPERTY_KEY_MCTF_PRE_FILT_ADJ_TYPE"
+ "AVE_Prop_MCTF_GetMCTFGatingType"
+ "AVE_Prop_MCTF_GetMCTFPreFiltAdjType"
+ "AVE_Prop_MCTF_SetMCTFGatingType"
+ "AVE_Prop_MCTF_SetMCTFPreFiltAdjType"
+ "Aug  5 2026"
+ "MCTFGatingType"
+ "MCTFGatingType = %d\n"
+ "MCTFPreFiltAdjType"
+ "MCTFPreFiltAdjType = %d\n"
+ "iGatingType >= -1 && iGatingType < AVE_MCTF_GatingType_Max"
+ "iPreFiltAdjType >= -1 && iPreFiltAdjType < AVE_MCTF_PreFiltAdjType_Max"
+ "psData != __null && eDevType > AVE_DevType_None && eDevType < AVE_DevType_Max && eWorkMode > AVE_MCTF_WorkMode_None && eWorkMode < AVE_MCTF_WorkMode_Max && eLatencyMode > AVE_MCTF_Mode_Invalid && eLatencyMode < AVE_MCTF_Mode_Max && peGatingType != __null"
- "%lld %d AVE %s: %s Enter %p %d %d %d %p"
- "%lld %d AVE %s: %s Enter %p %d %d %d %p\n"
- "%lld %d AVE %s: %s Exit %p %d %d %d %p %d"
- "%lld %d AVE %s: %s Exit %p %d %d %d %p %d\n"
- "%lld %d AVE %s: %s:%d %p sID 0x%x gating type %d"
- "%lld %d AVE %s: %s:%d %p sID 0x%x gating type %d\n"
- "%lld %d AVE %s: %s:%d %p sID 0x%x noise level %d rIdx %d/%d s %d"
- "%lld %d AVE %s: %s:%d %p sID 0x%x noise level %d rIdx %d/%d s %d\n"
- "%lld %d AVE %s: %s:%d %p sID 0x%x prefilt adj type %d"
- "%lld %d AVE %s: %s:%d %p sID 0x%x prefilt adj type %d\n"
- "%lld %d AVE %s: %s:%d %s | AVE_MCTF_GetGatingType failed %p %p %lld %d"
- "%lld %d AVE %s: %s:%d %s | AVE_MCTF_GetGatingType failed %p %p %lld %d\n"
- "%lld %d AVE %s: %s:%d %s | AVE_MCTF_GetPreFiltAdjType failed %p %p %lld %d"
- "%lld %d AVE %s: %s:%d %s | AVE_MCTF_GetPreFiltAdjType failed %p %p %lld %d\n"
- "%lld %d AVE %s: %s:%d %s | wrong params, %p %d %d %d"
- "%lld %d AVE %s: %s:%d %s | wrong params, %p %d %d %d\n"
- "%lld %d AVE %s: %s:%d %s | wrong params, %p %d %d %d %p"
- "%lld %d AVE %s: %s:%d %s | wrong params, %p %d %d %d %p\n"
- "%lld %d AVE %s: %s::%s:%d %s | fail to send PS %p %p"
- "%lld %d AVE %s: %s::%s:%d %s | fail to send PS %p %p\n"
- "21:39:53"
- "913.29.1"
- "AVE_MCTF_GetGatingType"
- "AVE_MCTF_GetPreFiltAdjType"
- "Jul 14 2026"
- "psData != __null && eDevType > AVE_DevType_None && eDevType < AVE_DevType_Max && eWorkMode > AVE_MCTF_WorkMode_None && eWorkMode < AVE_MCTF_WorkMode_Max && eLatencyMode > AVE_MCTF_Mode_Invalid && eLatencyMode < AVE_MCTF_Mode_Max"
```
