## SharedWebCredentials

> `/System/Library/PrivateFrameworks/SharedWebCredentials.framework/SharedWebCredentials`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14a30` | `0x14a48` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x244c` | `0x2450` | **`+0x4`** |

### Other Changes

```diff
Symbols:
+ __ZNKSt3__117basic_string_viewIcNS_11char_traitsIcEEE4findB9fqn220106EPKcm
+ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqn220106EPKvm
+ __ZNSt3__16vectorIcNS_9allocatorIcEEE20__throw_length_errorB9fqn220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
- __ZNKSt3__117basic_string_viewIcNS_11char_traitsIcEEE4findB9fqn220100EPKcm
- __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqn220100EPKvm
- __ZNSt3__16vectorIcNS_9allocatorIcEEE20__throw_length_errorB9fqn220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
Functions:
~ +[_SWCTrackingDomainInfo _trackingDomainInfoWithDomains:sources:] : 1240 -> 1236
~ -[_SWCPattern requiredEntitlement] : 256 -> 268
~ __ZNK17SWCPatternStorage8evaluateEP15NSURLComponentsPK10SWCFNMatchPK13audit_token_t : 1908 -> 1904
~ __ZNK17SWCPatternStorage7getSizeEv : 156 -> 168
~ +[_SWCPatternList patternListWithDetailsDictionary:defaults:] : 1016 -> 1008
~ +[_SWCPatternList patternListWithArray:] : 612 -> 608
~ -[_SWCPatternList initWithCoder:] : 1388 -> 1384
~ ___68+[_SWCSubstitutionVariableList cheapBuiltInSubstitutionVariableList]_block_invoke : 628 -> 656
~ __ZNK23SWCSubstitutionVariable7getSizeEv : 100 -> 120
~ ___72+[_SWCSubstitutionVariableList expensiveBuiltInSubstitutionVariableList]_block_invoke : 984 -> 976
~ ___71+[_SWCSubstitutionVariableList substitutionVariableListWithDictionary:]_block_invoke : 1364 -> 1356
~ -[_SWCSubstitutionVariableList initWithCoder:] : 1436 -> 1432
~ __ZNK23SWCSubstitutionVariable15getValuesNoCopyEv : 340 -> 344
~ __ZNK10SWCFNMatch8_executeERKNSt3__117basic_string_viewIcNS0_11char_traitsIcEEEES6_i : 1956 -> 1984
~ __ZNK10SWCFNMatch20_decodeUTF8CharacterEPKcS1_ : 408 -> 404
~ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqn220100EPKvm -> __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqn220106EPKvm : 1088 -> 1100
~ -[_SWCServiceSettings objectForKey:ofClass:valuesOfClass:] : 672 -> 668
~ +[_SWCServiceSpecifier(Private) _serviceSpecifiersWithEntitlementValue:serviceType:error:] : 1768 -> 1764
~ -[_SWCPrefs descriptionOfAllPrefs] : 516 -> 512
~ -[_SWCPrefs(Private) _recheckFuzzForSuccess:] : 88 -> 84
~ +[NSKeyedUnarchiver(SWCSecureCodingWorkaround) swc_unarchivedObjectOfClasses:fromData:error:] : 680 -> 676
~ -[NSCoder(SWCSecureCodingWorkaround) swc_decodeObjectOfClasses:forKey:] : 640 -> 636
~ +[_SWCServiceDetails(Synchronization) setAdditionalServiceDetailsForApplicationIdentifiers:usingContentsOfDictionary:completionHandler:] : 1088 -> 1084
~ ___110+[_SWCServiceDetails(Private) _serviceDetailsWithServiceSpecifier:URLComponents:limit:callerAuditToken:error:]_block_invoke_2 : 128 -> 124
~ __SWCLogHeader : 392 -> 396
~ -[_SWCDomain initWithString:] : 1172 -> 1164
~ -[_SWCDomain isValid] : 1728 -> 1720
```
