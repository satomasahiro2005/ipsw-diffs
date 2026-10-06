## Health

> `/private/var/staged_system_apps/Health.app/Health`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcd1b8` | `0xcd288` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x545e` | `0x544e` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  CStrings:  1690
+  CStrings:  1692
Symbols:
+ _$s19HealthAppServicesUI25HASUIDataEntryViewFactoryV04datafG10Controller3for16customInputValue17viewConfiguration0a10ExperienceD004DatafG17DelegateProviding_So06UIViewJ0CXcSo12HKObjectTypeC_AA0efmN0VSgAA0efgP0VtKF
- _$s19HealthAppServicesUI25HASUIDataEntryViewFactoryV04datafG10Controller3for16customInputValue17viewConfigurationSo06UIViewJ0CSo12HKObjectTypeC_AA0efmN0VSgAA0efgP0VtKF
Functions:
~ sub_100062248 : 1592 -> 1652
~ sub_100098d58 -> sub_100098d94 : 1424 -> 1416
~ sub_100099f9c -> sub_100099fd0 : 1228 -> 1220
~ sub_1000a2e14 -> sub_1000a2e40 : 256 -> 284
~ sub_1000a3598 -> sub_1000a35e0 : 1520 -> 1656
CStrings:
+ "SignificantChange-Localizable"
+ "significant_change_description"
+ "significant_change_waiting_button"
+ "significant_change_waiting_message"
+ "significant_change_waiting_title"
+ "significant_change_warming_button"
+ "significant_change_warming_message"
+ "significant_change_warming_title"
- "Approval Required"
- "Ask for Approval"
- "Ask for Approval Again"
- "There has been some changes to Health"
- "This Health update has some new features. You'll need approval from your parent or guardian to continue using the app."
- "You'll be able to use Health after your parent or guardian approves your request."
```
