## GSS

> `/System/Library/Frameworks/GSS.framework/GSS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x738` | `0x740` | **`+0x8`** |

### Other Changes

```diff

-725.0.8.0.0
+725.0.10.0.0
Symbols:
+ _asn1_KERB_ERROR_DATA_tag__456
- _asn1_KERB_ERROR_DATA_tag__455
Functions:
~ __gssapi_verify_pad : 76 -> 96
~ __gsskrb5_unwrap : 1372 -> 1352
```
