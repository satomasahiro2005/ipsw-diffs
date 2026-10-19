## AudioToolboxCore

> `/System/Library/PrivateFrameworks/AudioToolboxCore.framework/AudioToolboxCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x217e6` | `0x219d7` | **`+0x1f1`** |

### Other Changes

```diff

-  CStrings:  6830
+  CStrings:  6836
CStrings:
+ "PRECONDITION FAILURE (std::logic_error) [!mCookie.empty() is false]"
+ "PRECONDITION FAILURE (std::logic_error) [!mFileName.empty() is false]"
+ "PRECONDITION FAILURE (std::logic_error) [inCookie != nullptr is false]"
+ "PRECONDITION FAILURE (std::logic_error) [inCookieSize != 0 is false]"
+ "PRECONDITION FAILURE (std::logic_error) [inTapPoint < kTapPointCount is false]"
+ "PRECONDITION FAILURE (std::logic_error) [mClientFormat.mFormatID != 0 is false]"
+ "PRECONDITION FAILURE (std::logic_error) [mClientFormat.mFormatID != kAudioFormatLinearPCM is false]"
- "PRECONDITION FAILURE (std::logic_error)"
```
