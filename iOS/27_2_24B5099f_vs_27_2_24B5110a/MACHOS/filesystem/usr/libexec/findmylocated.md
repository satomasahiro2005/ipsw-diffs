## findmylocated

> `/usr/libexec/findmylocated`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ad6a4` | `0x5af0d4` | **`+0x1a30`** |
| `__TEXT.__eh_frame` | `0x4a270` | `0x4a450` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x1974c` | `0x1983c` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x727c` | `0x72fa` | **`+0x7e`** |
| `__TEXT.__const` | `0x20938` | `0x209a8` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x7234` | `0x7294` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x16478` | `0x164d8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x18878` | `0x188c8` | **`+0x50`** |
| `__TEXT.__cstring` | `0xbd92` | `0xbdc2` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x51f5` | `0x51c5` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x9114` | `0x9140` | **`+0x2c`** |
| `__TEXT.__objc_stubs` | `0x2100` | `0x20e0` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x45d0` | `0x45ec` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x1dc0` | `0x1dd8` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x4fdc` | `0x4ff0` | **`+0x14`** |
| `__DATA.__data` | `0xf380` | `0xf370` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x5d90` | `0x5da0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x7eed` | `0x7efd` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x299c` | `0x29ac` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xde8` | `0xde0` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x2ed0` | `0x2ed8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1778` | `0x1780` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-141.31.6.16.21
+141.31.6.16.22

-  Functions: 17812
-  Symbols:   2839
-  CStrings:  3931
+  Functions: 17836
+  Symbols:   2842
+  CStrings:  3934
Symbols:
+ _$s8Dispatch0A3QoSV0B6SClassO7utilityyA2EmFWC
+ _CLLocationCoordinate2DIsValid
+ _CNContactPhoneNumbersKey
CStrings:
+ "%{public}s: Dropping labeled location with invalid coordinate (lat: %{private}f, long: %{private}f)"
+ "[%{public}s] matchingContacts: finished, found %{public}ld match(es)"
+ "[%{public}s] matchingContacts: starting"
+ "labeledLocations(for:)"
+ "matchingContacts(predicate:keysToFetch:)"
- "ContactHandleCollaboration"
- "predicateForContactsMatchingPhoneNumber:prefixHint:"
```
