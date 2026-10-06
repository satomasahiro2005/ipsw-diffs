## VideosUIEngagementExtension

> `/System/Library/ExtensionKit/Extensions/VideosUIEngagementExtension.appex/VideosUIEngagementExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa584` | `0xa508` | **`-0x7c`** |
| `__TEXT.__auth_stubs` | `0x770` | `0x730` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x3c0` | `0x3a0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x11d8` | `0x11f0` | **`+0x18`** |
| `__DATA.__data` | `0x428` | `0x418` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x2a3` | `0x2a8` | **`+0x5`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1138.0.0.0.2
+1143.0.0.0.2

-  - /System/Library/PrivateFrameworks/TVAppServices.framework/TVAppServices
+  - /System/Library/PrivateFrameworks/iTunesCloud.framework/iTunesCloud

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftCoreAudio.dylib

+  - /usr/lib/swift/libswiftCoreImage.dylib

-  Symbols:   101
+  Symbols:   103
Symbols:
+ _OBJC_CLASS_$_ICUserIdentity
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ _objc_release_x25
- _OBJC_CLASS_$_NSNumber
- _objc_release_x24
- _objc_retain
Functions:
~ sub_10000269c -> sub_10000276c : 2648 -> 2632
~ sub_1000040d4 -> sub_100004194 : 280 -> 276
~ sub_1000056f4 -> sub_1000057b0 : 464 -> 452
~ sub_1000058c4 -> sub_100005974 : 352 -> 348
~ sub_100005a24 -> sub_100005ad0 : 412 -> 396
~ sub_100005f48 -> sub_100005fe4 : 1080 -> 924
~ sub_100006404 : 68 -> 100
~ sub_100006448 -> sub_100006468 : 100 -> 68
~ sub_1000064ac : 72 -> 76
~ sub_10000659c -> sub_1000065a0 : 340 -> 352
~ sub_100006744 -> sub_100006754 : 236 -> 256
~ sub_100006958 -> sub_10000697c : 1344 -> 1392
CStrings:
+ "accountDSID"
+ "activeAccount"
- "ams_DSID"
- "stringValue"
```
