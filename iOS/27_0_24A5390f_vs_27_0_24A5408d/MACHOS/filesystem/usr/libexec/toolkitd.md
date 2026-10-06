## toolkitd

> `/usr/libexec/toolkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x99920` | `0xa3198` | **`+0x9878`** |
| `__TEXT.__eh_frame` | `0x4c18` | `0x5f28` | **`+0x1310`** |
| `__TEXT.__unwind_info` | `0x1b38` | `0x1f10` | **`+0x3d8`** |
| `__DATA_CONST.__const` | `0x4160` | `0x4480` | **`+0x320`** |
| `__TEXT.__const` | `0x461c` | `0x482c` | **`+0x210`** |
| `__TEXT.__swift5_capture` | `0xc04` | `0xd44` | **`+0x140`** |
| `__TEXT.__auth_stubs` | `0x2d10` | `0x2e10` | **`+0x100`** |
| `__TEXT.__swift_as_ret` | `0x16c` | `0x228` | **`+0xbc`** |
| `__TEXT.__swift_as_entry` | `0x128` | `0x1e0` | **`+0xb8`** |
| `__TEXT.__swift_as_cont` | `0x384` | `0x410` | **`+0x8c`** |
| `__DATA_CONST.__auth_got` | `0x1690` | `0x1710` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x175c` | `0x17dc` | **`+0x80`** |
| `__TEXT.__cstring` | `0x220d` | `0x226d` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xbe8` | `0xc00` | **`+0x18`** |
| `__DATA.__data` | `0x1d78` | `0x1d68` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x790` | `0x798` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1845` | `0x183d` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-5034.0.12.100.0
+5037.103.100.0.0

-  Functions: 2752
-  Symbols:   1258
-  CStrings:  573
+  Functions: 2977
+  Symbols:   1277
+  CStrings:  580
Symbols:
+ _$s10Foundation4DateVACycfC
+ _$s19VoiceShortcutClient21ToolKitIndexingReasonV7TriggerO16languagesChangedyA2EmFWC
+ _$s19VoiceShortcutClient21ToolKitIndexingReasonV7TriggerO20siriLanguagesChangedyA2EmFWC
+ _$s19VoiceShortcutClient21ToolKitIndexingReasonV7TriggerOMa
+ _$s19VoiceShortcutClient21ToolKitIndexingReasonV7triggerAC7TriggerOvg
+ _$s19VoiceShortcutClient21ToolKitIndexingReasonVMa
+ _$s19VoiceShortcutClient22ToolKitIndexingRequestC7reasonsSayAA0deF6ReasonVGvg
+ _$s7ToolKit0A8DatabaseC8AccessorC15clearUnusedData24removedBundleIdentifiersyShySSG_tKF
+ _$s7ToolKit17IndexingTelemetryO013recordIndexedA08bundleIDySS_tFZ
+ _$s7ToolKit17IndexingTelemetryO12BundleCountsVMa
+ _$s7ToolKit17IndexingTelemetryO12recordBundle_6counts9startDate03endI0ySS_AC0F6CountsV10Foundation0I0VALtFZ
+ _$s7ToolKit17IndexingTelemetryO12resetAccrualyyFZ
+ _$s7ToolKit17IndexingTelemetryO14flushRunBuffer9reasonForyAC6ReasonOSSXE_tFZ
+ _$s7ToolKit17IndexingTelemetryO17recordIndexedEnum8bundleIDySS_tFZ
+ _$s7ToolKit17IndexingTelemetryO19recordIndexedEntity8bundleIDySS_tFZ
+ _$s7ToolKit17IndexingTelemetryO5drainyyYaFZ
+ _$s7ToolKit17IndexingTelemetryO5drainyyYaFZTu
+ _$s7ToolKit17IndexingTelemetryO6counts9forBundleAC0G6CountsVSS_tFZ
+ _$s7ToolKit17IndexingTelemetryO6reason16isLanguageChange9changesetAC6ReasonOSScSb_19VoiceShortcutClient0abcJ0V9ChangesetOtFZ
+ _$s7ToolKit17IndexingTelemetryO7prewarmyyFZ
- _$s7ToolKit0A8DatabaseC8AccessorC15clearUnusedDatayyKF
CStrings:
+ "AppIntentBundleIndexingStep bundle="
+ "IndexBundle"
+ "IndexStep"
+ "Reindex.LocalIndex"
+ "bundle=%{signpost.description:attribute}s"
+ "process: toolkitd"
+ "step=%{signpost.description:attribute}s"
```
