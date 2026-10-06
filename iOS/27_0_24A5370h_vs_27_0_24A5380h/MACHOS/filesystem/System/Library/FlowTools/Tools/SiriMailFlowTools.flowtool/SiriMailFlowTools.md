## SiriMailFlowTools

> `/System/Library/FlowTools/Tools/SiriMailFlowTools.flowtool/SiriMailFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46c0c` | `0x49aa0` | **`+0x2e94`** |
| `__TEXT.__oslogstring` | `0xffd` | `0x13da` | **`+0x3dd`** |
| `__TEXT.__objc_stubs` | `0x240` | `0x460` | **`+0x220`** |
| `__TEXT.__const` | `0x14c0` | `0x16c0` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x282` | `0x411` | **`+0x18f`** |
| `__TEXT.__eh_frame` | `0x3e10` | `0x3cc0` | **`-0x150`** |
| `__DATA_CONST.__const` | `0xa60` | `0xba8` | **`+0x148`** |
| `__DATA.__bss` | `0x1450` | `0x1520` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0x1350` | `0x1410` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x616` | `0x6c4` | **`+0xae`** |
| `__TEXT.__swift5_reflstr` | `0x503` | `0x5a9` | **`+0xa6`** |
| `__DATA.__objc_const` | `0xa38` | `0xad8` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x90` | `0x118` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x2f0` | `0x360` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x590` | `0x5fc` | **`+0x6c`** |
| `__TEXT.__constg_swiftt` | `0x36c` | `0x3d4` | **`+0x68`** |
| `__DATA.__data` | `0xa30` | `0xa90` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x9b0` | `0xa10` | **`+0x60`** |
| `__TEXT.__cstring` | `0x254` | `0x2a4` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1398` | `0x13e8` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x740` | `0x778` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x60` | `0x78` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x34` | `0x3c` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x10` | `0x14` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.23.4.0.0
+3600.23.10.0.0

+  - /System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics
+  - /System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation

-  Functions: 1471
-  Symbols:   142
-  CStrings:  102
+  Functions: 1543
+  Symbols:   157
+  CStrings:  132
Symbols:
+ _OBJC_CLASS_$_AssistantSiriAnalytics
+ _OBJC_CLASS_$_FTDMailSchemaFTDMailApplicationInfo
+ _OBJC_CLASS_$_FTDMailSchemaFTDMailCreateOrUpdateDraftInvoked
+ _OBJC_CLASS_$_FTDMailSchemaFTDMailRecipientsInfo
+ _OBJC_CLASS_$_FTDMailSchemaFTDMailSendDraftInvoked
+ _OBJC_CLASS_$_FTDSchemaFTDClientEvent
+ _OBJC_CLASS_$_FTDSchemaFTDClientEventMetadata
+ _OBJC_CLASS_$_SISchemaUUID
+ _objc_release
+ _objc_release_x25
+ _objc_release_x26
+ _objc_retain
+ _objc_retain_x23
+ _swift_conformsToProtocol2
+ _swift_unknownObjectRelease
CStrings:
+ "#ComposeMailFlowTool - foreground Mail compose detected, suppressing Siri response to avoid blank auto-snippet over the compose sheet"
+ "#FTDMailMetricsSubmitter %s"
+ "#FTDMailMetricsSubmitter Failed to create FTDMailSchemaFTDMailApplicationInfo"
+ "#FTDMailMetricsSubmitter Failed to create FTDMailSchemaFTDMailCreateOrUpdateDraftInvoked"
+ "#FTDMailMetricsSubmitter Failed to create FTDMailSchemaFTDMailRecipientsInfo"
+ "#FTDMailMetricsSubmitter Failed to create FTDMailSchemaFTDMailSendDraftInvoked"
+ "#FTDMailMetricsSubmitter Failed to create FTDSchemaFTDClientEvent"
+ "#FTDMailMetricsSubmitter Failed to create FTDSchemaFTDClientEventMetadata"
+ "#FTDMailMetricsSubmitter Unmapped FlowToolInvocationContext.ResponseMode case %s — reporting UNKNOWN"
+ "#MailFlowTool foregrounded app %s differs from executing app %s, but composing with attachments in display mode — letting AppIntent execute in foreground so the user can see the attachment in the full UI"
+ "_metricsSubmitter"
+ "emitMessage:"
+ "initWithNSUUID:"
+ "setAppBundleId:"
+ "setContactRecipients:"
+ "setEventMetadata:"
+ "setFlowToolClientInteractionId:"
+ "setHasForcedBackgroundMode:"
+ "setHasSpecifiedMailAccount:"
+ "setHasVendedSnippet:"
+ "setIsForegrounded:"
+ "setMailApplication:"
+ "setMailCreateOrUpdateDraftInvoked:"
+ "setMailSendDraftInvoked:"
+ "setNonContactRecipients:"
+ "setRecipients:"
+ "setUserResponseMode:"
+ "sharedStream"
+ "submitCreateOrUpdateDraftInvoked"
+ "submitSendDraftInvoked"
```
