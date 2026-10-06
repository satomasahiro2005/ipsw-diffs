## AgentCanvasPersistence

> `/System/Library/PrivateFrameworks/AgentCanvasPersistence.framework/AgentCanvasPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65f5c` | `0x69d10` | **`+0x3db4`** |
| `__TEXT.__oslogstring` | `0x6cb` | `0x86b` | **`+0x1a0`** |
| `__TEXT.__eh_frame` | `0x3668` | `0x37a8` | **`+0x140`** |
| `__AUTH_CONST.__auth_got` | `0xdb0` | `0xe58` | **`+0xa8`** |
| `__DATA.__data` | `0xdb0` | `0xe58` | **`+0xa8`** |
| `__TEXT.__const` | `0x6640` | `0x66b0` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1f20` | `0x1f88` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x16d4` | `0x1738` | **`+0x64`** |
| `__TEXT.__cstring` | `0xce4` | `0xd34` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x4350` | `0x4378` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0xa90` | `0xab0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x240` | `0x250` | **`+0x10`** |

### Other Changes

```diff

-73.0.5.102.0
+73.0.12.0.0

-  Functions: 3275
-  Symbols:   1070
-  CStrings:  126
+  Functions: 3317
+  Symbols:   1081
+  CStrings:  133
Symbols:
+ _OBJC_CLASS_$_NSJSONSerialization
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ ___swift_project_boxed_opaque_existential_0Tm
+ __swiftEmptyDictionarySingleton
+ _symbolic SDySSypG
+ _symbolic SS3key_yp5valuet
+ _symbolic ______p 10Foundation15ContiguousBytesP
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation4DataV
+ _symbolic _____ySSypG s17_NativeDictionaryV
+ _symbolic _____y_____SgG s23_ContiguousArrayStorageC 10Foundation4DataV
+ _symbolic yp4json_Sb7changedt
CStrings:
+ "AgentMediaFallbackImageDataStripper"
+ "Command archiving failed for %{private}s"
+ "Deep copy failed; persisting response with %ld fallbackImageData bytes across %ld snippet(s) intact"
+ "Marker bytes present but modelData did not parse as JSON; leaving snippet unchanged"
+ "Stripped fallbackImageData from %ld snippet(s), removed %ld bytes before persistence"
+ "Stripped model failed to re-encode; leaving snippet unchanged"
+ "snippetPluginItem"
```
