## Seeding

> `/System/Library/PrivateFrameworks/Seeding.framework/Seeding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d2cc` | `0x1d28c` | **`-0x40`** |

### Other Changes

```text
Functions:
~ +[SDProfileUtilities getAssetAudienceIDForInstalledProfile:] : 700 -> 696
~ +[SDMDMConfigurator configureWithOfferProgramTokens:requireProgramToken:enrollmentPolicy:error:] : 828 -> 824
~ +[SDBetaProgram betaProgramWithJSON:] : 2268 -> 2264
~ -[SDBetaProgram isMDMProgram] : 256 -> 252
~ _SDPlatformsFromCommaSeparatedString : 292 -> 288
~ +[SDDevice _devicesMatchingPlatforms:] : 380 -> 376
~ -[SDBetaManager serverURLWithPath:arguments:] : 684 -> 680
~ -[SDBetaManager _queryProgramsForSystemAccountsWithPlatforms:disableBuildPrefixMatching:language:completion:] : 2380 -> 2376
~ ___59-[SDBetaManager validateBetaEnrollmentTokens:errorHandler:]_block_invoke : 1080 -> 1072
~ -[SDBetaManager _finallyQueryProgramsForSystemAccountsWithPlatforms:credentials:betaEnrollmentTokens:shouldSavePrograms:disableBuildPrefixMatching:language:completion:] : 1932 -> 1928
~ ___168-[SDBetaManager _finallyQueryProgramsForSystemAccountsWithPlatforms:credentials:betaEnrollmentTokens:shouldSavePrograms:disableBuildPrefixMatching:language:completion:]_block_invoke : 1744 -> 1736
~ -[SDBetaManager parseProgramsResponse:platforms:shouldCache:skipsBuildMatching:] : 788 -> 784
~ -[SDBetaManager availableBetaProgramsForPlatforms:] : 416 -> 412
~ -[SDBetaManager setIsMigratingFromProfiles:] : 756 -> 752
```
