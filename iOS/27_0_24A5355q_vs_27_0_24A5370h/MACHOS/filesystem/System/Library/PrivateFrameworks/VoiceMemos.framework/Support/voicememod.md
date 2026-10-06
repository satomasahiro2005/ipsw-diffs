## voicememod

> `/System/Library/PrivateFrameworks/VoiceMemos.framework/Support/voicememod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49988` | `0x497c8` | **`-0x1c0`** |
| `__TEXT.__oslogstring` | `0x3348` | `0x32d8` | **`-0x70`** |
| `__TEXT.__eh_frame` | `0x1a90` | `0x1a58` | **`-0x38`** |
| `__TEXT.__cstring` | `0x39df` | `0x39af` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0x5ea0` | `0x5e80` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x17e4` | `0x17d4` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x6bd8` | `0x6bc8` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1af0` | `0x1ae8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x790` | `0x788` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1428.0.0.0.0
+1431.0.0.0.0

-  Functions: 1344
-  Symbols:   721
-  CStrings:  1738
+  Functions: 1342
+  Symbols:   720
+  CStrings:  1735
Symbols:
+ _NSPersistentStoreRemoteChangeNotificationPostOptionKey
- _NSXPCStorePostUpdateNotificationsKey
- _RCCloudRecording_AudioFutureFlags
CStrings:
- "%s -- Import change inconsistency versionedAudioFutureUpdated: %{public}i, audioFutureFlagsUpdated: %{public}i"
- "-[SavedRecordingService _validateUpdate:]"
- "_validateUpdate:"
```
