## BrailleNBSC

> `/System/Library/ScreenReader/BrailleTables/BrailleNBSC.brailletable/BrailleNBSC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22cc4` | `0x140f8` | **`-0xebcc`** |
| `__DATA.__data` | `0x10c80` | `0x8ae0` | **`-0x81a0`** |
| `__TEXT.__const` | `0x4ea0` | `0x1290` | **`-0x3c10`** |
| `__DATA.__common` | `0x81fa8` | `0x83060` | **`+0x10b8`** |
| `__TEXT.__ustring` | `0x14` | `0x35e` | **`+0x34a`** |
| `__TEXT.__cstring` | `0x1a9` | `0x28b` | **`+0xe2`** |
| `__TEXT.__auth_stubs` | `0x3b0` | `0x400` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x228` | `0x270` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x1e8` | `0x210` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x58` | `0x60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-15.0.0.0.0
+16.0.0.0.0

-  Functions: 130
-  Symbols:   222
-  CStrings:  140
+  Functions: 153
+  Symbols:   241
+  CStrings:  156
Symbols:
+ __Z7IsKoukiPw
+ __Z8KoukiSetPw
+ __ZN5ktoau11IsHiraMatchEPwS0_i
+ __ZN5ktoau11IsSuushiuNaEPwi
+ __ZN5ktoau11IsTanKeiyouEPw
+ __ZN5ktoau12IsKanjiMatchEPwS0_i
+ __ZN5ktoau12IsSuujiIndexEPw
+ __ZN5ktoau13IsDoushiHira3EPw
+ __ZN5ktoau13IsDoushiHira4EPw
+ __ZN5ktoau14IsKeiyouDoushiEPw
+ __ZN5ktoau3IsIEPw
+ __ZN5ktoau4IsB5EPw
+ __ZN5ktoau4IsC5EPw
+ __ZN5ktoau4IsG5EPw
+ __ZN5ktoau4IsK5EPw
+ __ZN5ktoau4IsM5EPw
+ __ZN5ktoau4IsR5EPw
+ __ZN5ktoau4IsS5EPw
+ __ZN5ktoau4IsT5EPw
+ __ZN5ktoau4IsW5EPw
+ __ZN5ktoau4IsZ5EPw
+ __ZN5ktoau7SetHiraEPwS0_Ptii
+ __ZN5ktoau8IsKeiyouEPw
+ __ZN5ktoau9IsKanjiNaEPwii
+ __ZN5ktoau9IsSuushiuEPwS0_i
+ _fprintf
+ _ftell
+ _fwrite
+ _main
+ _printf
+ _puts
- __ZN5ktoau10IsHiraKatuEPwS0_
- __ZN5ktoau11IsFukuKanjiEPwS0_
- __ZN5ktoau11IsHenSuushiEPw
- __ZN5ktoau11IsHiraMatchEPwS0_
- __ZN5ktoau12IsHiraDoushiEPwS0_
- __ZN5ktoau12IsKanjiMatchEPwS0_
- __ZN5ktoau12SetHenSuushiEPwPtS0_i
- __ZN5ktoau15TanKanji2SetSubEPwwwwS0_
- __ZN5ktoau8IsDoushiEPw
- __ZN5ktoau9IsKanjiNaEPwi
- __ZN5ktoau9IsSetsubiEPw
- __ZN5ktoau9IsSuushiuEPwS0_
CStrings:
+ "/Library/Accessibility/ktoa_u_kwa_v6.dic"
+ "ab"
+ "error code %d\n"
+ "log.txt"
+ "not Init"
+ "not Init error code %d\n"
+ "not convert"
+ "not convert error code %d\n"
+ "output.txt"
+ "output.txt not open"
+ "outputKana.txt"
+ "outputKana.txt not open"
+ "testu.txt"
+ "testu.txt not UTF-16LT"
+ "testu.txt not open"
+ "wb"
+ "\xff\xfe"
- "/Library/Accessibility/ktoa_u_kwa_v5.dic"
```
