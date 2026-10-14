## HSTouchHIDService

> `/System/Library/HIDPlugins/ServicePlugins/HSTouchHIDService.plugin/HSTouchHIDService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcfca0` | `0xcfe50` | **`+0x1b0`** |
| `__TEXT.__objc_methtype` | `0x58b1` | `0x590c` | **`+0x5b`** |
| `__TEXT.__objc_methname` | `0x90a9` | `0x90eb` | **`+0x42`** |
| `__TEXT.__gcc_except_tab` | `0xead8` | `0xeb0c` | **`+0x34`** |
| `__TEXT.__objc_stubs` | `0x7b20` | `0x7b40` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x4900` | `0x4910` | **`+0x10`** |
| `__DATA.__objc_const` | `0x9eb0` | `0x9eb8` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x2440` | `0x2448` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5558` | `0x5560` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-10110.3.0.0.0
+10110.4.0.0.0

-  Functions: 5285
-  Symbols:   7773
-  CStrings:  4203
+  Functions: 5288
+  Symbols:   7778
+  CStrings:  4206
Symbols:
+ GCC_except_table166
+ __ZN14SABinaryParser14parseRunHeaderEv
+ __ZN14SABinaryWriter5writeEPKvm
+ ___43-[HSTSensingAlgs initWithConfig:queue:log:]_block_invoke_9
+ _objc_msgSend$initWithStreamSize:platformId:personalityId:queue:streamCallback:
Functions:
~ __ZN14SABinaryParser15parseInjExtDataEPFbPvRK21_SABinaryInjExtPacketPKhES7_PFbS0_RK20_SABinaryInjExtPointE : 416 -> 424
~ __ZN14SABinaryParser13parseRunFrameEPFbPvRK19_SABinaryInjExtDataEPFbS0_RK21_SABinaryInjExtPacketPKhESC_ : 196 -> 132
+ __ZN14SABinaryParser14parseRunHeaderEv
~ -[HSTSensingAlgs initWithConfig:queue:log:] : 2000 -> 2204
~ ___43-[HSTSensingAlgs initWithConfig:queue:log:]_block_invoke_4 : 100 -> 116
~ ___43-[HSTSensingAlgs initWithConfig:queue:log:]_block_invoke_5 : 148 -> 100
~ ___43-[HSTSensingAlgs initWithConfig:queue:log:]_block_invoke_6 : 116 -> 148
~ ___43-[HSTSensingAlgs initWithConfig:queue:log:]_block_invoke_7 : 112 -> 116
~ ___43-[HSTSensingAlgs initWithConfig:queue:log:]_block_invoke_8 : 124 -> 112
+ ___43-[HSTSensingAlgs initWithConfig:queue:log:]_block_invoke_9
~ -[HSTSensingAlgs _handleResetRequest:] : 364 -> 368
~ __ZN14SABinaryWriter15initHostRequestEhtPKv : 240 -> 168
+ __ZN14SABinaryWriter5writeEPKvm
CStrings:
+ "10110.4"
+ "@56@0:8Q16Q24Q32@\"NSObject<OS_dispatch_queue>\"40@?<v@?@\"NSData\">48"
+ "@56@0:8Q16Q24Q32@40@?48"
+ "initWithStreamSize:platformId:personalityId:queue:streamCallback:"
- "10110.3"
```
