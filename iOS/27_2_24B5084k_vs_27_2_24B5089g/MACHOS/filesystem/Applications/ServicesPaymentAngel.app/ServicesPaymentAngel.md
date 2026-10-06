## ServicesPaymentAngel

> `/Applications/ServicesPaymentAngel.app/ServicesPaymentAngel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3aaf0` | `0x3b010` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x259f` | `0x268f` | **`+0xf0`** |
| `__TEXT.__cstring` | `0xcd1` | `0xcf1` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x34a9` | `0x34c9` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1960` | `0x1980` | **`+0x20`** |
| `__DATA.__data` | `0x1ed8` | `0x1ee8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1720` | `0x1730` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x14f8` | `0x1508` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xb48` | `0xb50` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xb98` | `0xba0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
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

-1.1.10.0.0
+1.1.11.0.0

-  Functions: 1214
-  Symbols:   3339
-  CStrings:  873
+  Functions: 1215
+  Symbols:   3342
+  CStrings:  878
Symbols:
+ _$s17ServicesPaymentUI25SubscriptionInviteRequestV20subscriptionFamilyId0G8InfoDataACSS_10Foundation0K0VSgtcfC
+ _$s20ServicesPaymentAngel33SubscriptionInviteSceneControllerC20subscriptionInfoData33_1B907FCF18E1E3EF8128A2D16F56D6D9LL4from10Foundation0J0VSgSDySSypG_tF
+ _objc_msgSend$dataWithJSONObject:options:error:
+ _swift_getDynamicType
- _$s17ServicesPaymentUI25SubscriptionInviteRequestV20subscriptionFamilyIdACSS_tcfC
Functions:
~ _$s20ServicesPaymentAngel33SubscriptionInviteSceneControllerC017createContentViewG05sceneSo06UIViewG0CSgSo016SBSUIRemoteAlertF0C_tF : 1244 -> 1264
+ _$s20ServicesPaymentAngel33SubscriptionInviteSceneControllerC20subscriptionInfoData33_1B907FCF18E1E3EF8128A2D16F56D6D9LL4from10Foundation0J0VSgSDySSypG_tF
CStrings:
+ "Subscription Invite request carried no subscriptionInfo"
+ "Subscription Invite subscriptionInfo was not an object; ignoring it. type=%s"
+ "Subscription Invite subscriptionInfo was not serializable JSON; ignoring it. error=%s"
+ "dataWithJSONObject:options:error:"
+ "subscriptionInfo"
```
