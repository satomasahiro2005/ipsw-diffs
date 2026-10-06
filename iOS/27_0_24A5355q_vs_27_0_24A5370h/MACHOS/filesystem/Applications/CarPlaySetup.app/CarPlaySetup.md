## CarPlaySetup

> `/Applications/CarPlaySetup.app/CarPlaySetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7708` | `0x78e4` | **`+0x1dc`** |
| `__TEXT.__oslogstring` | `0xc12` | `0xc6d` | **`+0x5b`** |
| `__TEXT.__objc_methname` | `0x2bd9` | `0x2c11` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x238` | `0x240` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-789.1.0.0.0
+792.0.0.0.0

-  Functions: 188
+  Functions: 190

-  CStrings:  561
+  CStrings:  563
CStrings:
+ "presentWaitingOnStartSessionPromptWithResponseHandler:"
+ "promptDirectorWantsToPresentWaitingOnStartSession:responseHandler:"
+ "waiting on start session prompt answered"
+ "waiting on start session prompt received response"
+ "waitingOnStartSessionPromptWithResponseHandler:"
- "presentWaitingOnStartSessionPrompt"
- "promptDirectorWantsToPresentWaitingOnStartSession:"
- "waitingOnStartSessionPrompt"
```
