## MusicSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/MusicSnippetProviderPlugin.bundle/MusicSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ca8` | `0x3344` | **`-0x1964`** |
| `__TEXT.__oslogstring` | `0x3af` | `0x205` | **`-0x1aa`** |
| `__TEXT.__auth_stubs` | `0x5d0` | `0x440` | **`-0x190`** |
| `__TEXT.__const` | `0x290` | `0x112` | **`-0x17e`** |
| `__TEXT.__eh_frame` | `0x138` | `—` | **`-0x138`** |
| `__TEXT.__swift5_typeref` | `0x13a` | `0x2f` | **`-0x10b`** |
| `__DATA_CONST.__auth_got` | `0x2e8` | `0x220` | **`-0xc8`** |
| `__DATA_CONST.__auth_ptr` | `0x100` | `0x68` | **`-0x98`** |
| `__DATA.__data` | `0x160` | `0xd8` | **`-0x88`** |
| `__TEXT.__cstring` | `0x54` | `0xd6` | **`+0x82`** |
| `__DATA.__bss` | `0x100` | `0x80` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x140` | `0xd8` | **`-0x68`** |
| `__DATA_CONST.__got` | `0xf8` | `0xb0` | **`-0x48`** |
| `__DATA_CONST.__const` | `0x168` | `0x138` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x64` | `0x48` | **`-0x1c`** |
| `__TEXT.__swift5_assocty` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__swift_as_entry` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x20` | `0x10` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x8` | `0x4` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x8` | `0x4` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x4` | `—` | **`-0x4`** |
| `__TEXT.__swift5_reflstr` | `0x2` | `—` | **`-0x2`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-4026.100.89.0.0
+4026.110.2.0.0

-  - /System/Library/PrivateFrameworks/SiriKitFlow.framework/SiriKitFlow

-  - /usr/lib/swift/libswiftMetalKit.dylib
-  - /usr/lib/swift/libswiftModelIO.dylib

-  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 86
-  Symbols:   73
-  CStrings:  18
+  Functions: 48
+  Symbols:   61
+  CStrings:  16
Symbols:
+ _objc_release_x25
+ _objc_release_x26
+ _swift_getMetatypeMetadata
+ _swift_release_x20
- __swift_FORCE_LOAD_$_swiftMetalKit
- __swift_FORCE_LOAD_$_swiftModelIO
- _objc_release_x22
- _objc_release_x23
- _objc_release_x24
- _objc_release_x27
- _swift_arrayInitWithCopy
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_bridgeObjectRetain_n
- _swift_initStackObject
- _swift_release_x19
- _swift_release_x21
- _swift_task_alloc
- _swift_task_dealloc
- _swift_task_switch
CStrings:
+ "%{public}s Could not create snippet model for item: %{public}s"
+ "%{public}s Created music model: %{public}s"
+ "%{public}s Creating %{public}s snippet model for entity with ID %{public}s and properties %{public}s"
+ "%{public}s Custom Siri snippets disabled, not handling item: %{public}s"
+ "%{public}s Handling item: %{public}s with context: %{public}s"
+ "%{public}s Unsupported bundle identifier: %{public}s"
+ "%{public}s Unsupported entity type: %{public}s"
+ "%{public}s Unsupported item: %{public}s"
+ "AlgorithmicStationSiriEntity"
+ "ArtistSiriEntity"
+ "LiveStationSiriEntity"
+ "PlaylistSiriEntity"
- "%{public}s Created %{public}s entities response with %{public}s items: %{public}s"
- "%{public}s Created %{public}s music Models: %{public}s"
- "%{public}s Determining support for system response: %s"
- "%{public}s Handling payload: %s"
- "%{public}s No valid music entities found in payload"
- "%{public}s Response is not supported because it doesn't contain any target entities"
- "%{public}s Response type %{public}s is not supported"
- "Couldn't create snippet model for unknown entity type %{public}s"
- "Creating %{public}s snippet model for entity with ID %{public}s and properties %{public}s"
- "Evaluating item %{public}s for type %{public}s"
- "Ignoring unsupported entity: bundleIdentifier=%s, type=%s"
- "Item not a supported entity - unexpected bundle id and type"
- "Item not a supported entity - unexpected type"
- "Item not a supported entity - unexpected value and entity"
```
