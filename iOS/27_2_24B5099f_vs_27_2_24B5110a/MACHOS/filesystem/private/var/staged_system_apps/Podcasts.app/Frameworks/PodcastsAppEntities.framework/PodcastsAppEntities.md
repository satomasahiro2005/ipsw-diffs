## PodcastsAppEntities

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsAppEntities.framework/PodcastsAppEntities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63fb8` | `0x643f4` | **`+0x43c`** |
| `__TEXT.__oslogstring` | `0x76c` | `0x80c` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x21a0` | `0x21d0` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x10d8` | `0x10f0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x568` | `0x578` | **`+0x10`** |
| `__DATA.__data` | `0x2038` | `0x2040` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4027.200.32.0.0
+4027.210.1.0.0

-  CStrings:  246
+  CStrings:  248
Functions:
~ sub_50a5c : 4068 -> 5152
CStrings:
+ "EpisodeEntity %{private,mask.hash}s: no artwork available"
+ "EpisodeEntity %{private,mask.hash}s: no podcast artwork, falling back to episode artwork"
```
