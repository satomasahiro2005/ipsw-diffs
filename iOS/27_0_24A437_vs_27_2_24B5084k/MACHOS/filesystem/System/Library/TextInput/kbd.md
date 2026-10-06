## kbd

> `/System/Library/TextInput/kbd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x19e5` | `0x183d` | **`-0x1a8`** |
| `__TEXT.__text` | `0xeaf8` | `0xec28` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0xbff` | `0xc9b` | **`+0x9c`** |
| `__TEXT.__objc_methname` | `0x340f` | `0x3458` | **`+0x49`** |
| `__DATA_CONST.__const` | `0x6e0` | `0x728` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x2860` | `0x28a0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xe28` | `0xe38` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x7c0` | `0x7d0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x418` | `0x428` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x3e8` | `0x3f0` | **`+0x8`** |
| `__TEXT.__const` | `0xd2` | `0xda` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3567.0.0.0.0
+3568.1.4.0.0

-  Functions: 396
-  Symbols:   252
-  CStrings:  973
+  Functions: 398
+  Symbols:   253
+  CStrings:  970
Symbols:
+ _TIInputManagerServerOSLogFacility
CStrings:
+ "Connection interrupted for client PID %{public}d (connection still valid, may resume)"
+ "Connection invalidated for client PID %{public}d (wasInteractingConnection=%{public}d)"
+ "Establishing connection with client PID %{public}d"
+ "Flushing the dynamic resources on inactivity"
+ "Keyboard settings changed. Releasing input managers."
+ "Preparing keyboard for activity"
+ "Preparing keyboard for inactivity"
+ "Preparing keyboard for inactivity, last flush at %lf, flush period: %lf"
+ "Received memory pressure level %ld"
+ "Reduce cache to size=%lu"
+ "releaseAllInputManagersAndLanguageModelResources"
+ "setInterruptionHandler:"
- "%s  Establishing connection with PID %d"
- "%s  Flushing the dynamic resources on inactivity"
- "%s  Keyboard settings changed. Releasing input managers."
- "%s  Preparing keyboard for activity"
- "%s  Preparing keyboard for inactivity"
- "%s  Preparing keyboard for inactivity, last flush at %lf, flush period: %lf"
- "%s  Received memory pressure level %ld"
- "%s  Reduce cache to size=%lu"
- "-[TIKeyboardInputManagerServer appleKeyboardsSettingsChanged:]"
- "-[TIKeyboardInputManagerServer checkAndFlushDynamicCaches]"
- "-[TIKeyboardInputManagerServer handleMemoryPressureLevel:excessMemoryInBytes:]"
- "-[TIKeyboardInputManagerServer listener:shouldAcceptNewConnection:]"
- "-[TIKeyboardInputManagerServer prepareForActivity]"
- "-[TIKeyboardInputManagerServer prepareForInactivity]"
- "-[TIKeyboardInputManagerServer reduceCacheToSize:]"
```
