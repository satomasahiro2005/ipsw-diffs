## com.apple.driver.AppleS8000AES

> `com.apple.driver.AppleS8000AES`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x412c` | `0x4270` | **`+0x144`** |

### Other Changes

```text
Functions:
~ sub_fffffff0093edb70 -> sub_fffffff009462310 : 72 -> 76
~ sub_fffffff0093edbc0 -> sub_fffffff009462364 : 52 -> 56
~ sub_fffffff0093edbf4 -> sub_fffffff00946239c : 52 -> 56
~ sub_fffffff0093edc38 -> sub_fffffff0094623e4 : 68 -> 72
~ sub_fffffff0093edca4 -> sub_fffffff009462454 : 72 -> 76
~ sub_fffffff0093edcec -> sub_fffffff0094624a0 : 104 -> 108
~ sub_fffffff0093edd68 -> sub_fffffff009462520 : 88 -> 92
~ sub_fffffff0093eddc0 -> sub_fffffff00946257c : 88 -> 92
~ sub_fffffff0093ede18 -> sub_fffffff0094625d8 : 72 -> 76
~ sub_fffffff0093ede68 -> sub_fffffff00946262c : 52 -> 56
~ sub_fffffff0093ede9c -> sub_fffffff009462664 : 52 -> 56
~ sub_fffffff0093edee0 -> sub_fffffff0094626ac : 68 -> 72
~ sub_fffffff0093edf4c -> sub_fffffff00946271c : 72 -> 76
~ sub_fffffff0093edf94 -> sub_fffffff009462768 : 104 -> 108
~ sub_fffffff0093ee010 -> sub_fffffff0094627e8 : 88 -> 92
~ sub_fffffff0093ee068 -> sub_fffffff009462844 : 88 -> 92
~ _OUTLINED_FUNCTION_0 : 2492 -> 2496
~ __ZN24AppleS8000AESAccelerator18_interruptOccurredEP22IOInterruptEventSourcei : 244 -> 248
~ sub_fffffff0093eeb70 -> sub_fffffff009463358 : 256 -> 260
~ sub_fffffff0093eec8c -> sub_fffffff009463478 : 184 -> 188
~ _OUTLINED_FUNCTION_2 : 72 -> 76
~ sub_fffffff0093eed8c -> sub_fffffff009463580 : 232 -> 236
~ __ZN24AppleS8000AESAccelerator10_enableAESEb : 784 -> 788
~ __ZN24AppleS8000AESAccelerator13_configureAESEP23IOAESAcceleratorCommandj : 2596 -> 2600
~ __ZN24AppleS8000AESAccelerator16_space_availableEj : 332 -> 336
~ sub_fffffff0093efe08 -> sub_fffffff00946460c : 104 -> 108
~ __ZN24AppleS8000AESAccelerator16_distribute_dkeyEv : 164 -> 168
~ __ZN24AppleS8000AESAccelerator17performAESQuantumEP23IOAESAcceleratorCommand : 1620 -> 1624
~ __ZN24AppleS8000AESAccelerator16_prepareTransferEjjP12IODMACommandS1_yyy : 616 -> 620
~ __ZN24AppleS8000AESAccelerator15_handleIVBounceEP7IOAESIVt : 260 -> 264
~ __ZN24AppleS8000AESAccelerator12_completeAESEv : 920 -> 924
~ __ZN24AppleS8000AESAccelerator13getDTPropertyEPKcP9IOServicePj : 240 -> 244
~ __ZN24AppleS8000AESAccelerator14OverrideRegMapEP9IOService : 496 -> 500
~ __ZN24AppleS8000AESAccelerator13_push_commandEPvj : 256 -> 260
~ __GLOBAL__sub_I_AppleS8000AES.cpp : 160 -> 164
~ sub_fffffff0093f12dc -> sub_fffffff009465b08 : 56 -> 60
~ _panic : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.2 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.3 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.4 : 44 -> 48
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.5 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.6 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.7 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.8 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.9 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.10 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.11 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.12 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.13 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator5startEP9IOService.cold.14 : 40 -> 44
~ __ZN24AppleS8000AESAccelerator18_interruptOccurredEP22IOInterruptEventSourcei.cold.1 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator4stopEP9IOService.cold.1 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator10_enableAESEb.cold.1 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator10_enableAESEb.cold.2 : 44 -> 48
~ __ZN24AppleS8000AESAccelerator10_enableAESEb.cold.3 : 44 -> 48
~ __ZN24AppleS8000AESAccelerator13_configureAESEP23IOAESAcceleratorCommandj.cold.1 : 44 -> 48
~ __ZN24AppleS8000AESAccelerator17_push_command_keyEjjPhS0_b.cold.1 : 60 -> 64
~ __ZN24AppleS8000AESAccelerator16_distribute_dkeyEv.cold.1 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator17performAESQuantumEP23IOAESAcceleratorCommand.cold.1 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator12_completeAESEv.cold.2 : 52 -> 56
~ sub_fffffff0093f1868 -> sub_fffffff0094660f8 : 28 -> 32
~ sub_fffffff0093f1884 -> sub_fffffff009466118 : 28 -> 32
~ sub_fffffff0093f18a0 -> sub_fffffff009466138 : 28 -> 32
~ __ZN24AppleS8000AESAccelerator12_completeAESEv.cold.3 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator12_completeAESEv.cold.4 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator12_completeAESEv.cold.6 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator12_completeAESEv.cold.7 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator17performAESQuantumEP23IOAESAcceleratorCommand.cold.10 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator15_handleIVBounceEP7IOAESIVt.cold.1 : 52 -> 56
~ _OUTLINED_FUNCTION_1 : 52 -> 56
~ sub_fffffff0093f1a28 -> sub_fffffff0094662e0 : 52 -> 56
~ sub_fffffff0093f1a5c -> sub_fffffff009466318 : 52 -> 56
~ sub_fffffff0093f1a90 -> sub_fffffff009466350 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator12_completeAESEv.cold.5 : 52 -> 56
~ sub_fffffff0093f1af8 -> sub_fffffff0094663c0 : 52 -> 56
~ sub_fffffff0093f1b2c -> sub_fffffff0094663f8 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator12_completeAESEv.cold.8 : 52 -> 56
~ __ZN24AppleS8000AESAccelerator13getDTPropertyEPKcP9IOServicePj.cold.1 : 84 -> 88
~ __ZN24AppleS8000AESAccelerator16_space_availableEj.cold.1 : 60 -> 64
~ __ZN24AppleS8000AESAccelerator13_push_commandEPvj.cold.1 : 60 -> 64
~ __ZN24AppleS8000AESAccelerator13_push_commandEPvj.cold.2 : 60 -> 64
```
