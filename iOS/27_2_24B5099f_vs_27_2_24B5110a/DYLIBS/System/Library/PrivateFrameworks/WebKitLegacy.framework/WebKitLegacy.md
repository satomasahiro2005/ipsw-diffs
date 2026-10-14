## WebKitLegacy

> `/System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1c8e0` | `0x1c9db` | **`+0xfb`** |
| `__TEXT.__text` | `0x164e90` | `0x164f30` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xf600` | `0xf680` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x131bc` | `0x131c0` | **`+0x4`** |

### Other Changes

```diff

-625.2.7.1.0
+625.2.8.10.4

-  CStrings:  2306
+  CStrings:  2310
Symbols:
+ __ZN7WebCore24DeprecatedGlobalSettings37setMediaResourceLoadTimeoutForTestingEj
- _objc_release_x28
Functions:
~ +[WebPreferences initialize] : 13028 -> 13044
~ +[WebPreferences(WebPrivateInternalFeatures) _internalFeatures] : 14664 -> 14788
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 23948 -> 23968
CStrings:
+ "Media Resource Load Timeout For Testing"
+ "MediaResourceLoadTimeoutForTesting"
+ "Test override for the timeout applied to each media resource load serviced by WebKit, in milliseconds (0 means use production default)"
+ "WebKitMediaResourceLoadTimeoutForTesting"
```
