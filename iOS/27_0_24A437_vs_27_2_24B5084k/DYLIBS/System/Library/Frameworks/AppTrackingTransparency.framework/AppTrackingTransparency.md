## AppTrackingTransparency

> `/System/Library/Frameworks/AppTrackingTransparency.framework/AppTrackingTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f4c` | `0x2a1c` | **`+0xad0`** |
| `__TEXT.__cstring` | `0x1aa` | `0x4c5` | **`+0x31b`** |
| `__AUTH_CONST.__cfstring` | `0x160` | `0x2a0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x6f6` | `0x835` | **`+0x13f`** |
| `__DATA_CONST.__const` | `0x160` | `0x1b0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x144` | `0x184` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x100` | `0x138` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x188` | `0x1b8` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xbc` | `0xe8` | **`+0x2c`** |
| `__DATA.__bss` | `0x30` | `0x2c` | **`-0x4`** |

### Other Changes

```diff

-106.2.2.0.0
+106.3.1.0.0

-  Functions: 40
-  Symbols:   154
-  CStrings:  41
+  Functions: 49
+  Symbols:   177
+  CStrings:  56
Symbols:
+ +[ATTrackingManager _isRepromptEligible]
+ +[ATTrackingManager _performTCCAccessRequestUsingExpandedInterface:displayAdditionalInfo:completion:]
+ +[ATTrackingManager _preRequestChecksWithCompletion:]
+ +[ATTrackingManager _recordRequestOutcome:prompted:deniedReason:log:]
+ +[ATTrackingManager requestTrackingAuthorizationUsingExpandedInterface:additionalInformationAction:completionHandler:]
+ GCC_except_table15
+ GCC_except_table20
+ GCC_except_table25
+ GCC_except_table27
+ _OBJC_CLASS_$_NSString
+ ___101+[ATTrackingManager _performTCCAccessRequestUsingExpandedInterface:displayAdditionalInfo:completion:]_block_invoke
+ ___118+[ATTrackingManager requestTrackingAuthorizationUsingExpandedInterface:additionalInformationAction:completionHandler:]_block_invoke
+ ___40+[ATTrackingManager _isRepromptEligible]_block_invoke
+ ___block_descriptor_48_e8_32bs40bs_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_e8_32bs40bs_e8_v16?0Q8ls32l8s40l8
+ __dispatch_main_q
+ _dispatch_async
+ _objc_release_x25
+ _objc_retain_x3
+ _objc_retain_x4
+ _objc_retain_x5
+ _tcc_authorization_record_get_eligible_for_reprompt
+ _tcc_message_options_set_learn_more_link
CStrings:
+ "Tracking authorization request returning - Restricted due to permission."
+ "Tracking authorization request returning - Restricted due to profile."
+ "Tracking authorization request returning - Restricted."
+ "[%@] %{public}@"
+ "[%@] Call to requesting tracking authorization eligible for rate limiting. Returning %lu"
+ "[%@] Performing TCC Access Request (preferExpandedInterface=%d, displayAdditionalInfo=%d)."
+ "[%@] Performing TCC reprompt eligibility request."
+ "[%@] Received error invoking TCC access request with sheet."
+ "[%@] Received error querying TCC reprompt eligibility."
+ "[%@] requestTrackingAuthorizationUsingExpandedInterface API call failed due to missing completion."
+ "[%@] requestTrackingAuthorizationUsingExpandedInterface API call invoked, preferExpandedInterface=%d, displayAdditionalInfo=%d."
+ "[%@] requestTrackingAuthorizationUsingExpandedInterface returning - Additional Information button tapped."
+ "requestTrackingAuthorizationUsingExpandedInterface returning %lu due to backgrounded app."
+ "requestTrackingAuthorizationUsingExpandedInterface returning - ATT Authorized."
+ "requestTrackingAuthorizationUsingExpandedInterface returning - ATT Denied due to tracking toggle."
+ "requestTrackingAuthorizationUsingExpandedInterface returning - ATT Denied."
+ "requestTrackingAuthorizationUsingExpandedInterface returning - ATT not determined."
+ "requestTrackingAuthorizationUsingExpandedInterface returning Authorized due to consent."
+ "requestTrackingAuthorizationUsingExpandedInterface returning Denied due to consent."
- "[%@] Call to requestTrackingAuthorizationWithCompletionHandler eligible for rate limiting. Returning %lu"
- "[%@] requestTrackingAuthorizationWithCompletionHandler returning - Restricted due to permission."
- "[%@] requestTrackingAuthorizationWithCompletionHandler returning - Restricted due to profile."
- "[%@] requestTrackingAuthorizationWithCompletionHandler returning - Restricted."
```
