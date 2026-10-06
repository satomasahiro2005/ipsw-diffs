## AudioSession

> `/System/Library/PrivateFrameworks/AudioSession.framework/AudioSession`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x47f4` | `0x4878` | **`+0x84`** |

### Other Changes

```diff

-449.107.0.0.0
+449.203.0.0.0
CStrings:
+ "%25s:%-5d __delegate_identifier__:Performance Diagnostics__:::____message__:This method can lead to UI unresponsiveness if called on the main thread while the audio session is active."
+ "%25s:%-5d __delegate_identifier__:Performance Diagnostics__:::____message__:This method can lead to UI unresponsiveness if called on the main thread. Consider using the asynchronous activate/deactivate API instead for calls from the main thread."
- "%25s:%-5d This method can lead to UI unresponsiveness if called on the main thread while the audio session is active."
- "%25s:%-5d This method can lead to UI unresponsiveness if called on the main thread. Consider using the asynchronous activate/deactivate API instead for calls from the main thread."
```
