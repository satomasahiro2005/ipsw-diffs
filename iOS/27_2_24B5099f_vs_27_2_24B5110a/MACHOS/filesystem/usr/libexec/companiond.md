## companiond

> `/usr/libexec/companiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8c068` | `0x8dc2c` | **`+0x1bc4`** |
| `__DATA.__objc_const` | `0x7568` | `0x7988` | **`+0x420`** |
| `__TEXT.__objc_methname` | `0x61a5` | `0x6475` | **`+0x2d0`** |
| `__TEXT.__objc_methlist` | `0x2b60` | `0x2d30` | **`+0x1d0`** |
| `__TEXT.__gcc_except_tab` | `0x1ad0` | `0x1c50` | **`+0x180`** |
| `__TEXT.__cstring` | `0x2621` | `0x2789` | **`+0x168`** |
| `__DATA_CONST.__cfstring` | `0x1ba0` | `0x1ce0` | **`+0x140`** |
| `__TEXT.__objc_stubs` | `0x4460` | `0x45a0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x4142` | `0x426e` | **`+0x12c`** |
| `__DATA.__objc_data` | `0x18e0` | `0x1980` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x1560` | `0x15e0` | **`+0x80`** |
| `__TEXT.__objc_methtype` | `0x159b` | `0x15fd` | **`+0x62`** |
| `__TEXT.__unwind_info` | `0x2558` | `0x25b0` | **`+0x58`** |
| `__TEXT.__objc_classname` | `0xb48` | `0xb9b` | **`+0x53`** |
| `__DATA_CONST.__const` | `0x2538` | `0x2580` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x414` | `0x440` | **`+0x2c`** |
| `__DATA_CONST.__objc_classlist` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x198` | `0x1a8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2d40` | `0x2d50` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x16b0` | `0x16b8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xcf8` | `0xd00` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-524.10.109.0.1
+524.11.6.0.0

-  Functions: 2295
-  Symbols:   1269
-  CStrings:  1956
+  Functions: 2341
+  Symbols:   1271
+  CStrings:  1997
Symbols:
+ _CPSAllowedClassesForPhotosConfiguration
+ _OBJC_CLASS_$_CPSPhotosConfigurationRequest
CStrings:
+ "@\"<CPSPhotosConfiguration>\""
+ "@\"CPSPhotosConfigurationRequest\""
+ "CDPhotosConfigurationDidFinishAuthRequest"
+ "CDPhotosConfigurationGetAuthInfoResponse"
+ "CompanionViewService.PhotosConfigurationViewController"
+ "Missing configuration in get auth info response: %@"
+ "PHOTOS_CONFIGURATION_BODY"
+ "PHOTOS_CONFIGURATION_TITLE"
+ "Photos configuration completion {configuration = %@, error = %@}"
+ "Starting Photos Configuration session."
+ "T@\"<CPSPhotosConfiguration>\",C,N,V_configuration"
+ "T@\"CPSPhotosConfigurationRequest\",&,N,V_photosConfigurationRequest"
+ "T@?,C,N,V_photosConfigurationCompletionHandler"
+ "[decodedResponse configuration]"
+ "_photosConfigurationCompletionHandler"
+ "_photosConfigurationRequest"
+ "_photosConfigurationUserNotificationSessionWithGetAuthInfoResponse:"
+ "_presentPhotosConfigurationViewService:proxCardClient:"
+ "_typeIdentifierForDevice:"
+ "appletv"
+ "com.apple.companion-authentication.photos-configuration"
+ "com.apple.homeaccessory-1"
+ "com.apple.homeaccessory-2"
+ "hasPhotosConfigurationEntitlement"
+ "initWithConfiguration:"
+ "localizedDescription"
+ "person.badge.waveform.fill"
+ "photoSetupContentWithTypeIdentifier:"
+ "photos configuration session/handle get auth info response"
+ "photos configuration session/present view service"
+ "photos configuration session/start"
+ "photosConfigurationCompletionHandler"
+ "photosConfigurationContent"
+ "photosConfigurationFailedWithError:"
+ "photosConfigurationFinishedWithConfiguration:"
+ "photosConfigurationObject"
+ "photosConfigurationRequest"
+ "setConfiguration:"
+ "setPhotosConfigurationCompletionHandler:"
+ "setPhotosConfigurationRequest:"
+ "typeWithIdentifier:"
+ "v24@0:8@\"<CPSPhotosConfiguration>\"16"
+ "v24@?0@\"<CPSPhotosConfiguration>\"8@\"NSError\"16"
- "photoSetupContent"
- "siri-icon"
```
