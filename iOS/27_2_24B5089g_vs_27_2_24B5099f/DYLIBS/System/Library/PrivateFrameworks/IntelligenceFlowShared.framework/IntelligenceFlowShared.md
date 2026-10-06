## IntelligenceFlowShared

> `/System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd88d4` | `0xdc9f8` | **`+0x4124`** |
| `__AUTH_CONST.__const` | `0xcb10` | `0xcea8` | **`+0x398`** |
| `__TEXT.__eh_frame` | `0x54d4` | `0x569c` | **`+0x1c8`** |
| `__TEXT.__const` | `0x15570` | `0x156e0` | **`+0x170`** |
| `__TEXT.__cstring` | `0x956a` | `0x96aa` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x5c20` | `0x5d50` | **`+0x130`** |
| `__AUTH_CONST.__auth_got` | `0x1428` | `0x1548` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0x3df2` | `0x3ebc` | **`+0xca`** |
| `__TEXT.__constg_swiftt` | `0x3954` | `0x3a18` | **`+0xc4`** |
| `__DATA_CONST.__got` | `0x7b8` | `0x848` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0xd66` | `0xdf6` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x57bc` | `0x5840` | **`+0x84`** |
| `__DATA.__bss` | `0x19010` | `0x19090` | **`+0x80`** |
| `__DATA.__data` | `0x2348` | `0x23b0` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x338` | `0x390` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x354` | `0x388` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0x3f1c` | `0x3f4c` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x5d0` | `0x5e4` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x578` | `0x580` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1400` | `0x1408` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x38` | `0x3c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x8c` | `0x90` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x88` | `0x8c` | **`+0x4`** |

### Other Changes

```diff

-3605.16.9.501.1
+3605.21.1.501.4

+  - /System/Library/Frameworks/CFNetwork.framework/CFNetwork

+  - /System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation

-  Functions: 9764
-  Symbols:   308
-  CStrings:  1162
+  Functions: 9859
+  Symbols:   314
+  CStrings:  1172
Symbols:
+ _OBJC_CLASS_$_AssistantSiriAnalytics
+ _OBJC_CLASS_$_LSAppLink
+ _OBJC_CLASS_$_LSApplicationExtensionRecord
+ _OBJC_CLASS_$_LSBundleRecord
+ _OBJC_CLASS_$_SISchemaProvisionalEvent
+ __CFHostIsDomainTopLevel
CStrings:
+ "Failed to allocate SISchemaProvisionalEvent for clock ping"
+ "OutputGuardrailOnPCC"
+ "[UniversalLinkResolver] LSAppLink lookup failed for %{sensitive}s: %{public}s"
+ "bundleIdentifier(forURL:)"
+ "com.apple.TVSystemUIService"
+ "com.apple.intelligenceflow.clock_ping"
+ "com.apple.mobiletimer.Alarms"
+ "com.apple.private.appintents.attribution.bundle-identifier"
+ "if.executor.classifier_input_char_count"
+ "if.planner.ipi_input_char_count"
```
