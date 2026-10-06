## PodcastsSuggestedDonations

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsSuggestedDonations.framework/PodcastsSuggestedDonations`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbfe8` | `0xc3c0` | **`+0x3d8`** |
| `__TEXT.__auth_stubs` | `0xaf0` | `0xb30` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x580` | `0x5a0` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x620` | `0x618` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4027.100.75.0.0
+4027.100.80.0.0
Functions:
~ sub_3dec : 1132 -> 1408
~ sub_4258 -> sub_436c : 2196 -> 2308
~ sub_4bfc -> sub_4d80 : 2016 -> 2120
~ sub_5504 -> sub_56f0 : 4748 -> 4856
~ sub_6790 -> sub_69e8 : 340 -> 352
~ sub_68e4 -> sub_6b48 : 1132 -> 1188
~ sub_6d50 -> sub_6fec : 2104 -> 2208
~ sub_7588 -> sub_788c : 2104 -> 2208
~ sub_7dc0 -> sub_812c : 1196 -> 1304
CStrings:
+ "Successfully donated %ld episodes using RelevantEntities"
+ "SuggestedDonationsSupport: Failed to donate suggested episodes using RelevantEntities: %@"
- "Successfully donated %ld episodes using EntityDonationManager"
- "SuggestedDonationsSupport: Failed to donate suggested episodes using EntityDonationManager: %@"
```
