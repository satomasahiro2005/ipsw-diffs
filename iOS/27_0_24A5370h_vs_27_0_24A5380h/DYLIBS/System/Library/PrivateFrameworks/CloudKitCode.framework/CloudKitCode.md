## CloudKitCode

> `/System/Library/PrivateFrameworks/CloudKitCode.framework/CloudKitCode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `—` | `0x390` | **`+0x390`** |
| `__DATA_DIRTY.__data` | `0xa98` | `0x718` | **`-0x380`** |
| `__AUTH.__objc_data` | `—` | `0x148` | **`+0x148`** |
| `__DATA_DIRTY.__objc_data` | `0x1e8` | `0xa0` | **`-0x148`** |
| `__TEXT.__text` | `0x2714c` | `0x270f8` | **`-0x54`** |
| `__TEXT.__const` | `0x1d90` | `0x1d80` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xf98` | `0xfa0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2710.112.0.0.0
+2710.114.0.0.0

-  Functions: 1614
+  Functions: 1615
Functions:
~ _$s12CloudKitCode16Ckcode_Proto2AnyV5value10Foundation4DataVvg : 80 -> 56
~ _$s12CloudKitCode16Ckcode_Proto2AnyV5value10Foundation4DataVvM : 128 -> 96
+ sub_256e88514
- sub_252786470
+ sub_256e885bc
+ sub_256e885fc
- _$s12CloudKitCode22Ckcode_RecordTransportV8contentsAC14OneOf_ContentsOSgvg
~ _$s12CloudKitCode22Ckcode_RecordTransportV18encryptedMasterKey10Foundation4DataVvg : 88 -> 64
~ _$s12CloudKitCode22Ckcode_RecordTransportV18encryptedMasterKey10Foundation4DataVvM : 140 -> 104
~ _$s12CloudKitCode22Ckcode_RecordTransportV13decodeMessage7decoderyxz_tK21InternalSwiftProtobuf7DecoderRzlF : 172 -> 160
~ _$s12CloudKitCode22Ckcode_RecordTransportV8traverse7visitoryxz_tK21InternalSwiftProtobuf7VisitorRzlF : 160 -> 184
CStrings:
+ "CKRecords sent via Inverness cannot contain in-memory asset content"
- "CKRecords sent via Inverness cannot container in-memory asset content"
```
