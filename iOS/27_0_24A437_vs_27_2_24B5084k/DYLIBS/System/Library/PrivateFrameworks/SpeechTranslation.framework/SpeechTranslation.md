## SpeechTranslation

> `/System/Library/PrivateFrameworks/SpeechTranslation.framework/SpeechTranslation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x328c4` | `0x33978` | **`+0x10b4`** |
| `__AUTH_CONST.__objc_const` | `0x2488` | `0x2638` | **`+0x1b0`** |
| `__TEXT.__objc_methlist` | `0x1314` | `0x13f4` | **`+0xe0`** |
| `__DATA.__data` | `0xb28` | `0xbf8` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0xde8` | `0xd80` | **`-0x68`** |
| `__AUTH.__objc_data` | `0x640` | `0x690` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0xd98` | `0xde8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xab8` | `0xb08` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x675` | `0x659` | **`-0x1c`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0xb0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x3cc` | `0x3e4` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x598` | `0x5a8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xba8` | `0xbb0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xb8` | `0xc0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xcd0` | `0xcd8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xc4` | `0xc0` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x48` | `0x44` | **`-0x4`** |

### Other Changes

```diff

-389.1.0.0.0
+393.1.0.0.0

-  Functions: 1007
-  Symbols:   1057
+  Functions: 1030
+  Symbols:   1078
Symbols:
+ -[STConversationalSpeechCoordinator addAudioBuffer:forSourceLocale:]
+ -[STConversationalSpeechCoordinator finishInputForSourceLocale:]
+ -[STConversationalSpeechCoordinator setDelegate:forSourceLocale:]
+ -[STConversationalSpeechCoordinator supportsSourceLocale:targetLocale:]
+ _OBJC_CLASS_$_STConversationalSpeechCoordinator
+ _OBJC_METACLASS_$_STConversationalSpeechCoordinator
+ __OBJC_$_INSTANCE_METHODS_STConversationalSpeechCoordinator
+ __OBJC_$_INSTANCE_METHODS_STSpeechTranslator(SpeechTranslation|SpeechTranslation1)
+ __OBJC_$_PROP_LIST_STConversationalSpeechCoordinator
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_STConversationalSpeechCoordinatorDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_STConversationalSpeechCoordinating
+ __OBJC_$_PROTOCOL_METHOD_TYPES_STConversationalSpeechCoordinating
+ __OBJC_$_PROTOCOL_METHOD_TYPES_STConversationalSpeechCoordinatorDelegate
+ __OBJC_$_PROTOCOL_REFS_STConversationalSpeechCoordinating
+ __OBJC_$_PROTOCOL_REFS_STConversationalSpeechCoordinatorDelegate
+ __OBJC_CLASS_PROTOCOLS_$_STConversationalSpeechCoordinator
+ __OBJC_CLASS_PROTOCOLS_$_STSpeechTranslator(SpeechTranslation|SpeechTranslation1)
+ __OBJC_CLASS_RO_$_STConversationalSpeechCoordinator
+ __OBJC_LABEL_PROTOCOL_$_STConversationalSpeechCoordinating
+ __OBJC_LABEL_PROTOCOL_$_STConversationalSpeechCoordinatorDelegate
+ __OBJC_METACLASS_RO_$_STConversationalSpeechCoordinator
+ __OBJC_PROTOCOL_$_STConversationalSpeechCoordinating
+ __OBJC_PROTOCOL_$_STConversationalSpeechCoordinatorDelegate
+ ___swift_closure_destructor.115Tm
+ ___swift_closure_destructor.124Tm
+ ___swift_closure_destructor.76Tm
+ _keypath_get_selector_conversationalCoordinator
- __OBJC_$_INSTANCE_METHODS_STSpeechTranslator(SpeechTranslation)
- __OBJC_CLASS_PROTOCOLS_$_STSpeechTranslator(SpeechTranslation)
- ___swift_closure_destructor.108Tm
- ___swift_closure_destructor.117Tm
- ___swift_closure_destructor.74Tm
- _symbolic So21STTranscriptionResultC
```
