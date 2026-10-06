## _OnDeviceStorage_JetEngine

> `/System/Library/PrivateFrameworks/_OnDeviceStorage_JetEngine.framework/_OnDeviceStorage_JetEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f52c` | `0x2e8d4` | **`-0xc58`** |
| `__TEXT.__oslogstring` | `0xe7` | `0x333` | **`+0x24c`** |
| `__AUTH_CONST.__const` | `0x2028` | `0x2140` | **`+0x118`** |
| `__TEXT.__eh_frame` | `0x1c08` | `0x1c50` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0xbb0` | `0xbf8` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0xa40` | `0xa08` | **`-0x38`** |
| `__DATA.__common` | `0x90` | `0x60` | **`-0x30`** |
| `__TEXT.__const` | `0x1018` | `0x1048` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xa88` | `0xab0` | **`+0x28`** |
| `__DATA.__bss` | `0x6a0` | `0x690` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0xe5b` | `0xe6b` | **`+0x10`** |
| `__DATA.__data` | `0x700` | `0x6f8` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3.0.59.0.0
+3.1.10.0.0

-  Functions: 820
-  Symbols:   545
-  CStrings:  79
+  Functions: 836
+  Symbols:   548
+  CStrings:  89
Symbols:
+ ___swift_closure_destructor.17Tm
+ ___swift_closure_destructor.25Tm
+ ___swift_closure_destructor.41Tm
+ __swiftImmortalRefCount
+ _memcpy
+ _swift_bridgeObjectRelease_n
+ _swift_unknownObjectRetain
+ _symbolic So8NSObjectCSg
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
- ___swift_allocate_boxed_opaque_existential_0
- ___swift_closure_destructor.19Tm
- ___swift_closure_destructor.27Tm
- ___swift_closure_destructor.43Tm
- _swift_getMetatypeMetadata
- _symbolic _____y_____G s23_ContiguousArrayStorageC 18OnDeviceFoundation10LogMessageV
CStrings:
+ "Could not convert <%{public}s> into JavaScript error, reason: %{public}s"
+ "Failed to reject promise, reason: %{public}s; JS error: %{public}@"
+ "Failed to resolve promise, reason: %{public}s"
+ "Reusing cached connection for %{public}s"
+ "error from message"
+ "error(message:in:)"
+ "errorOrNil(message:in:)"
+ "expected a string profile id, received: "
+ "int32OrNil(_:in:)"
+ "newObject(in:)"
+ "object(_:in:)"
+ "objectOrNil(_:in:)"
+ "promise resolved with result"
+ "promise(in:executor:)"
+ "resolvedPromise(with:in:)"
+ "undefined(in:)"
+ "🧨 JavaScriptCore returned nil for %{public}s in %{public}s — the JS context is no longer usable (stack torn down mid-call); reporting to JavaScript instead of trapping"
+ "🧨 JavaScriptCore returned nil for %{public}s in %{public}s — the JS context is no longer usable (stack torn down mid-call); skipping the call"
- "> into JavaScript error, reason: "
- "Could not convert <"
- "Failed to reject promise, reason: "
- "Failed to resolve promise, reason: "
- "Reusing cached connection for "
- "Unable to create new JS value in context"
- "Unable to create new JavaScript error"
- "expected a string user id, received: "
```
