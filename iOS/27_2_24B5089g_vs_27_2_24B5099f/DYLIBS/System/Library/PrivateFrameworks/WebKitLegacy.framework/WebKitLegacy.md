## WebKitLegacy

> `/System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x164ed0` | `0x164e90` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x131d0` | `0x131bc` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0x46c8` | `0x46c0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7ec8` | `0x7ec0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0xf5f0` | `0xf5e8` | **`-0x8`** |

### Other Changes

```diff

-625.2.5.10.1
+625.2.7.1.0

-  Functions: 7315
-  Symbols:   13062
+  Functions: 7314
+  Symbols:   13060
Symbols:
- +[WebCoreStatistics garbageCollectJavaScriptObjectsOnAlternateThreadForDebugging:]
- __ZN7WebCore27GarbageCollectionController43garbageCollectOnAlternateThreadForDebuggingEb
Functions:
~ -[DOMElement focus] : 172 -> 176
- +[WebCoreStatistics setJavaScriptGarbageCollectorTimerEnabled:]
~ +[WebPreferences initialize] : 13036 -> 13028
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 23952 -> 23948
```
