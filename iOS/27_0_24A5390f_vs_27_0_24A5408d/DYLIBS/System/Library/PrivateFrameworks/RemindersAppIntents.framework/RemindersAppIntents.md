## RemindersAppIntents

> `/System/Library/PrivateFrameworks/RemindersAppIntents.framework/RemindersAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27b29c` | `0x27f554` | **`+0x42b8`** |
| `__TEXT.__eh_frame` | `0xeefc` | `0xf32c` | **`+0x430`** |
| `__DATA.__bss` | `0x17e20` | `0x18020` | **`+0x200`** |
| `__TEXT.__const` | `0x15f34` | `0x16074` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x8688` | `0x87b0` | **`+0x128`** |
| `__AUTH_CONST.__const` | `0x9830` | `0x9938` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0x66f3` | `0x67c3` | **`+0xd0`** |
| `__TEXT.__swift5_assocty` | `0x2350` | `0x23b0` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x4074` | `0x40d0` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x1ec8` | `0x1f20` | **`+0x58`** |
| `__TEXT.__swift_as_cont` | `0xdb0` | `0xdf4` | **`+0x44`** |
| `__AUTH.__data` | `0x2370` | `0x23b0` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x4bdf` | `0x4c1f` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x82fc` | `0x833a` | **`+0x3e`** |
| `__TEXT.__constg_swiftt` | `0x4408` | `0x4440` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0x850` | `0x874` | **`+0x24`** |
| `__DATA.__data` | `0x5020` | `0x5040` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x111c` | `0x112c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x988` | `0x990` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x400` | `0x408` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x7f8` | `0x7fc` | **`+0x4`** |

### Other Changes

```diff

-4043.0.0.0.0
+4046.11.0.0.0

+  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 10914
-  Symbols:   3065
-  CStrings:  1443
+  Functions: 10981
+  Symbols:   3073
+  CStrings:  1445
Symbols:
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ __swift_FORCE_LOAD_$_swiftAppleArchive_$_RemindersAppIntents
+ _associated conformance 19RemindersAppIntents011CreateGroupB20IntentRepresentationVAA05TypedbF13RepresentableAA8BaseTypeAaDP_0bC00bF0
+ _associated conformance 19RemindersAppIntents011UpdateGroupB20IntentRepresentationVAA05TypedbF13RepresentableAA8BaseTypeAaDP_0bC00bF0
+ _symbolic _____ 19RemindersAppIntents011CreateGroupB20IntentRepresentationV
+ _symbolic _____ 19RemindersAppIntents011UpdateGroupB20IntentRepresentationV
+ _symbolic _____ySay_____GSgG 18AppIntentsServices15IntentParameterC 09RemindersaB024ListEntityRepresentationC
+ _symbolic _____y_____G 18AppIntentsServices15IntentParameterC 09RemindersaB025GroupEntityRepresentationC
CStrings:
+ "[CreateGroupAppIntent] Attempt to create a group with a shared-to-me list: %{public}@"
+ "[UpdateGroupIntentPerforming] Attempt to update a group with a group: %{public}@"
+ "[UpdateGroupIntentPerforming] Attempt to update a group with a shared-to-me list: %{public}@"
- "[CreateGroupAppIntent] Attempt to create a group with a shared list: %{public}@"
```
