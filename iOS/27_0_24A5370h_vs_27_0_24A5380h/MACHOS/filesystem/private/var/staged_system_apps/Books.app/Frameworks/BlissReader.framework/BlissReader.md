## BlissReader

> `/private/var/staged_system_apps/Books.app/Frameworks/BlissReader.framework/BlissReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x1700` | `0x1c00` | **`+0x500`** |
| `__TEXT.__text` | `0x2a3b08` | `0x2a3a28` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x36a33` | `0x36a16` | **`-0x1d`** |
| `__TEXT.__objc_methname` | `0x8e160` | `0x8e157` | **`-0x9`** |
| `__TEXT.__unwind_info` | `0xdf18` | `0xdf20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6636.0.0.0.0
+6643.0.0.0.0

-  CStrings:  32254
+  CStrings:  32253
Symbols:
+ __ZN11yyFlexLexer16yy_create_bufferEPNSt3__113basic_istreamIcNS0_11char_traitsIcEEEEm
+ __ZN11yyFlexLexer16yy_create_bufferERNSt3__113basic_istreamIcNS0_11char_traitsIcEEEEm
- __ZN11yyFlexLexer16yy_create_bufferEPNSt3__113basic_istreamIcNS0_11char_traitsIcEEEEi
- __ZN11yyFlexLexer16yy_create_bufferERNSt3__113basic_istreamIcNS0_11char_traitsIcEEEEi
Functions:
~ sub_1d244 : 1012 -> 996
~ sub_f2d28 -> sub_f2d18 : 64 -> 72
~ sub_f3110 -> sub_f3108 : 164 -> 172
~ sub_fd864 : 672 -> 680
~ sub_1ee08c -> sub_1ee094 : 488 -> 480
~ sub_1f440c : 164 -> 160
~ sub_1fb3fc -> sub_1fb3f8 : 484 -> 472
~ sub_1fd4fc -> sub_1fd4ec : 532 -> 520
~ sub_2022cc -> sub_2022b0 : 484 -> 472
~ sub_205088 -> sub_205060 : 108 -> 100
~ sub_20528c -> sub_20525c : 612 -> 564
~ sub_205cc0 -> sub_205c60 : 132 -> 112
~ sub_205d44 -> sub_205cd0 : 164 -> 140
~ _sfaxmlXmlCharToFloat : 316 -> 300
~ _sfaxmlXmlCharToDouble : 312 -> 296
~ __ZN11yyFlexLexer18yy_get_next_bufferEv : 828 -> 788
~ __ZN11yyFlexLexer16yy_create_bufferERNSt3__113basic_istreamIcNS0_11char_traitsIcEEEEi -> __ZN11yyFlexLexer16yy_create_bufferERNSt3__113basic_istreamIcNS0_11char_traitsIcEEEEm : 212 -> 208
~ __Z24strdupWithoutURLOrQuotesPc : 256 -> 232
~ sub_2414fc -> sub_24140c : 612 -> 624
~ sub_2417e8 -> sub_241704 : 172 -> 160
~ _sb_stemmer_new : 200 -> 216
CStrings:
+ "B24@0:8@\"UIZoomTransitionInteractionContext\"16"
+ "willBegin"
- "B24@0:8@\"_UIViewControllerTransitionInteractionContext\"16"
- "input in flex scanner failed"
- "proposedBeginState"
```
