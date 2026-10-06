## tursd

> `/usr/libexec/tursd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methtype` | `0x92e` | `0x948` | **`+0x1a`** |
| `__TEXT.__objc_methname` | `0x3b0c` | `0x3b13` | **`+0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1160.0.0.0.0
+1161.1.2.0.0

-  CStrings:  756
+  CStrings:  757
CStrings:
+ "conversationManager:conversation:participant:didUpdateNickname:reason:"
+ "v56@0:8@\"TUConversationManager\"16@\"TUConversation\"24@\"TUConversationParticipant\"32@\"NSString\"40Q48"
+ "v56@0:8@16@24@32@40Q48"
- "conversationManager:conversation:participant:didUpdateNickname:"
- "v48@0:8@\"TUConversationManager\"16@\"TUConversation\"24@\"TUConversationParticipant\"32@\"NSString\"40"
```
