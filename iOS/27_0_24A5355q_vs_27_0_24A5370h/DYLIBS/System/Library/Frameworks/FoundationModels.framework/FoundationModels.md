## FoundationModels

> `/System/Library/Frameworks/FoundationModels.framework/FoundationModels`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x222b6c` | `0x205664` | **`-0x1d508`** |
| `__TEXT.__const` | `0x1da58` | `0x1ce82` | **`-0xbd6`** |
| `__AUTH_CONST.__const` | `0x15eb8` | `0x154f8` | **`-0x9c0`** |
| `__TEXT.__eh_frame` | `0xf228` | `0xeb10` | **`-0x718`** |
| `__DATA.__bss` | `0x22e50` | `0x22820` | **`-0x630`** |
| `__TEXT.__swift5_typeref` | `0x727d` | `0x6e6e` | **`-0x40f`** |
| `__TEXT.__unwind_info` | `0x7bb8` | `0x77c0` | **`-0x3f8`** |
| `__AUTH.__data` | `0x4b68` | `0x47b0` | **`-0x3b8`** |
| `__TEXT.__swift5_fieldmd` | `0x8c14` | `0x88f0` | **`-0x324`** |
| `__TEXT.__constg_swiftt` | `0x7f84` | `0x7c68` | **`-0x31c`** |
| `__DATA.__data` | `0x5320` | `0x5088` | **`-0x298`** |
| `__TEXT.__swift5_reflstr` | `0x584a` | `0x5676` | **`-0x1d4`** |
| `__TEXT.__swift5_assocty` | `0x1620` | `0x1468` | **`-0x1b8`** |
| `__AUTH_CONST.__objc_const` | `0x2150` | `0x1fc8` | **`-0x188`** |
| `__TEXT.__cstring` | `0x5aaa` | `0x5bcb` | **`+0x121`** |
| `__DATA_DIRTY.__data` | `0x2300` | `0x2218` | **`-0xe8`** |
| `__TEXT.__swift5_capture` | `0x1310` | `0x1258` | **`-0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x2848` | `0x27e0` | **`-0x68`** |
| `__DATA_DIRTY.__common` | `0xd8` | `0x78` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x460` | `0x410` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x480` | `0x430` | **`-0x50`** |
| `__TEXT.__swift5_proto` | `0x14b4` | `0x1468` | **`-0x4c`** |
| `__TEXT.__swift_as_ret` | `0x510` | `0x4c4` | **`-0x4c`** |
| `__TEXT.__swift5_types` | `0xafc` | `0xab4` | **`-0x48`** |
| `__DATA.__common` | `0x260` | `0x2a0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xe00` | `0xdd0` | **`-0x30`** |
| `__TEXT.__swift_as_entry` | `0x3f8` | `0x3c8` | **`-0x30`** |
| `__TEXT.__swift5_builtin` | `0x258` | `0x230` | **`-0x28`** |
| `__TEXT.__oslogstring` | `0x1d7c` | `0x1d5c` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x5bc` | `0x5d8` | **`+0x1c`** |
| `__TEXT.__swift5_mpenum` | `0x150` | `0x13c` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0xf0` | `0xe0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x428` | `0x438` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0xc0` | `0xbc` | **`-0x4`** |

### Other Changes

