## libswiftDemangle.dylib

> `/usr/lib/swift/libswiftDemangle.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59da0` | `0x59fec` | **`+0x24c`** |
| `__TEXT.__cstring` | `0x5380` | `0x539c` | **`+0x1c`** |

### Other Changes

```diff

-6.4.0.27.101
+6.4.0.31.4

-  CStrings:  1345
+  CStrings:  1346
Functions:
~ sub_2c242718c -> sub_2c225e18c : 48 -> 52
~ __ZN5swift8Demangle9Demangler30demangleFunctionSpecializationEv : 1096 -> 1104
~ __ZN5swift8Demangle9Demangler21demangleFuncSpecParamENS0_4Node4KindE : 2856 -> 2992
~ __ZN5swift8Demangle11NodePrinter5printEPNS0_4NodeEjb : 27628 -> 27640
~ __ZN5swift8Demangle11NodePrinter36printFunctionSigSpecializationParamsEPNS0_4NodeEj : 2760 -> 2792
~ __ZN12_GLOBAL__N_19Remangler42mangleFunctionSignatureSpecializationParamEPN5swift8Demangle4NodeEj : 6148 -> 6544
CStrings:
+ "Escaping Closure Propagated"
```
