## ManagedBackgroundAssetsHelper

> `/System/Library/PrivateFrameworks/ManagedBackgroundAssetsHelper.framework/ManagedBackgroundAssetsHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cf6a4` | `0x1c767c` | **`-0x8028`** |
| `__DATA.__bss` | `0x1ee60` | `0x1e860` | **`-0x600`** |
| `__TEXT.__oslogstring` | `0xa685` | `0xa235` | **`-0x450`** |
| `__TEXT.__const` | `0x15940` | `0x15690` | **`-0x2b0`** |
| `__TEXT.__cstring` | `0x497c` | `0x46cc` | **`-0x2b0`** |
| `__TEXT.__eh_frame` | `0x11608` | `0x113b8` | **`-0x250`** |
| `__DATA_DIRTY.__bss` | `0x4500` | `0x4700` | **`+0x200`** |
| `__DATA.__data` | `0x3468` | `0x3340` | **`-0x128`** |
| `__AUTH.__data` | `0x8e0` | `0x7c0` | **`-0x120`** |
| `__TEXT.__unwind_info` | `0x5f98` | `0x5e80` | **`-0x118`** |
| `__AUTH_CONST.__auth_got` | `0x1558` | `0x1450` | **`-0x108`** |
| `__AUTH_CONST.__const` | `0x7988` | `0x7880` | **`-0x108`** |
| `__TEXT.__swift5_typeref` | `0x52c6` | `0x51e8` | **`-0xde`** |
| `__DATA_DIRTY.__data` | `0x22b8` | `0x2348` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x3228` | `0x31c4` | **`-0x64`** |
| `__DATA_CONST.__got` | `0x880` | `0x820` | **`-0x60`** |
| `__TEXT.__swift5_reflstr` | `0x1ef8` | `0x1e98` | **`-0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x3ae0` | `0x3a84` | **`-0x5c`** |
| `__TEXT.__swift5_capture` | `0x19c` | `0x15c` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x1638` | `0x1618` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x11a8` | `0x1188` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0xc20` | `0xc0c` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0x49c` | `0x494` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x354` | `0x34c` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x494` | `0x48c` | **`-0x8`** |

### Other Changes

```diff

-2.1.6.0.0
+2.1.9.0.0

