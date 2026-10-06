## PodcastsWidgetKit

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsWidgetKit.framework/PodcastsWidgetKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62400` | `0x62f50` | **`+0xb50`** |
| `__TEXT.__auth_stubs` | `0x2c00` | `0x2c60` | **`+0x60`** |
| `__TEXT.__cstring` | `0xb48` | `0xba8` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1608` | `0x1638` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xd45` | `0xd75` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xd28` | `0xd4c` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0x13d0` | `0x13f0` | **`+0x20`** |
| `__DATA.__common` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA.__data` | `0x2c38` | `0x2c48` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.100.59.0.0
+4027.100.70.0.0

-  Functions: 1677
+  Functions: 1687

-  CStrings:  168
+  CStrings:  170
Symbols:
+ _os_feature_enabled_hlsrss
- _objc_retain_x26
CStrings:
+ "EPISODE_CAPTION_VIDEO"
+ "Received a show configuration without a show or uuid: %s"
+ "WIDGET_SHOW_WIDGET_NEEDS_TO_BE_RECONFIGURED_MESSAGE"
- "Received a show configuration without a uuid: %s"
```
