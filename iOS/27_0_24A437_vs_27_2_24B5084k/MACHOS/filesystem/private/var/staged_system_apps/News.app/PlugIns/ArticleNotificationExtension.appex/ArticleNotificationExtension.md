## ArticleNotificationExtension

> `/private/var/staged_system_apps/News.app/PlugIns/ArticleNotificationExtension.appex/ArticleNotificationExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fd4` | `0x206c` | **`+0x98`** |
| `__TEXT.__objc_methname` | `0xfa6` | `0xff2` | **`+0x4c`** |
| `__TEXT.__objc_stubs` | `0xaa0` | `0xac0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x420` | `0x430` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x374` | `0x37c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x118` | `0x120` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

-  Functions: 59
+  Functions: 60

-  CStrings:  231
+  CStrings:  233
Functions:
~ sub_100002188 : 92 -> 152
+ sub_100002220
CStrings:
+ "preferredContentSize"
+ "preferredContentSizeDidChangeForChildContentContainer:"
```