```diff

-2.0.51.3.0
+2.0.55.1.102

-  - /System/Library/PrivateFrameworks/ArgumentParserInternal.framework/ArgumentParserInternal

-  Functions: 10796
-  Symbols:   323
-  CStrings:  632
+  Functions: 10376
+  Symbols:   318
+  CStrings:  626
Symbols:
+ _swift_task_localValueGet
+ _sysctlbyname
- _CFGetTypeID
- _CGImageGetTypeID
- _MobileGestalt_copy_buildVersion_obj
- _MobileGestalt_copy_marketingProductName_obj
- _MobileGestalt_copy_productVersion_obj
- _swift_isClassType
- _swift_setAtWritableKeyPath
CStrings:
+ "%{public}s ends with %{public}s"
+ "%{public}s is empty"
+ "'body' should not be called on (TranscriptErrorHandlingPolicyModifier in _1CE817521DE1C52719918F4583AEF418)."
+ "'body' should not be called on AnyDynamicProfile."
+ "@SessionProperty can only be used in structs. Accessing @SessionProperty properties from %{public}s is a programmer error."
+ "Discarding invalid image tokenization recommendations (%lux%lu); falling back to original image dimensions."
+ "Duplicate tool name ('%{public}s'). Only the first will be used."
+ "FoundationModels/LanguageModelSession+Profile.swift"
+ "FoundationModels/LanguageModelSession+ProfileModifier.swift"
+ "FoundationModels/LanguageModelSession.swift"
+ "FoundationModels/ToolModifier.swift"
+ "Model is unavailable: %s"
+ "Process is missing required entitlement: "
+ "The arguments to 'Tool' should be a struct or enum. '%{public}s' takes 'arguments' of primitive type '%{public}s', which may not be properly called by the model."
+ "[DI]  @SessionProperty(%s) @Offset%{public}ld"
+ "ddF>VUO'o?_>f?btqTS{p'O=o'Oxge[wpzyvg`Ouoz^tf?S=gdq$pzyCg`O}o{O>qPO=geu=YvObfdq(VT[uovO'geO'ge[yo{^tn?cBVU_$pTywp'%tgd>$qTy$o{Z!VTFvnzcwqUZ!VTF'VTSwqTy$o{Z!VTW>qPO\"qe[=VTByqzc'VTWyVUc#p?Szg`%tq{c!g?S'YPO$pvO$gzgyo{[}qzb#VSy$q`O@nd&!VTWyVTq}qzc#VTRtqe[ypvO}o{O>qPO=o'O=fdp!VTg$oT&$q?cxVTF%qTy$ozS!oUxtf{xt`y[]avO(f?uyodRtp@Oyf?yznd[uqTy$o{Z#VS_ug'O$oz&BVU_|g`O>p?c'VTy#pUc=YvOPg`OvpzyygvOuoz^tgTEtozF=VUO'o?_>f?btodF'g`O=nTS#VQbtqTS{p'O>oz&yp@ZtndB(qUW>f@_ygPO$qTuyp{q}p?b#Pt}ZfdB{qdS{g`O'qd&yVPu>oz&yp@ZtndB(qUW>f@_ygPO$qTuyp{q}p?b}\\vO=nTbtqTS{VUguoUcyp'OBo@btpUW$gUcwg`O\"qe[=VTWyVUq'ne_=gdAtndAtqTuyVU[uodbtoTS#g@cug?btfeZtqTuyVTy#pUc=VU_yrU^#VR_$VTB$qPO=pzS#p?&uqTbtqTuyVTy#pUc=YvOTo@VtgeuuoeO!g`%tqTuyVU[wnTc\"f`O%pzF%geW=r`O#fd>yp'O\"fextfzbtndAt_dB{oTy(nP%tf{c=VU_ug'O?fd&>geZtgzF!oTF@VU_|g`O}o{O>qPO!fdB{qdS{g`At`dftqTuyVTy#pUc=VTy(VTy#VRqypz>uov%tq@W}qTbt_?c'odS#VU_ug@Z#VRyzVU_|g`O}o{O>qPO}p'O}ovOQnTy#ge[yYPO@pzy=g`OQnTy#ge[yVU_ug@Z#VRyzVU_|g`O}o{O>qPO}p'O}ovOWqTS!ndS#YPO@pzy=g`OWqTS!ndS#VU_ug@Z#VRS#gPO$gvOwo@c'p?b!VTyzVU_|g`O}o{O>qPO}p'OSozq!ne[|YPO@pzy=g`OSozq!ne[|VU_ug@Z#"
+ "error"
+ "kern.osversion"
+ "success"
- "%s ends with %s"
- "%s is empty"
- "'@SessionEnvironment' is deprecated, use '@SessionProperty instead'"
- "'AnyTool' might contain multiple tools."
- "'body' should not be called on (TranscriptErrorHandlingPolicyModifier in _346B07E8849AC3E2F00480608BC0A70F)."
- "'body' should not be called on DynamicInstructionsOutputsAdapter."
- "'body(content:)' should not be called on ErrorRecoveryPolicyToolModifier."
- "@SessionProperty can only be used in structs. Accessing @SessionProperty properties from %s is a programmer error."
- "Custom Segments are not applicable in Agents"
- "Duplicate tool name (\"%{public}s\"). Only the first will be used."
- "FoundationModels/AnyTool.swift"
- "FoundationModels/LanguageModelSession+Profile_v1.swift"
- "FoundationModels/LanguageModelSession+Profile_v1Modifier.swift"
- "FoundationModels/ToolModifier2.swift"
- "Templates are only supported for SystemLanguageModel"
- "The arguments to 'Tool' should be a struct or enum. '%s' takes 'arguments' of primitive type '%s', which may not be properly called by the model."
- "The system is not ready. Try again later."
- "Too many nested arrays or dictionaries."
- "ToolCalls entry metadata is not aggregated. Ignoring."
- "Use 'LanguageModelSession.DynamicProfile'"
- "You initialized a session with instructions and then used a prompt\ntemplate with it. The instructions passed in the initializer will be\nignored."
- "You specialize in producing tags in the same language as the input to describe and categorize input text. Tags can represent key topics, emotions, objects, or actions, but should never be unsafe, vulgar, or offensive. You will be given a user input to tag, followed optionally by JSON schema specifications. Tag only the user input."
- "[DI]  @SessionProperty(%s) @Offset%ld"
- "newErrorTypes"
- "openaicompletions"
```
