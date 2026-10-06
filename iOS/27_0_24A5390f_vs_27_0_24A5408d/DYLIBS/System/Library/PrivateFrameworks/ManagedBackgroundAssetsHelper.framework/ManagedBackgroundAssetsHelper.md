## ManagedBackgroundAssetsHelper

> `/System/Library/PrivateFrameworks/ManagedBackgroundAssetsHelper.framework/ManagedBackgroundAssetsHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b16f8` | `0x1bb0fc` | **`+0x9a04`** |
| `__TEXT.__oslogstring` | `0x9555` | `0x9bf5` | **`+0x6a0`** |
| `__TEXT.__eh_frame` | `0x108c8` | `0x10c18` | **`+0x350`** |
| `__TEXT.__const` | `0x14c50` | `0x14cb0` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x7570` | `0x75c0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x43dc` | `0x442c` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5cd8` | `0x5d28` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1380` | `0x13b8` | **`+0x38`** |
| `__DATA.__data` | `0x3178` | `0x31b0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x790` | `0x7c8` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0xbb8` | `0xbc8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x4fd2` | `0x4fe0` | **`+0xe`** |
| `__TEXT.__swift_as_ret` | `0x468` | `0x470` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x334` | `0x338` | **`+0x4`** |

### Other Changes

```diff

-2.0.32.0.0
+2.0.35.1.0

+  - /System/Library/Frameworks/Combine.framework/Combine

+  - /System/Library/PrivateFrameworks/ManagedBackgroundAssetsRelay.framework/ManagedBackgroundAssetsRelay

-  Functions: 5744
-  Symbols:   2127
-  CStrings:  864
+  Functions: 5761
+  Symbols:   2130
+  CStrings:  878
Symbols:
+ ___swift_deallocate_boxed_opaque_existential_0
+ ___swift_get_extra_inhabitant_index.569Tm
+ ___swift_get_extra_inhabitant_index.587Tm
+ ___swift_store_extra_inhabitant_index.570Tm
+ ___swift_store_extra_inhabitant_index.588Tm
+ _associated conformance 29ManagedBackgroundAssetsHelper11ErrorCodingV05SwiftE10ProjectionV10Foundation09LocalizedE0AAs0E0
+ _associated conformance 29ManagedBackgroundAssetsHelper11ErrorCodingV05SwiftE10ProjectionV10Foundation13CustomNSErrorAAs0E0
+ _symbolic SSSg_____Su_____Sg___________pIetMHgTnTyTnTgzo_ 29ManagedBackgroundAssetsHelper15AssetPackRecordC8GlobalIDV AA11ErrorCodingV AA0D0C s0J0P
+ _symbolic _____ 29ManagedBackgroundAssetsHelper11ErrorCodingV05SwiftE10ProjectionV
+ _symbolic _____Sg 28ManagedBackgroundAssetsRelay14ResumptionInfoV
+ _type_layout_string 29ManagedBackgroundAssetsHelper11ErrorCodingV05SwiftE10ProjectionV
+ _xpc_add_bundle
- ___swift_get_extra_inhabitant_index.565Tm
- ___swift_get_extra_inhabitant_index.583Tm
- ___swift_store_extra_inhabitant_index.566Tm
- ___swift_store_extra_inhabitant_index.584Tm
- _associated conformance 29ManagedBackgroundAssetsHelper11ErrorCodingV05SwiftE10Projection33_2C8B19F64FA66920F5B93A6DCF147067LLV10Foundation09LocalizedE0AAs0E0
- _associated conformance 29ManagedBackgroundAssetsHelper11ErrorCodingV05SwiftE10Projection33_2C8B19F64FA66920F5B93A6DCF147067LLV10Foundation13CustomNSErrorAAs0E0
- _symbolic _____ 29ManagedBackgroundAssetsHelper11ErrorCodingV05SwiftE10Projection33_2C8B19F64FA66920F5B93A6DCF147067LLV
- _symbolic _____Su_____Sg___________pIetMHnTyTnTgzo_ 29ManagedBackgroundAssetsHelper15AssetPackRecordC8GlobalIDV AA11ErrorCodingV AA0D0C s0J0P
- _type_layout_string 29ManagedBackgroundAssetsHelper11ErrorCodingV05SwiftE10Projection33_2C8B19F64FA66920F5B93A6DCF147067LLV
CStrings:
+ "/System/Library/PrivateFrameworks/ManagedBackgroundAssets.framework"
+ "An item already exists at “%{public}s”; overwriting it…"
+ "Error"
+ "Removing the resumption info for the download with the unique ID “%{public}s” of the asset pack with the ID “%{public}s” for the app with the bundle ID “%{public}s” via the relay…"
+ "Report download with ID: %{public}s of asset pack with global ID: %{public}s version: %lu"
+ "Report download with ID: %{public}s of asset pack with global ID: %{public}s version: %lu reached terminal phase with error coding: %{public}s"
+ "Report failed download with ID: %{public}s of asset pack with global ID: %{public}s version: %{public}lu with error: %{public}@"
+ "Resolved from bookmark data: %{public}s to: %{public}s attributing to bundle with ID: %{public}s overwrite: %{bool}d"
+ "Resolved from bookmark data: %{public}s to: %{public}s overwrite: %{bool}d"
+ "Resumption info for the download with the unique ID “%{public}s” of the asset pack with the ID “%{public}s” for the app with the bundle ID “%{public}s” couldn’t be removed via the relay: %{public}@"
+ "The attribution of the %{public}sitem%{public}s at %{public}s to the bundle with the ID “%{public}s” couldn’t be removed: %{public}@"
+ "The attribution of the item at “%{public}s” to the bundle with the ID “%{public}s” couldn’t be removed: %{public}@"
+ "The fact that version %lu of the asset pack with the ID “%{public}s” for the app with the bundle ID “%{public}s” failed to be downloaded couldn’t be reported to TestFlight: %{public}@"
+ "The fact that version %lu of the asset pack with the ID “%{public}s” for the app with the bundle ID “%{public}s” was successfully downloaded couldn’t be reported to TestFlight: %{public}@"
+ "The item at “%{public}s” couldn’t be attributed to the bundle with the ID “%{public}s”: %{public}@"
+ "URL"
- "Resolved from bookmark data: %{public}s to: %{public}s"
- "Resolved from bookmark data: %{public}s to: %{public}s attributing to bundle with ID: %{public}s"
```
