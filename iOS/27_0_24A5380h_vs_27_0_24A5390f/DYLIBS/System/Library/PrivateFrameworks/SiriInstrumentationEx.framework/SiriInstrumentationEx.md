## SiriInstrumentationEx

> `/System/Library/PrivateFrameworks/SiriInstrumentationEx.framework/SiriInstrumentationEx`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21778c` | `0x21930c` | **`+0x1b80`** |
| `__AUTH_CONST.__objc_const` | `0x259f0` | `0x25d90` | **`+0x3a0`** |
| `__TEXT.__objc_methlist` | `0x18e04` | `0x19064` | **`+0x260`** |
| `__DATA.__bss` | `0x66800` | `0x66980` | **`+0x180`** |
| `__TEXT.__const` | `0x57464` | `0x575c4` | **`+0x160`** |
| `__AUTH.__objc_data` | `0x8200` | `0x82f0` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1be78` | `0x1bf30` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x5e4c` | `0x5efb` | **`+0xaf`** |
| `__AUTH_CONST.__cfstring` | `0x6760` | `0x6800` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x9938` | `0x99d0` | **`+0x98`** |
| `__DATA.__objc_ivar` | `0x199c` | `0x19bc` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xd00` | `0xd18` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0xd00` | `0xd18` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x13b8` | `0x13c8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x3340` | `0x334c` | **`+0xc`** |
| `__DATA.__data` | `0xa80` | `0xa88` | **`+0x8`** |

### Other Changes

```diff

-3600.79.1.0.0
+3600.80.1.0.0

-  Functions: 15192
-  Symbols:   13108
-  CStrings:  831
+  Functions: 15245
+  Symbols:   13185
+  CStrings:  836
Symbols:
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource cascadeFieldType]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource deleteCascadeFieldType]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource deleteNumEnrolledEntities]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource dictionaryRepresentation]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource hasCascadeFieldType]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource hasNumEnrolledEntities]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource hash]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource initWithDictionary:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource initWithJSON:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource isEqual:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource jsonData]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource numEnrolledEntities]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource readFrom:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource setCascadeFieldType:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource setHasCascadeFieldType:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource setHasNumEnrolledEntities:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource setNumEnrolledEntities:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource writeTo:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded deleteExists]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded dictionaryRepresentation]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded exists]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded hasExists]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded hash]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded initWithDictionary:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded initWithJSON:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded isEqual:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded jsonData]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded readFrom:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded setExists:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded setHasExists:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded writeTo:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent .cxx_destruct]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent appForegrounded]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent deleteAppForegrounded]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent dictionaryRepresentation]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent hasAppForegrounded]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent hash]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent initWithDictionary:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent initWithJSON:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent isEqual:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent jsonData]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent qualifiedMessageName]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent readFrom:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent setAppForegrounded:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent setHasAppForegrounded:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent whichEvent_Type]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent writeTo:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent(InstrumentationAdditions) getAnyEventType]
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource._cascadeFieldType
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource._has
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource._numEnrolledEntities
+ OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded._exists
+ OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded._has
+ OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALClientEvent._appForegrounded
+ _OBJC_CLASS_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ _OBJC_CLASS_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ _OBJC_CLASS_$_ODSIGNALSiriSchemaODSIGNALClientEvent
+ _OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALClientEvent._hasAppForegrounded
+ _OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALClientEvent._whichEvent_Type
+ _OBJC_METACLASS_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ _OBJC_METACLASS_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ _OBJC_METACLASS_$_ODSIGNALSiriSchemaODSIGNALClientEvent
+ __OBJC_$_INSTANCE_METHODS_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_$_INSTANCE_METHODS_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_$_INSTANCE_METHODS_ODSIGNALSiriSchemaODSIGNALClientEvent(InstrumentationAdditions)
+ __OBJC_$_INSTANCE_VARIABLES_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_$_INSTANCE_VARIABLES_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_$_INSTANCE_VARIABLES_ODSIGNALSiriSchemaODSIGNALClientEvent
+ __OBJC_$_PROP_LIST_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_$_PROP_LIST_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_$_PROP_LIST_ODSIGNALSiriSchemaODSIGNALClientEvent
+ __OBJC_CLASS_RO_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_CLASS_RO_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_CLASS_RO_$_ODSIGNALSiriSchemaODSIGNALClientEvent
+ __OBJC_METACLASS_RO_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_METACLASS_RO_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_METACLASS_RO_$_ODSIGNALSiriSchemaODSIGNALClientEvent
CStrings:
+ "appForegrounded"
+ "cascadeFieldType"
+ "com.apple.aiml.siri.odsignal.ODSIGNALClientEvent"
+ "com.apple.aiml.siri.odsignal.ODSIGNALClientEvent.ODSIGNALAppForegrounded"
+ "numEnrolledEntities"
```
