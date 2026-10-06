## libCRFSuite.dylib

> `/usr/lib/libCRFSuite.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f724` | `0x2f6c4` | **`-0x60`** |
| `__AUTH.__data` | `—` | `0x8` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```text
Functions:
~ _read_header_from_buffer : 228 -> 232
~ __ZNSt3__114random_shuffleB9fqe220106INS_11__wrap_iterIPiEEEEvT_S4_ : 200 -> 192
~ __ZN26ME_Efficient_Model_Trainer19add_training_sampleERK9ME_Sample : 628 -> 612
~ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqe220106EPKvm : 532 -> 520
~ __ZNSt3__16vectorIN26ME_Efficient_Model_Trainer6SampleENS_9allocatorIS2_EEE22__base_destruct_at_endB9fqe220106EPS2_ : 96 -> 84
~ __ZNSt3__116__insertion_sortB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN26ME_Efficient_Model_Trainer6SampleEEEvT1_S8_T0_ : 580 -> 572
~ __ZNSt3__126__insertion_sort_unguardedB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN26ME_Efficient_Model_Trainer6SampleEEEvT1_S8_T0_ : 624 -> 616
~ __ZNSt3__127__insertion_sort_incompleteB9fqe220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN26ME_Efficient_Model_Trainer6SampleEEEbT1_S8_T0_ : 900 -> 880
~ _maxent_classify : 224 -> 204
~ _maxent_sample_description : 476 -> 452
~ __ZL17svm_group_classesPK11svm_problemPiPS2_S3_S3_S2_ : 632 -> 636
~ _svm_check_parameter : 860 -> 864
~ __ZN3nlp12BurstTrieAddEPNS_10_BurstTrieEPKhjj : 432 -> 444
~ __ZN3nlp15BurstTrieRemoveEPNS_10_BurstTrieEPKhj : 2372 -> 2380
```
