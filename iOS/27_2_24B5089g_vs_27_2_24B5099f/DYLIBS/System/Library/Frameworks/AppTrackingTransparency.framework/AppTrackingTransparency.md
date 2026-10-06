## AppTrackingTransparency

> `/System/Library/Frameworks/AppTrackingTransparency.framework/AppTrackingTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4cc` | `0x4e8` | **`+0x1c`** |
| `__TEXT.__oslogstring` | `0x838` | `0x844` | **`+0xc`** |

### Other Changes

```diff

-106.3.2.0.0
+106.3.3.0.0
Symbols:
+ +[ATTrackingManager requestTrackingAuthorizationPreferringExpandedInterface:additionalInformationAction:completionHandler:]
+ ___123+[ATTrackingManager requestTrackingAuthorizationPreferringExpandedInterface:additionalInformationAction:completionHandler:]_block_invoke
- +[ATTrackingManager requestTrackingAuthorizationPreferExpandedInterface:additionalInformationAction:completionHandler:]
- ___119+[ATTrackingManager requestTrackingAuthorizationPreferExpandedInterface:additionalInformationAction:completionHandler:]_block_invoke
CStrings:
+ "[%@] requestTrackingAuthorizationPreferringExpandedInterface API call failed due to missing completion."
+ "[%@] requestTrackingAuthorizationPreferringExpandedInterface API call invoked, preferExpandedInterface=%d, displayAdditionalInfo=%d."
+ "[%@] requestTrackingAuthorizationPreferringExpandedInterface returning - Additional Information button tapped."
+ "requestTrackingAuthorizationPreferringExpandedInterface returning %lu due to backgrounded app."
+ "requestTrackingAuthorizationPreferringExpandedInterface returning - ATT Authorized."
+ "requestTrackingAuthorizationPreferringExpandedInterface returning - ATT Denied due to tracking toggle."
+ "requestTrackingAuthorizationPreferringExpandedInterface returning - ATT Denied."
+ "requestTrackingAuthorizationPreferringExpandedInterface returning - ATT not determined."
+ "requestTrackingAuthorizationPreferringExpandedInterface returning Authorized due to consent."
+ "requestTrackingAuthorizationPreferringExpandedInterface returning Denied due to consent."
- "[%@] requestTrackingAuthorizationPreferExpandedInterface API call failed due to missing completion."
- "[%@] requestTrackingAuthorizationPreferExpandedInterface API call invoked, preferExpandedInterface=%d, displayAdditionalInfo=%d."
- "[%@] requestTrackingAuthorizationPreferExpandedInterface returning - Additional Information button tapped."
- "requestTrackingAuthorizationPreferExpandedInterface returning %lu due to backgrounded app."
- "requestTrackingAuthorizationPreferExpandedInterface returning - ATT Authorized."
- "requestTrackingAuthorizationPreferExpandedInterface returning - ATT Denied due to tracking toggle."
- "requestTrackingAuthorizationPreferExpandedInterface returning - ATT Denied."
- "requestTrackingAuthorizationPreferExpandedInterface returning - ATT not determined."
- "requestTrackingAuthorizationPreferExpandedInterface returning Authorized due to consent."
- "requestTrackingAuthorizationPreferExpandedInterface returning Denied due to consent."
```
