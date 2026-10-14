## installd

> `/usr/libexec/installd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1a123` | `0x1a6b3` | **`+0x590`** |
| `__TEXT.__text` | `0x77948` | `0x77db8` | **`+0x470`** |
| `__DATA_CONST.__cfstring` | `0xae20` | `0xaf80` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0xe087` | `0xe0c7` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x9580` | `0x95a0` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x2b8` | `0x2d0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2a70` | `0x2a78` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1630` | `0x1628` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-  Functions: 1661
+  Functions: 1662

-  CStrings:  4081
+  CStrings:  4094
CStrings:
+ "\"%@\" does not have the wrapper bundle entitlement (\"%@\" = TRUE) which is required for apps within the App Clips management domain (those with entitlement \"%@\" = \"%@\", which this app has). All apps in the App Clips management domain must be wrapper bundles."
+ "\"%@\" has a Home extension, but the app itself does not have the required HomeKit (\"%@\" = TRUE) entitlement."
+ "\"%@\" has the entitlement \"%@\" = %@, but does not also have the required \"%@\" = TRUE entitlement to indicate that it is an App Clip. All apps in the App Clips management domain must be App Clips."
+ "\"%@\" has the entitlement \"%@\", which is only allowed on Home app extensions."
+ "The app extension at \"%@\" has the \"%@\" entitlement, which is not allowed on this app extension because it does not implement the \"%@\" extension point."
+ "The app extension at \"%@\" has the \"%@\" entitlement, which is not allowed on this app extension because it implements the \"%@\" extension point."
+ "The app extension at \"%@\" implements the \"%@\" extension point, but another app extension at \"%@\" also implements that same extension point. Only one app extension per app is allowed to implement the \"%@\" extension point."
+ "The app extension at \"%@\" is missing the required \"%@\" = TRUE entitlement. This entitlement is required on this app extension because it implements the \"%@\" extension point."
+ "_ValidateAppBundleEntitlements"
+ "com.apple.AppClips"
+ "com.apple.Home.HomeExtension"
+ "com.apple.developer.home"
+ "hasAtLeastOneExtensionImplementingExtensionPointIn:error:"
```
