## PreviewsInjection

> `/System/Library/PrivateFrameworks/PreviewsInjection.framework/PreviewsInjection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x765dc` | `0x79408` | **`+0x2e2c`** |
| `__TEXT.__eh_frame` | `0x5010` | `0x5428` | **`+0x418`** |
| `__TEXT.__const` | `0x52e0` | `0x54c0` | **`+0x1e0`** |
| `__DATA.__bss` | `0x4a00` | `0x4b80` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x1f10` | `0x2018` | **`+0x108`** |
| `__AUTH_CONST.__const` | `0x2180` | `0x2280` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x2491` | `0x2523` | **`+0x92`** |
| `__TEXT.__constg_swiftt` | `0x1ea8` | `0x1f1c` | **`+0x74`** |
| `__TEXT.__swift5_assocty` | `0x550` | `0x5b0` | **`+0x60`** |
| `__DATA.__data` | `0x17a8` | `0x17f8` | **`+0x50`** |
| `__AUTH.__data` | `0x1fd8` | `0x2020` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x3d8` | `0x420` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0xf73` | `0xfb3` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x2e0` | `0x31c` | **`+0x3c`** |
| `__TEXT.__swift_as_ret` | `0x218` | `0x254` | **`+0x3c`** |
| `__TEXT.__swift_as_cont` | `0x440` | `0x474` | **`+0x34`** |
| `__TEXT.__swift5_fieldmd` | `0x1180` | `0x11b0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x17b8` | `0x17d8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1988` | `0x1978` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x284` | `0x290` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x198` | `0x1a4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x998` | `0x990` | **`-0x8`** |

### Other Changes

```diff

-24.0.35.0.0
+24.0.37.0.0

-  Functions: 2238
-  Symbols:   1049
-  CStrings:  244
+  Functions: 2280
+  Symbols:   1058
+  CStrings:  245
Symbols:
+ _symbolic $s19PreviewsMessagingOS18TransportInterfaceP
+ _symbolic ScSy_____y_____GG 19PreviewsMessagingOS16TransportMessageO 0A9Injection30RegistryControlEventsInterface33_4D960DEADBC44D786C0400B9EA4B19DBLLV
+ _symbolic _____ 17PreviewsInjection19CFunctionEntryPointV0C18StreamingInterface33_E95E04C315EE45FA99EEDF5ECC8D74D8LLV
+ _symbolic _____ 17PreviewsInjection30RegistryControlEventsInterface33_4D960DEADBC44D786C0400B9EA4B19DBLLV
+ _symbolic _____ 17PreviewsInjection30RegistryRuntimeEventsInterface33_4D960DEADBC44D786C0400B9EA4B19DBLLV
+ _symbolic _____ 19PreviewsMessagingOS18AsyncMessageStreamV
+ _symbolic _____y_____G 19PreviewsMessagingOS16TransportMessageO 0A9Injection30RegistryControlEventsInterface33_4D960DEADBC44D786C0400B9EA4B19DBLLV
+ _symbolic _____y_____GSg 19PreviewsMessagingOS16TransportMessageO 0A9Injection30RegistryControlEventsInterface33_4D960DEADBC44D786C0400B9EA4B19DBLLV
+ _symbolic _____y______G 19PreviewsMessagingOS18AsyncMessageStreamV6SenderV 0A9Injection19CFunctionEntryPointV0I18StreamingInterface33_E95E04C315EE45FA99EEDF5ECC8D74D8LLV
+ _symbolic _____y______G 19PreviewsMessagingOS18AsyncMessageStreamV6SenderV 0A9Injection30RegistryRuntimeEventsInterface33_4D960DEADBC44D786C0400B9EA4B19DBLLV
+ _symbolic _____y______G6sender_t 19PreviewsMessagingOS18AsyncMessageStreamV6SenderV 0A9Injection19CFunctionEntryPointV0I18StreamingInterface33_E95E04C315EE45FA99EEDF5ECC8D74D8LLV
+ _symbolic _____y______G6sender_t 19PreviewsMessagingOS18AsyncMessageStreamV6SenderV 0A9Injection30RegistryRuntimeEventsInterface33_4D960DEADBC44D786C0400B9EA4B19DBLLV
+ _symbolic _____y_____y_____G_G ScS8IteratorV 19PreviewsMessagingOS16TransportMessageO 0B9Injection30RegistryControlEventsInterface33_4D960DEADBC44D786C0400B9EA4B19DBLLV
- _symbolic _____ 19PreviewsMessagingOS13MessageStreamV
- _symbolic _____y______G 19PreviewsMessagingOS13MessageStreamV6SenderV 0a10FoundationC012PropertyListV
- _symbolic _____y______G6sender_t 19PreviewsMessagingOS13MessageStreamV6SenderV 0a10FoundationC012PropertyListV
- _symbolic _____yq_G______pIegozo_ 20PreviewsFoundationOS6FutureC s5ErrorP
CStrings:
+ "Failed to acquire registry runtime events sender: %@"
+ "Failed to acquire sender for C function streaming output: %@"
- "ProductLoader NOT loading %{public}s because XOJIT has already loaded it from the shell (%s)"
```