-  Functions: 5962
-  Symbols:   2202
-  CStrings:  940
+  Functions: 5893
+  Symbols:   2181
+  CStrings:  909
Symbols:
+ ___swift_get_extra_inhabitant_index.591Tm
+ ___swift_get_extra_inhabitant_index.609Tm
+ ___swift_store_extra_inhabitant_index.592Tm
+ ___swift_store_extra_inhabitant_index.610Tm
+ _objc_retain_x26
- ___swift_destroy_boxed_opaque_existential_0Tm
- ___swift_get_extra_inhabitant_index.593Tm
- ___swift_get_extra_inhabitant_index.611Tm
- ___swift_project_boxed_opaque_existential_0Tm
- ___swift_store_extra_inhabitant_index.594Tm
- ___swift_store_extra_inhabitant_index.612Tm
- _associated conformance 29ManagedBackgroundAssetsHelper35AppReviewLicenseRequestRetryOptionsV10CodingKeys33_C4AB38F9035031268D27AA0DDCE02018LLOSHAASQ
- _associated conformance 29ManagedBackgroundAssetsHelper35AppReviewLicenseRequestRetryOptionsV10CodingKeys33_C4AB38F9035031268D27AA0DDCE02018LLOs0K3KeyAAs23CustomStringConvertible
- _associated conformance 29ManagedBackgroundAssetsHelper35AppReviewLicenseRequestRetryOptionsV10CodingKeys33_C4AB38F9035031268D27AA0DDCE02018LLOs0K3KeyAAs28CustomDebugStringConvertible
- _associated conformance 29ManagedBackgroundAssetsHelper35AppReviewLicenseRequestRetryOptionsV22ArgumentParserInternal17ParsableArgumentsAASe
- _swift_retain_x10
- _symbolic SDySS_____G s5Int64V
- _symbolic SDy_____ScTyyt_____GG s6UInt64V s5NeverO
- _symbolic SS______t s5Int64V
- _symbolic _____ 29ManagedBackgroundAssetsHelper35AppReviewLicenseRequestRetryOptionsV
- _symbolic _____ 29ManagedBackgroundAssetsHelper35AppReviewLicenseRequestRetryOptionsV10CodingKeys33_C4AB38F9035031268D27AA0DDCE02018LLO
- _symbolic _____Sg 22ArgumentParserInternal0A4HelpV
- _symbolic _____Sg 22ArgumentParserInternal14CompletionKindV
- _symbolic _____Sg 29ManagedBackgroundAssetsHelper35AppReviewLicenseRequestRetryOptionsV
- _symbolic _____Sg s8DurationV
- _symbolic _____ySS_____G s18_DictionaryStorageC s5Int64V
- _symbolic _____ySS______tG s23_ContiguousArrayStorageC s5Int64V
- _symbolic _____ySiSgG 22ArgumentParserInternal6OptionV
- _symbolic _____y_____G s22KeyedDecodingContainerV 29ManagedBackgroundAssetsHelper35AppReviewLicenseRequestRetryOptionsV10CodingKeys33_C4AB38F9035031268D27AA0DDCE02018LLO
- _symbolic _____y_____ScTyyt_____GG s18_DictionaryStorageC s6UInt64V s5NeverO
- _symbolic _____y_____SgG 22ArgumentParserInternal6OptionV s8DurationV
CStrings:
+ "No pending continuation is available for the license with the ID “%llu”."
+ "Posting a license-request notification for the license with the ID “%llu” from App Review…"
+ "Request license from App Review with: %{public}s app bundle ID: %{public}s continuation: %{public}s"
+ "Resuming the continuation for the license ID “%llu”…"
+ "Storing the provided continuation for the license ID “%llu”…"
+ "The process lacks a team ID, but it has the validation-bypass entitlement and internal security policies are allowed, so its team ID won’t be verified."
+ "The process’s validation-bypass entitlement couldn’t be verified: %{public}@"
+ "requestLicenseFromAppReview(with:appBundleID:continuation:)"
- "<App Review License Request Retry Options | Count: "
- "An App Review license-request retry task failed to sleep: %{public}@"
- "App Review License-Request Retry ("
- "App Review license-request retry options were provided with a count of %ld and an interval of %{public}s."
- "App Review license-request retry options weren’t provided."
- "Arguments were specified"
- "Canceling all retry tasks for the posting of license requests to App Review…"
- "Count"
- "Defaults object"
- "Init count: %ld interval: %{public}s"
- "Init defaults object: %{public}s"
- "Interval"
- "LicenseManagerAppReviewLicenseRequestRetryOptions"
- "MBAAppReviewLicenseRequestRetryOptions"
- "No pending delivery continuation is available for the license with the ID “%llu”."
- "Posting a license-request notification for the license with the ID “%llu” to App Review…"
- "Request license from App Review with: %{public}s app bundle ID: %{public}s delivery continuation: %{public}s"
- "Resuming the delivery continuation for the license ID “%llu” by throwing the error “%{public}@”…"
- "Resuming the delivery continuation for the license ID “%llu”…"
- "Retrying the posting of a license-request notification for the license with the ID “%llu” to App Review…"
- "Storing the provided delivery continuation for the license ID “%llu”…"
- "Subtracting one attempt"
- "The default value is "
- "The defaults dictionary lacks a dictionary value for the key “%{public}s” that maps strings to 64-bit integers."
- "The defaults dictionary lacks an integer value for the key “%{public}s”."
- "The defaults dictionary’s nested dictionary with the key “%{public}s” lacks a value for the key “%{public}s”."
- "The defaults object isn’t a string-keyed dictionary."
- "The interval between retries of the posting of a license request to App Review in seconds."
- "The number of types to retry the posting of a license request to App Review."
- "Validate"
- "app-review-license-request-retry-count"
- "app-review-license-request-retry-interval"
- "requestLicenseFromAppReview(with:appBundleID:deliveryContinuation:)"
- "“%ld” is an invalid count value."
- "“%lld” is an invalid attoseconds value for an interval."
- "“%lld” is an invalid seconds value for an interval."
- "” couldn’t be parsed as a number of seconds."
- "” is an invalid count value."
- "” is an invalid number of seconds."
```
