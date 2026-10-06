## gamepolicyd

> `/usr/libexec/gamepolicyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42724` | `0x4a854` | **`+0x8130`** |
| `__DATA.__data` | `0x2100` | `0x2390` | **`+0x290`** |
| `__TEXT.__cstring` | `0x1014` | `0x11a7` | **`+0x193`** |
| `__DATA.__objc_const` | `0x2198` | `0x22d8` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0xbfb` | `0xd1e` | **`+0x123`** |
| `__TEXT.__oslogstring` | `0x13ff` | `0x151b` | **`+0x11c`** |
| `__TEXT.__auth_stubs` | `0x21c0` | `0x22d0` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x1418` | `0x14ec` | **`+0xd4`** |
| `__TEXT.__eh_frame` | `0x968` | `0xa18` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x938` | `0x9e0` | **`+0xa8`** |
| `__TEXT.__const` | `0x1470` | `0x1508` | **`+0x98`** |
| `__DATA_CONST.__auth_got` | `0x10f0` | `0x1178` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0xa00` | `0xa80` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0xe5a` | `0xeb3` | **`+0x59`** |
| `__TEXT.__objc_methname` | `0x200f` | `0x205f` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0xf20` | `0xf60` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x72a` | `0x75c` | **`+0x32`** |
| `__DATA_CONST.__auth_ptr` | `0x3d8` | `0x400` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x18f0` | `0x1918` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x610` | `0x628` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x7f4` | `0x804` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xcd8` | `0xcc8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x68` | `0x70` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4.0.5.0.0
+4.0.6.0.0

-  Functions: 919
-  Symbols:   772
-  CStrings:  598
+  Functions: 970
+  Symbols:   791
+  CStrings:  629
Symbols:
+ _$s10Foundation3URLV6stringACSgSSh_tcfC
+ _$s10Foundation3URLVMn
+ _$s10Foundation4DateV18addingTimeIntervalyACSdF
+ _$s2os12OSSignpostIDV8rawValues6UInt64Vvg
+ _$s2os12OSSignposterV9logHandleACSo03OS_a1_C0C_tcfC
+ _$s2os12OSSignposterV9logHandleSo03OS_a1_C0Cvg
+ _$s2os12OSSignposterVMa
+ _$s2os15OSSignpostErrorO9doubleEndyA2CmFWC
+ _$s2os15OSSignpostErrorOMa
+ _$s2os23OSSignpostIntervalStateC10signpostIDAA0bF0Vvg
+ _$s2os23OSSignpostIntervalStateC2id6isOpenAcA0B2IDV_Sbtcfc
+ _$s2os23OSSignpostIntervalStateCMa
+ _$s2os28checkForErrorAndConsumeState5stateAA010OSSignpostD0OAA0i8IntervalG0C_tF
+ _$s2os6LoggerV20GamePolicyFoundationE22gameLibraryPerformanceSo03OS_A4_logCvgZ
+ _$sSaMa
+ _$sSo17NSKeyedUnarchiverC10FoundationE16unarchivedObject7ofClass4fromxSgxm_AC4DataVtKSo8NSObjectCRbzSo8NSCodingRzlFZ
+ _$sSo9OS_os_logC0B0E16signpostsEnabledSbvg
+ __os_signpost_emit_with_name_impl
+ _swift_allocBox
CStrings:
+ "%ld entries"
+ "%ld games"
+ "%ld identifiers"
+ "%ld records"
+ "All library caches cleared."
+ "CacheLoadFromDisk"
+ "CacheMaintenance"
+ "CacheWriteToDisk"
+ "Clearing all library caches."
+ "CreateGameLibraryGames"
+ "EnumerateInstalledGames"
+ "Evicted %ld stale metadata hint cache entries."
+ "FetchApps(adamIDs)"
+ "FetchApps(bundleIDs)"
+ "LibraryRefresh"
+ "LoadInstalledGamesFromDisk"
+ "Loaded %ld metadata hint cache entries from disk."
+ "Metadata hints cache cleared."
+ "WriteInstalledGamesToDisk"
+ "[Error] Interval already ended"
+ "_TtC11gamepolicyd22GameMetadataHintsCache"
+ "arrayForKey:"
+ "cacheKey"
+ "entries"
+ "gameMetadataHintsCache"
+ "metadataHintsCache"
+ "modificationDate"
+ "removeObjectForKey:"
+ "requestClearLibraryCache"
+ "requestClearLibraryCacheWithReply:"
+ "ttl"
```
