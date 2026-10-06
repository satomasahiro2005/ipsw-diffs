## AppIntentsTypeSupport

> `/System/Library/Frameworks/AppIntentsTypeSupport.framework/AppIntentsTypeSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9fc` | `0xc904` | **`+0xf08`** |
| `__TEXT.__const` | `0x1720` | `0x19f4` | **`+0x2d4`** |
| `__AUTH_CONST.__const` | `0x1590` | `0x1788` | **`+0x1f8`** |
| `__DATA.__bss` | `0x1c10` | `0x1d90` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x4e0` | `0x5a0` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x79b` | `0x83d` | **`+0xa2`** |
| `__TEXT.__swift5_fieldmd` | `0x3a8` | `0x440` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x690` | `0x724` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0x640` | `0x6b8` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0x236` | `0x2ab` | **`+0x75`** |
| `__TEXT.__cstring` | `0x14e` | `0x19e` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2c0` | `0x2f8` | **`+0x38`** |
| `__DATA.__data` | `0x408` | `0x428` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0xe0` | `0xf0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1dc` | `0x1ec` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x54` | `0x60` | **`+0xc`** |
| `__TEXT.__swift5_mpenum` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-301.0.51.1.104
+301.1.9.1.101

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 630
-  Symbols:   214
-  CStrings:  9
+  Functions: 680
+  Symbols:   236
+  CStrings:  10
Symbols:
+ _OUTLINED_FUNCTION_8
+ _OUTLINED_FUNCTION_9
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ _associated conformance 21AppIntentsTypeSupport0cD5ErrorO10Foundation09LocalizedE0AAs0E0
+ _get_enum_tag_for_layout_string 21AppIntentsTypeSupport24PropertyContainerElementV5StateO
+ _get_enum_tag_for_layout_string 21AppIntentsTypeSupport28DeferredValueResolverFactory_pSg
+ _swift_task_alloc
+ _swift_task_dealloc
+ _swift_task_switch
+ _symbolic $s21AppIntentsTypeSupport21DeferredValueResolverP
+ _symbolic $s21AppIntentsTypeSupport28DeferredValueResolverFactoryP
+ _symbolic _____ 21AppIntentsTypeSupport19DeferredIntentValueV
+ _symbolic _____ 21AppIntentsTypeSupport24DeferredValuePlaceholderV
+ _symbolic _____ 21AppIntentsTypeSupport24PropertyContainerElementV5StateO
+ _symbolic ______AAt 21AppIntentsTypeSupport21IntentValueExpressionV7StorageO
+ _symbolic ______p 21AppIntentsTypeSupport21DeferredValueResolverP
+ _symbolic ______pSg 21AppIntentsTypeSupport28DeferredValueResolverFactoryP
+ _type_layout_string 21AppIntentsTypeSupport19DeferredIntentValueV
+ _type_layout_string 21AppIntentsTypeSupport20IntentValueContainerV17ConversionContextV
+ _type_layout_string 21AppIntentsTypeSupport24PropertyContainerElementV5StateO
CStrings:
+ "This value is deferred; it must be fetched before it can be read."
```
