## Moments

> `/usr/libexec/Moments.framework/Moments`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x106e0` | `0x10920` | **`+0x240`** |
| `__TEXT.__cstring` | `0xe22f` | `0xe38f` | **`+0x160`** |
| `__TEXT.__text` | `0x75b34` | `0x75b4c` | **`+0x18`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_DIRTY.__data`
- `__DATA_DIRTY.__objc_data`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 2925
+  Functions: 2924

-  CStrings:  5172
+  CStrings:  5190
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Moments/install/TempContent/Objects/Moments.build/Moments.build/Objects-normal/arm64e/RTLocation+MOExtensions-7e1a45f4f90ca3312d0526f55c247da1.o
+ _swift_release_x27
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Moments/install/TempContent/Objects/Moments.build/Moments.build/Objects-normal/arm64e/RTLocation+MOExtensions-c11802b4aeeaa31b0d7eff86612c76b7.o
- _swift_release_x25
Functions:
~ _OUTLINED_FUNCTION_2 : 20 -> 40
~ _OUTLINED_FUNCTION_3 : 40 -> 20
- _OUTLINED_FUNCTION_0
~ _$ss17_NativeDictionaryV4copyyyFSS_Say7Moments10IndexEntry33_79BD8C0856AF87E18AD46ADB07A1F2B3LLVGTg5 : 360 -> 364
~ _$ss17_NativeDictionaryV4copyyyFSS_SdTg5 : 352 -> 356
~ __62-[MOConnectionManager withProxyProvider:proxyHandler:onError:]_block_invoke.cold.1 : 136 -> 164
~ __62-[MOConnectionManager withProxyProvider:proxyHandler:onError:]_block_invoke.27.cold.1 : 136 -> 164
CStrings:
+ "MOAction.m"
+ "MOAppEngagementReporter.m"
+ "MOConnectionManager.m"
+ "MODefaultsManager.m"
+ "MODictionaryEncoder.m"
+ "MOEvent.m"
+ "MOEventBundle.m"
+ "MOEventBundleLabelCondition.m"
+ "MOEventBundleLabelFormat.m"
+ "MOEventBundleLabelLocalizer.m"
+ "MOEventBundleLabelTemplate.m"
+ "MOEventExtendedAtrributes.m"
+ "MOInteraction.m"
+ "MOMediaPlaySession.m"
+ "MOPlace.m"
+ "MOResource.m"
+ "MOTime.m"
+ "MOXPCContext.m"
```
