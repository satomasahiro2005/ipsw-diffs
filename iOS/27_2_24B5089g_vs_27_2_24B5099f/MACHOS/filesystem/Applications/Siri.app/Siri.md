## Siri

> `/Applications/Siri.app/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf24b4` | `0xf2f64` | **`+0xab0`** |
| `__TEXT.__objc_methtype` | `0xafb1` | `0xb101` | **`+0x150`** |
| `__TEXT.__cstring` | `0x2481d` | `0x2492d` | **`+0x110`** |
| `__TEXT.__objc_methname` | `0x2bb7f` | `0x2ba7f` | **`-0x100`** |
| `__TEXT.__swift5_reflstr` | `0x1a61` | `0x1b11` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x265c` | `0x2700` | **`+0xa4`** |
| `__DATA.__objc_const` | `0x10eb8` | `0x10f38` | **`+0x80`** |
| `__DATA.__objc_data` | `0x4bd8` | `0x4c48` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0xdc34` | `0xdca4` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x2578` | `0x25c8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xe480` | `0xe4b0` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1348` | `0x1378` | **`+0x30`** |
| `__DATA.__data` | `0x47f0` | `0x4810` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x3060` | `0x3080` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1b860` | `0x1b880` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x90b8` | `0x90c8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1840` | `0x1850` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x1fa3` | `0x1fb3` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.24.1.0.0
+3605.30.1.0.0

-  Functions: 5209
-  Symbols:   1865
-  CStrings:  9087
+  Functions: 5216
+  Symbols:   1867
+  CStrings:  9100
Symbols:
+ _$s10Foundation4UUIDV2eeoiySbAC_ACtFZ
+ _swift_setAtReferenceWritableKeyPath
CStrings:
+ "#PreprocessNotification We have a preprocessed response. Presenting the response and immediately marking the response as rendered."
+ "%s #aceCommandRecord recording action completed at the presentation's request for aceCommand=%@ success=%i"
+ "-[SRSiriViewController siriPresentation:recordActionCompletedForAceCommand:success:]"
+ "carPlayViewControllerRequestsPerformIFAction(_:action:turnIdentifier:)"
+ "dispatcher:didFailPerformingAppIntentWithError:"
+ "isAttendingCarProvider"
+ "maxHeightConstraint"
+ "minHeightConstraint"
+ "pendingInteractionTurn"
+ "performIFAction:turnIdentifier:"
+ "searchui_cardLoader"
+ "siriPresentation:performIFAction:turnIdentifier:completion:"
+ "siriPresentation:recordActionCompletedForAceCommand:success:"
+ "startNewInstrumentationTurn(from:)"
+ "v32@0:8@\"<AFIntelligenceFlowActionDescriptor>\"16@\"NSUUID\"24"
+ "v32@0:8@\"SRUIFAppIntentDispatcher\"16@\"NSError\"24"
+ "v36@0:8@\"<SiriUIPresentation>\"16@\"AceObject<SAAceCommand>\"24B32"
+ "v48@0:8@\"<SiriUIPresentation>\"16@\"<AFIntelligenceFlowActionDescriptor>\"24@\"NSUUID\"32@?<v@?B>40"
+ "waveFormIsVisible"
- "#instrumentation New Turn %@ "
- "_directionalAccessoryEdgeInsets"
- "_scrollViewAccessoryInsetsDidChange:"
- "carPlayViewControllerRequestsPerformIFAction(_:action:)"
- "cardLoader"
- "isAttendingCar"
```
