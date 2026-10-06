## APConfigurationSystem

> `/System/Library/PrivateFrameworks/APConfigurationSystem.framework/APConfigurationSystem`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a8c0` | `0x1b9f0` | **`+0x1130`** |
| `__DATA.__bss` | `0x3a80` | `0x4000` | **`+0x580`** |
| `__TEXT.__cstring` | `0x1290` | `0x1610` | **`+0x380`** |
| `__TEXT.__const` | `0x2a10` | `0x2cd8` | **`+0x2c8`** |
| `__AUTH_CONST.__const` | `0x15c8` | `0x1728` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0xbd9` | `0xcc9` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x950` | `0x9f8` | **`+0xa8`** |
| `__DATA.__data` | `0x868` | `0x8f8` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x938` | `0x9be` | **`+0x86`** |
| `__TEXT.__unwind_info` | `0x8d0` | `0x938` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x8c0` | `0x924` | **`+0x64`** |
| `__TEXT.__swift5_reflstr` | `0x5bf` | `0x61f` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x678` | `0x6c0` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0xf8` | `0xb8` | **`-0x40`** |
| `__TEXT.__swift5_proto` | `0x248` | `0x274` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x778` | `0x788` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xcc` | `0xd8` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x2e0` | `0x2e8` | **`+0x8`** |

### Other Changes

```diff

-557.1.16.0.0
+557.1.21.0.0

-  Functions: 876
+  Functions: 927

-  CStrings:  209
+  CStrings:  223
Symbols:
+ _OBJC_CLASS_$_NSDistributedNotificationCenter
- _swift_bridgeObjectRetain_n
CStrings:
+ "[EligibilitySnapshot] Received apAccountChanged — invalidating in-memory cache"
+ "[EligibilitySnapshot] Received snapshotChangedNotification — invalidating in-memory cache"
+ "[EligibilitySnapshot] Registering cross-process cache-invalidation observers (apAccountChanged + snapshotChangedNotification)"
+ "[EligibilitySnapshot] getSnapshot — UserDefaults missing, falling back to baked-in defaults (cold-cold path; daemon has not yet seeded)"
+ "[EligibilitySnapshot] getSnapshot — in-memory cache hit"
+ "[EligibilitySnapshot] getSnapshot — populated cache from UserDefaults"
+ "[EligibilitySnapshot] loadFromUserDefaults — JSON decode failed: %{public}s"
+ "[EligibilitySnapshot] loadFromUserDefaults — could not open suite %{public}s"
+ "[EligibilitySnapshot] loadFromUserDefaults — decoded snapshot from UserDefaults"
+ "[EligibilitySnapshot] loadFromUserDefaults — no data at key %{public}s"
+ "com.apple.ap.eligibilitySnapshot"
+ "com.apple.ap.eligibilitySnapshotChanged"
+ "educationModeEnabled"
+ "isEducationManagedAccount"
+ "kADIDManager_ChangedNotification"
- "com.apple.ap.poiConfig.refresh"
```
