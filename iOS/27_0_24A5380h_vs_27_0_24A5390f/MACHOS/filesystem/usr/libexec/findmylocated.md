## findmylocated

> `/usr/libexec/findmylocated`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x585adc` | `0x58cc9c` | **`+0x71c0`** |
| `__TEXT.__eh_frame` | `0x48098` | `0x487f0` | **`+0x758`** |
| `__TEXT.__unwind_info` | `0x15da8` | `0x16358` | **`+0x5b0`** |
| `__TEXT.__const` | `0x20718` | `0x20988` | **`+0x270`** |
| `__DATA.__bss` | `0x2e380` | `0x2e580` | **`+0x200`** |
| `__DATA.__objc_const` | `0x6278` | `0x6358` | **`+0xe0`** |
| `__TEXT.__cstring` | `0xb842` | `0xb922` | **`+0xe0`** |
| `__DATA.__data` | `0xefa0` | `0xf050` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x181c0` | `0x18270` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x18f2c` | `0x18fcc` | **`+0xa0`** |
| `__TEXT.__swift_as_cont` | `0x435c` | `0x43f4` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x70cc` | `0x7140` | **`+0x74`** |
| `__TEXT.__swift_as_ret` | `0x27f4` | `0x2864` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x8f84` | `0x8fdc` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x4d2c` | `0x4d74` | **`+0x48`** |
| `__TEXT.__swift_as_entry` | `0x16a4` | `0x16e8` | **`+0x44`** |
| `__TEXT.__swift5_reflstr` | `0x7e1d` | `0x7e5d` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x5cc0` | `0x5cf0` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x1276` | `0x12a6` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x4eb5` | `0x4ee5` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1d20` | `0x1d48` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x729c` | `0x72c2` | **`+0x26`** |
| `__DATA.__common` | `0x1408` | `0x1420` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x2e68` | `0x2e80` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1a58` | `0x1a70` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xf34` | `0xf4c` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x17d8` | `0x17e8` | **`+0x10`** |
| `__DATA.__objc_data` | `0x1428` | `0x1430` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xd58` | `0xd60` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x248` | `0x250` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x7f0` | `0x7f4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-141.30.6.14.2
+141.30.6.14.7

-  Functions: 17446
-  Symbols:   2870
-  CStrings:  3834
+  Functions: 17533
+  Symbols:   2879
+  CStrings:  3845
Symbols:
+ _$s10AppIntents11EntityQueryP22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKFTq
+ _$s10AppIntents11EntityQueryPAAE22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKF
+ _$s10AppIntents11EntityQueryPAAE22displayRepresentations3forSDy0C0_2IDQZAA21DisplayRepresentationVGSayAHG_tYaKFTu
+ _$s12FindMyLocate13LocationLabelOSHAAMc
+ _$s12FindMyLocate16LocationProtocolP31_fmltool_redonatePersonEntitiesyyYaKFTq
+ _$sSo17CSSearchableIndexC10AppIntentsE06deleteC8Entities6ofTypeyxm_tYaKAC13IndexedEntityRzlF
+ _$sSo17CSSearchableIndexC10AppIntentsE06deleteC8Entities6ofTypeyxm_tYaKAC13IndexedEntityRzlFTu
+ _NSCurrentLocaleDidChangeNotification
+ _xpc_transaction_exit_clean
CStrings:
+ "\nlabelledLocations: "
+ "$__lazy_storage_$_sharedKeyStorage"
+ "AppleLanguagePreferencesChangedNotification"
+ "BACKWARDS_COMPATIBILITY_ALERT_MESSAGE_GENERIC"
+ "LabelStore: applyRefresh save failed: %@"
+ "Locale/language change received. Exiting at next clean opportunity."
+ "LocaleChangeMonitor"
+ "LocaleChangeMonitor startup"
+ "Received Key: Unable to get following handles, so subscribing with intent to notify server of keys received %s"
+ "_TtC13findmylocated19LocaleChangeMonitor"
+ "_fmltool_redonatePersonEntities(completion:)"
+ "_fmltool_redonatePersonEntitiesWithCompletion:"
+ "biomeDonation: Writing Biome event for handle: %{private,mask.hash}s, publishReason: %{public}s"
+ "labels"
+ "receivedKeyForHandle"
- "Received Key: Unable to get following handles %{public}s,\nso subscribing with intent to notify server of keys received %s"
- "_receivedKeyForHandleMutex"
- "biomeDonation: Writing Biome event for handle: %s, publishReason: %{public}s"
- "sharedKeyStorage"
```
