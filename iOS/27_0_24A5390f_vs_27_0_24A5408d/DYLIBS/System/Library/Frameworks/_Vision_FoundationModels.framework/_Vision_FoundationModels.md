## _Vision_FoundationModels

> `/System/Library/Frameworks/_Vision_FoundationModels.framework/_Vision_FoundationModels`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2b9` | `0x439` | **`+0x180`** |

### Other Changes

```diff

-10.0.39.0.0
+10.0.45.0.0
CStrings:
+ "Reads barcodes and QR codes from an image attached to the conversation. The image argument's attachmentLabel must be the label of an attached image (the identifier shown with the image), not a schema reference, $ref, or type name."
+ "Reads text from an image attached to the conversation. The image argument's attachmentLabel must be the label of an attached image (the identifier shown with the image), not a schema reference, $ref, or type name."
- "Get text in an image"
- "Read barcodes and QR codes in an image"
```
