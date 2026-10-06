## com.apple.EXBrightKext

> `com.apple.EXBrightKext`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x176cc` | `0x17ecc` | **`+0x800`** |
| `__TEXT.__cstring` | `0x4b36` | `0x4da4` | **`+0x26e`** |
| `__DATA_CONST.__const` | `0x1f60` | `0x1fc0` | **`+0x60`** |
| `__TEXT.__const` | `0x118` | `0x120` | **`+0x8`** |

### Other Changes

```diff

-2300.40.39.0.0
-  Functions: 585
+2300.40.47.0.4
+  Functions: 599

-  CStrings:  315
+  CStrings:  319
CStrings:
+ "\"TB_ASSERT: \" \"(exbrightkextinterface_exbrightindicatordata__decode(msg, &item) == TB_ERROR_SUCCESS) && \\\"failed to decode type: EXBrightKextInterface.EXBrightIndicatorData\\\"\" \", \" \"\\b\\b\" \" (%s:%d)\" @%s:%d"
+ "\"TB_FATAL: \" \"invalid tag in `[EXBrightKextInterface.EXBrightIndicatorData]` metadata: 0x%x\" @%s:%d"
+ "EXBrightSILStateTrusted"
+ "I40@?0{exbrightkextinterface_exbrightindicatordata__opt_s=B{exbrightkextinterface_exbrightindicatordata_s=C{exbrightkextinterface_exbrightindicatorstate_s=Q(?={?=S})}}}8"
+ "I48@?0{exbrightkextinterface_exbrightindicatordata_v_s=C(?={?=^{exbrightkextinterface_exbrightindicatordata_s}Q@?}{?=*QQ}{?=^{tb_message_s}QQQ})}8"
+ "v24@?0Q8r^{exbrightkextinterface_exbrightindicatordata_s=C{exbrightkextinterface_exbrightindicatorstate_s=Q(?={?=S})}}16"
+ "v40@?0{exbrightkextinterface_exbrightindicatordata__opt_s=B{exbrightkextinterface_exbrightindicatordata_s=C{exbrightkextinterface_exbrightindicatorstate_s=Q(?={?=S})}}}8"
+ "v48@?0{exbrightkextinterface_exbrightindicatordata_v_s=C(?={?=^{exbrightkextinterface_exbrightindicatordata_s}Q@?}{?=*QQ}{?=^{tb_message_s}QQQ})}8"
- "\"TB_FATAL: \" \"invalid tag in `[EXBrightKextInterface.EXBrightIndicatorState]` metadata: 0x%x\" @%s:%d"
- "I48@?0{exbrightkextinterface_exbrightindicatorstate_v_s=C(?={?=^{exbrightkextinterface_exbrightindicatorstate_s}Q@?}{?=*QQ}{?=^{tb_message_s}QQQ})}8"
- "v24@?0Q8r^{exbrightkextinterface_exbrightindicatorstate_s=BC}16"
- "v48@?0{exbrightkextinterface_exbrightindicatorstate_v_s=C(?={?=^{exbrightkextinterface_exbrightindicatorstate_s}Q@?}{?=*QQ}{?=^{tb_message_s}QQQ})}8"
```
