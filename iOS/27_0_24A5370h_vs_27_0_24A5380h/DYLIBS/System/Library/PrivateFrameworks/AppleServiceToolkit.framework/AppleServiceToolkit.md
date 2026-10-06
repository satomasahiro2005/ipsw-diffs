## AppleServiceToolkit

> `/System/Library/PrivateFrameworks/AppleServiceToolkit.framework/AppleServiceToolkit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c928` | `0x2c978` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xca0` | `0xc98` | **`-0x8`** |

### Other Changes

```diff

-232.0.0.0.0
+234.0.1.0.0
Functions:
~ -[ASTSession sendProfileResult:error:] : 112 -> 96
~ -[ASTSession session:signPayload:completionHandler:] : 208 -> 192
~ -[ASTSession session:signFile:completionHandler:] : 208 -> 192
~ +[ASTEncodingUtilities parseJSONResponseWithData:error:] : 160 -> 220
~ +[ASTEncodingUtilities jsonSerializeObject:error:] : 256 -> 316
~ -[ASTRemoteServerSession sendAuthInfoResult:error:] : 400 -> 408
~ -[ASTRemoteServerSession sendProfileResult:error:] : 792 -> 788
~ -[ASTRemoteServerSession sendTestResult:error:] : 600 -> 604
```
