## RemindersWidgetExtension

> `/private/var/staged_system_apps/Reminders.app/PlugIns/RemindersWidgetExtension.appex/RemindersWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9290` | `0xe04a4` | **`+0x7214`** |
| `__DATA.__bss` | `0xa650` | `0xaa50` | **`+0x400`** |
| `__TEXT.__oslogstring` | `0x14aa` | `0x17fa` | **`+0x350`** |
| `__TEXT.__const` | `0x9374` | `0x9604` | **`+0x290`** |
| `__DATA.__data` | `0x5398` | `0x5580` | **`+0x1e8`** |
| `__TEXT.__auth_stubs` | `0x3d80` | `0x3ef0` | **`+0x170`** |
| `__DATA_CONST.__const` | `0x2a90` | `0x2bd8` | **`+0x148`** |
| `__TEXT.__objc_stubs` | `0x840` | `0x980` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x64a` | `0x757` | **`+0x10d`** |
| `__TEXT.__constg_swiftt` | `0x2400` | `0x24e0` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x528` | `0x600` | **`+0xd8`** |
| `__TEXT.__swift5_typeref` | `0xc594` | `0xc64e` | **`+0xba`** |
| `__DATA_CONST.__auth_got` | `0x1ec8` | `0x1f80` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x1a0c` | `0x1abc` | **`+0xb0`** |
| `__DATA_CONST.__auth_ptr` | `0x1190` | `0x1228` | **`+0x98`** |
| `__TEXT.__cstring` | `0x3a69` | `0x3af9` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x2820` | `0x28b0` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x2968` | `0x29e8` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x61c` | `0x68c` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x123a` | `0x12aa` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x210` | `0x260` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x1a8` | `0x1e8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xe00` | `0xe28` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x52c` | `0x550` | **`+0x24`** |
| `__TEXT.__swift5_types` | `0x264` | `0x274` | **`+0x10`** |
| `__DATA.__common` | `0x368` | `0x370` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x18` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4046.11.0.0.0
+4076.0.0.0.0

+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 3373
-  Symbols:   235
-  CStrings:  398
+  Functions: 3437
+  Symbols:   239
+  CStrings:  423
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
+ _OBJC_CLASS_$_REMAccount
+ __REMGetLocalizedString
+ _swift_getMetatypeMetadata
CStrings:
+ "%{public}s: configuration names the local account's default list; following the user's default list instead {objectID: %{public}@}"
+ "%{public}s: could not decode record {objectID: %{public}@, error: %{public}s}"
+ "%{public}s: could not encode record {objectID: %{public}@, error: %{public}s}"
+ "%{public}s: dropping a record that could not be decoded {key: %{public}s, error: %{public}s}"
+ "%{public}s: list has been unfetchable past the grace period; using the default list {objectID: %{public}@, failingFor: %{public}f}"
+ "TTRNewWidgetInteractor looked for the list in deactivated accounts {objectID: %{public}s, exists: %{bool,public}d}"
+ "TTRNewWidgetInteractor: could not look for the list in deactivated accounts {objectID: %{public}s, error: %{public}s}"
+ "TTRWidgetListFetchState."
+ "TTRWidgetListFetchState.lastPrune"
+ "Widget presenter: %{public}s is in a deactivated account, so it cannot return; showing the default list {objectID: %{public}@}"
+ "Widget presenter: %{public}s is not expected to return; showing the default list {objectID: %{public}@}"
+ "Widget presenter: %{public}s unavailable but expected to return; showing placeholder instead of the default list {objectID: %{public}@}"
+ "Widget presenter: Could not fetch %{public}s {objectID: %{public}@ error: %{public}s}"
+ "Widget presenter: no list exists to show as the default; showing an empty list"
+ "_TtC24RemindersWidgetExtension28TTRWidgetListFetchStateStore"
+ "custom smart list"
+ "dataForKey:"
+ "dictionaryRepresentation"
+ "fetchAccountsIncludingInactive:error:"
+ "fetchListsWithError:"
+ "firstFailureOfCurrentRun"
+ "inactive"
+ "initWithSuiteName:"
+ "listFetchStateTracker"
+ "localAccountDefaultListID"
+ "objectForKey:"
+ "removeObjectForKey:"
+ "setObject:forKey:"
+ "userDefaults"
- "Widget presenter: Could not fetch custom smart list {customSmartListID: %{public}@ error: %{public}s}"
- "Widget presenter: Could not fetch list {listID: %{public}@ error: %{public}s}"
- "Widget presenter: custom smart list unavailable (likely transient); showing placeholder instead of the default list {customSmartListID: %{public}@}"
- "Widget presenter: list unavailable (likely transient — store loading or revalidating); showing placeholder instead of the default list {listID: %{public}@}"
```
