## swtransparencyd

> `/usr/libexec/swtransparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xff2d0` | `0xffbe8` | **`+0x918`** |
| `__TEXT.__objc_methname` | `0x780d` | `0x79bd` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0x65c0` | `0x6680` | **`+0xc0`** |
| `__DATA.__objc_const` | `0xe860` | `0xe8f0` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x30c0` | `0x3140` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x70b4` | `0x712c` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x2158` | `0x21c0` | **`+0x68`** |
| `__TEXT.__cstring` | `0x4ea9` | `0x4ee9` | **`+0x40`** |
| `__DATA_CONST.__objc_intobj` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x2810` | `0x2840` | **`+0x30`** |
| `__TEXT.__const` | `0x5ef0` | `0x5f20` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x20a5` | `0x20d2` | **`+0x2d`** |
| `__DATA_CONST.__got` | `0x698` | `0x6b8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1418` | `0x1430` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4840` | `0x4858` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x141b` | `0x142f` | **`+0x14`** |
| `__DATA.__bss` | `0x7118` | `0x7128` | **`+0x10`** |
| `__DATA.__data` | `0x48c0` | `0x48d0` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x6a54` | `0x6a64` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x448` | `0x458` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x468` | `0x474` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1766.40.47.0.0
+1766.40.50.0.0

-  Functions: 6052
-  Symbols:   960
-  CStrings:  2901
+  Functions: 6063
+  Symbols:   967
+  CStrings:  2928
Symbols:
+ _$sSh10FoundationE19_bridgeToObjectiveCSo5NSSetCyF
+ _$sSo8NSObjectC10ObjectiveCE13_rawHashValue4seedS2i_tF
+ _$sSo8NSObjectC10ObjectiveCE2eeoiySbAB_ABtFZ
+ _$sSo8NSObjectCSH10ObjectiveCMc
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _OBJC_CLASS_$_NSSet
+ _kKTApplicationIdentifierIDS
CStrings:
+ "%ld"
+ "@\"NSNumber\""
+ "@32@0:8d16@24"
+ "T@\"NSArray\",&,V_queryReasons"
+ "T@\"NSNumber\",&,V_optInState"
+ "TB,V_needsRefreshFromUnknownSPKIHash"
+ "_needsRefreshFromUnknownSPKIHash"
+ "_optInState"
+ "_queryReasons"
+ "allObjects"
+ "compare:"
+ "configBagRequest:queryReasons:"
+ "configureFromNetworkWithFetcher:networkTimeout:queryReasons:completionHandler:"
+ "configureWithFetcher:networkTimeout:queryReasons:completionHandler:"
+ "needsRefreshFromUnknownSPKIHash"
+ "optInState"
+ "optInStateForApplication:"
+ "q"
+ "queryReasonHeaderValue:"
+ "queryReasons"
+ "setByAddingObject:"
+ "setNeedsRefreshFromUnknownSPKIHash:"
+ "setOptInState:"
+ "setOptInStateProvider:"
+ "setQueryReasons:"
+ "setWithArray:"
+ "triggerConfigBagFetch:reasons:"
+ "v1:[%@]"
+ "v32@0:8d16@\"NSSet\"24"
+ "v48@0:8@16d24@32@?40"
+ "x-apple-kt-opt-in"
+ "x-apple-kt-query-reason"
- "configBagRequest:"
- "configureFromNetworkWithFetcher:networkTimeout:completionHandler:"
- "configureWithFetcher:networkTimeout:completionHandler:"
- "triggerConfigBagFetch:"
- "v40@0:8@16d24@?32"
```
