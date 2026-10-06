## com.apple.Dataclass.Siri

> `/System/Library/iCloudSettings/com.apple.Dataclass.Siri.bundle/com.apple.Dataclass.Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b7c` | `0x1950` | **`-0x22c`** |
| `__TEXT.__cstring` | `0x55` | `0xe5` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x3f0` | `0x3d0` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x62` | `0x48` | **`-0x1a`** |
| `__DATA_CONST.__auth_got` | `0x200` | `0x1f0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xe8` | `0xf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-3600.62.13.1.1
+3600.62.27.1.1

-  Functions: 53
-  Symbols:   305
-  CStrings:  14
+  Functions: 52
+  Symbols:   302
+  CStrings:  16
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/SiriSetup_Cloud/install/TempContent/Objects/SiriSetup.build/SiriCloudSettingsBundle.build/Objects-normal/arm64e/SiriCloudSettingsBundle-e321312c0883ea8b3b986249462e0f8e.o
+ _$s17SiriCloudSettings0abC9ViewModelC14accountManagerACSo011AIDAAccountG0C_tcfc
+ _$ss17_assertionFailure__4file4line5flagss5NeverOs12StaticStringV_SSAHSus6UInt32VtF
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/SiriSetup_Cloud/install/TempContent/Objects/SiriSetup.build/SiriCloudSettingsBundle.build/Objects-normal/arm64e/SiriCloudSettingsBundle-567050f5227268c8774a19df8e0463a6.o
- _$s17SiriCloudSettings0abC9ViewModelC7accountACSo9ACAccountCSg_tcfc
- _$s24com_apple_Dataclass_Siri0D19CloudSettingsBundleC7account9dataclassACSo9ACAccountC_So0jC0atcfcTf4gdn_n
- _objc_release_x21
- _objc_release_x24
- _objc_retain_x21
CStrings:
+ "Fatal error"
+ "com_apple_Dataclass_Siri/SiriCloudSettingsBundle.swift"
+ "init(account:dataclass:) has not been implemented"
- "Received account."
```
