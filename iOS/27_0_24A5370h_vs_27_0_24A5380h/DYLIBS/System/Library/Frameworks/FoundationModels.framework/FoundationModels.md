## FoundationModels

> `/System/Library/Frameworks/FoundationModels.framework/FoundationModels`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x2218` | `0x4bb0` | **`+0x2998`** |
| `__AUTH.__data` | `0x47b0` | `0x2b98` | **`-0x1c18`** |
| `__TEXT.__text` | `0x205664` | `0x206c34` | **`+0x15d0`** |
| `__DATA_DIRTY.__bss` | `0x1100` | `0x2200` | **`+0x1100`** |
| `__TEXT.__const` | `0x1ce82` | `0x1db22` | **`+0xca0`** |
| `__DATA.__data` | `0x5088` | `0x4860` | **`-0x828`** |
| `__AUTH_CONST.__const` | `0x154f8` | `0x15ac8` | **`+0x5d0`** |
| `__AUTH.__objc_data` | `0x410` | `0x90` | **`-0x380`** |
| `__DATA_DIRTY.__objc_data` | `0x190` | `0x510` | **`+0x380`** |
| `__TEXT.__swift5_fieldmd` | `0x88f0` | `0x8c10` | **`+0x320`** |
| `__TEXT.__swift5_capture` | `0x1258` | `0xfec` | **`-0x26c`** |
| `__TEXT.__constg_swiftt` | `0x7c68` | `0x7e84` | **`+0x21c`** |
| `__TEXT.__eh_frame` | `0xeb10` | `0xe988` | **`-0x188`** |
| `__DATA.__common` | `0x2a0` | `0x180` | **`-0x120`** |
| `__DATA_DIRTY.__common` | `0x78` | `0x188` | **`+0x110`** |
| `__TEXT.__swift5_assocty` | `0x1468` | `0x1570` | **`+0x108`** |
| `__TEXT.__swift5_reflstr` | `0x5676` | `0x5776` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x77c0` | `0x7870` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x27e0` | `0x2880` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x6e6e` | `0x6f0a` | **`+0x9c`** |
| `__TEXT.__swift5_proto` | `0x1468` | `0x14fc` | **`+0x94`** |
| `__TEXT.__cstring` | `0x5bcb` | `0x5b3b` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x1d5c` | `0x1dec` | **`+0x90`** |
| `__DATA.__bss` | `0x22820` | `0x22890` | **`+0x70`** |
| `__TEXT.__swift5_types` | `0xab4` | `0xafc` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x1fc8` | `0x1f88` | **`-0x40`** |
| `__TEXT.__swift5_mpenum` | `0x13c` | `0x120` | **`-0x1c`** |
| `__TEXT.__swift5_builtin` | `0x230` | `0x21c` | **`-0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x438` | `0x448` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xdd0` | `0xdc8` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0xbc` | `0xb8` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x3c8` | `0x3c4` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x4c4` | `0x4c8` | **`+0x4`** |

### Other Changes

```diff

-2.0.55.1.102
+2.0.59.0.0

-  Functions: 10376
-  Symbols:   318
-  CStrings:  626
+  Functions: 10541
+  Symbols:   320
+  CStrings:  653
Symbols:
+ _swift_getExtendedExistentialTypeMetadata_unique
+ _swift_task_localValuePop
+ _swift_task_localValuePush
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "\n[Internal Only]:\n"
+ "'body' should not be called on OnReasoningDynamicProfileModifier."
+ "Failed to read entitlement %{public}s: %{public}@"
+ "PromptCompletionEventConverter dropping unknown thought update: %s"
+ "Reduce the size of the transcript and try again."
+ "Remove the unsupported content from the transcript or use a model that supports it."
+ "Switch to a model that supports "
+ "Switch to a model that supports the generation guide, or change the guide."
+ "Try a different language or locale that the model supports."
+ "Try a different prompt."
+ "Wait a few seconds and try again."
+ "Wait a little bit and try again later."
+ "cached_tokens"
+ "chat.completion.chunk"
+ "choices"
+ "completion_tokens_details"
+ "guided generation"
+ "include_usage"
+ "n"
+ "parallel_tool_calls"
+ "prompt_tokens_details"
+ "reasoning_effort"
+ "reasoning_tokens"
+ "refusal"
+ "seed"
+ "stop"
+ "stream_options"
+ "tool_choice object form: expected type=='function', got '"
+ "tool_choice object form: missing function.name (or top-level name)"
+ "usage"
- "FoundationModels/LanguageModelSession.swift"
- "Unknown JSON value"
- "ddF>VUO'o?_>f?btqTS{p'O=o'Oxge[wpzyvg`Ouoz^tf?S=gdq$pzyCg`O}o{O>qPO=geu=YvObfdq(VT[uovO'geO'ge[yo{^tn?cBVU_$pTywp'%tgd>$qTy$o{Z!VTFvnzcwqUZ!VTF'VTSwqTy$o{Z!VTW>qPO\"qe[=VTByqzc'VTWyVUc#p?Szg`%tq{c!g?S'YPO$pvO$gzgyo{[}qzb#VSy$q`O@nd&!VTWyVTq}qzc#VTRtqe[ypvO}o{O>qPO=o'O=fdp!VTg$oT&$q?cxVTF%qTy$ozS!oUxtf{xt`y[]avO(f?uyodRtp@Oyf?yznd[uqTy$o{Z#VS_ug'O$oz&BVU_|g`O>p?c'VTy#pUc=YvOPg`OvpzyygvOuoz^tgTEtozF=VUO'o?_>f?btodF'g`O=nTS#VQbtqTS{p'O>oz&yp@ZtndB(qUW>f@_ygPO$qTuyp{q}p?b#Pt}ZfdB{qdS{g`O'qd&yVPu>oz&yp@ZtndB(qUW>f@_ygPO$qTuyp{q}p?b}\\vO=nTbtqTS{VUguoUcyp'OBo@btpUW$gUcwg`O\"qe[=VTWyVUq'ne_=gdAtndAtqTuyVU[uodbtoTS#g@cug?btfeZtqTuyVTy#pUc=VU_yrU^#VR_$VTB$qPO=pzS#p?&uqTbtqTuyVTy#pUc=YvOTo@VtgeuuoeO!g`%tqTuyVU[wnTc\"f`O%pzF%geW=r`O#fd>yp'O\"fextfzbtndAt_dB{oTy(nP%tf{c=VU_ug'O?fd&>geZtgzF!oTF@VU_|g`O}o{O>qPO!fdB{qdS{g`At`dftqTuyVTy#pUc=VTy(VTy#VRqypz>uov%tq@W}qTbt_?c'odS#VU_ug@Z#VRyzVU_|g`O}o{O>qPO}p'O}ovOQnTy#ge[yYPO@pzy=g`OQnTy#ge[yVU_ug@Z#VRyzVU_|g`O}o{O>qPO}p'O}ovOWqTS!ndS#YPO@pzy=g`OWqTS!ndS#VU_ug@Z#VRS#gPO$gvOwo@c'p?b!VTyzVU_|g`O}o{O>qPO}p'OSozq!ne[|YPO@pzy=g`OSozq!ne[|VU_ug@Z#"
```
