## Celestial

> `/System/Library/PrivateFrameworks/Celestial.framework/Celestial`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16c0` | `0xdac` | **`-0x914`** |
| `__TEXT.__oslogstring` | `0x2cc` | `—` | **`-0x2cc`** |
| `__TEXT.__cstring` | `0x57d` | `0x516` | **`-0x67`** |
| `__AUTH_CONST.__cfstring` | `0x8e0` | `0x8a0` | **`-0x40`** |
| `__DATA.__common` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__const` | `0x10` | `0x4` | **`-0xc`** |

### Other Changes

```diff

-3385.8.1.11.1
+3385.12.1.0.0

-  Symbols:   139
-  CStrings:  83
+  Symbols:   135
+  CStrings:  69
Symbols:
+ _objc_release_x20
+ _objc_release_x21
+ _objc_release_x28
- _FigNote_AllowInternalDefaultLogs
- __os_log_send_and_compose_impl
- _fig_log_call_emit_and_clean_up_after_send_and_compose
- _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
- _fig_note_initialize_category_with_default_work_cf
- _gFigCheckpointTrace
- _os_log_type_enabled
Functions:
~ +[FigCheckpointSupport makeDictionary] : 104 -> 8
~ __computeCheckpoint : 4080 -> 1960
~ +[FigCheckpointSupport makeDictionaryForDevice:] : 116 -> 8
CStrings:
- "<<<< FigCheckpointSupport >>>> %s: CHECKPOINT %@"
- "<<<< FigCheckpointSupport >>>> %s: Finished creating audio codec list %@"
- "<<<< FigCheckpointSupport >>>> %s: Finished creating complete list %@"
- "<<<< FigCheckpointSupport >>>> %s: Finished creating video codec list %@"
- "<<<< FigCheckpointSupport >>>> %s: Opening checkpointAdditionsSpecificationDictionary %@"
- "<<<< FigCheckpointSupport >>>> %s: creating audio and video codec dictionary from input %@"
- "<<<< FigCheckpointSupport >>>> %s: failed to create dictionary from %s"
- "<<<< FigCheckpointSupport >>>> %s: specificationDictionary was NIL, audioSpecificationDictionary %@"
- "<<<< FigCheckpointSupport >>>> %s: specificationDictionary was NIL, videoSpecificationDictionary %@"
- "_addSpecificationAdditions"
- "_computeCheckpoint"
- "_twiddleCheckpoint"
- "checkpoint_trace"
- "com.apple.coremedia"
```
