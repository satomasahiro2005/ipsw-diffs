## BackgroundAssets

> `/System/Library/Frameworks/BackgroundAssets.framework/BackgroundAssets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f52c` | `0x90c34` | **`+0x1708`** |
| `__TEXT.__oslogstring` | `0x4558` | `0x4738` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x2970` | `0x2ac8` | **`+0x158`** |
| `__TEXT.__const` | `0x2f28` | `0x3028` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x819` | `0x8e9` | **`+0xd0`** |
| `__AUTH.__data` | `0xad0` | `0xb70` | **`+0xa0`** |
| `__DATA.__bss` | `0x3be0` | `0x3c60` | **`+0x80`** |
| `__TEXT.__cstring` | `0x41dd` | `0x424a` | **`+0x6d`** |
| `__TEXT.__swift5_fieldmd` | `0x8cc` | `0x930` | **`+0x64`** |
| `__AUTH_CONST.__const` | `0x1ea8` | `0x1e60` | **`-0x48`** |
| `__DATA.__data` | `0x1360` | `0x13a8` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x11dd` | `0x121f` | **`+0x42`** |
| `__AUTH_CONST.__auth_got` | `0xf68` | `0xfa8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xc34` | `0xc60` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x5d0` | `0x5e8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1438` | `0x1450` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0xad0` | `0xae0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1af0` | `0x1ae0` | **`-0x10`** |
| `__DATA.__common` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xf8` | `0x100` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x41a8` | `0x41a0` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1dc` | `0x1e0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xb8` | `0xbc` | **`+0x4`** |

### Other Changes

```diff

-268.0.0.502.1
+271.0.0.0.0

+  - /System/Library/PrivateFrameworks/StorageContainersPrivate.framework/StorageContainersPrivate

-  Functions: 1961
-  Symbols:   1501
-  CStrings:  587
+  Functions: 1963
+  Symbols:   1512
+  CStrings:  593
Symbols:
+ -[NSDictionary(BAInfoDictionary) infoDictionaryHasManagedAssetPacks]
+ -[NSDictionary(BAInfoDictionary) infoDictionaryUsesAppleHosting]
+ -[NSUserDefaults(BAContainers) initWithSuiteName:inContainerAtURL:]
+ __DATA__TtC16BackgroundAssets16DefaultsProvider
+ __IVARS__TtC16BackgroundAssets16DefaultsProvider
+ __METACLASS_DATA__TtC16BackgroundAssets16DefaultsProvider
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDictionary_$_BAInfoDictionary
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSUserDefaults_$_BAContainers
+ __OBJC_$_CATEGORY_NSDictionary_$_BAInfoDictionary
+ __OBJC_$_CATEGORY_NSUserDefaults_$_BAContainers
+ ___swift_memcpy56_8
+ ___swift_memcpy88_8
+ _get_enum_tag_for_layout_string 16BackgroundAssets21LanguageSettingsError33_6C5541F1816FD7A3A389821E40FD73D9LLO
+ _get_type_metadata 15Synchronization5MutexVySo14NSUserDefaultsCG noncopyable
+ _swift_release_x9
+ _symbolic SS8withName_t
+ _symbolic _____ 16BackgroundAssets16DefaultsProviderC
+ _symbolic _____Sg 16BackgroundAssets16DefaultsProviderC
+ _symbolic _____ySo14NSUserDefaultsCG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 0C17ContainersPrivate5QueryC7OptionsO
- -[NSDictionary(ManagedBackgroundAssets) infoDictionaryHasManagedAssetPacks]
- -[NSDictionary(ManagedBackgroundAssets) infoDictionaryUsesAppleHosting]
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDictionary_$_ManagedBackgroundAssets
- __OBJC_$_CATEGORY_NSDictionary_$_ManagedBackgroundAssets
- ___swift_closure_destructor.6Tm
- ___swift_memcpy48_8
- ___swift_memcpy80_8
- _swift_bridgeObjectRetain_n
- _symbolic SS4name_t
CStrings:
+ "<Defaults Provider | Defaults: "
+ "Init bundle ID: %{public}s app group ID: %{public}s defaults provider: %{public}s source: %{public}s managed: %{bool}d helper: %{public}s"
+ "Init bundle ID: %{public}s defaults provider: %{public}s source: %{public}s managed: %{bool}d helper: %{public}s"
+ "Initializing a fallback defaults provider…"
+ "Language settings for the app with the bundle ID “%s” couldn’t be initialized: %{public}@"
+ "Resetting the resolved language…"
+ "Setting the resolved language to %s…"
+ "The URL for the container with the ID “"
+ "The defaults suite that’s named “"
- "App group ID"
- "Defaults"
- "The defaults suite named “"
```
