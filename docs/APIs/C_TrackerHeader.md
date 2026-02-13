# C_TrackerHeader



**Members:** 35  •  **Functions:** 7  •  **Interface calls:** 14 (across up to 2 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Ascension_TrackerHeader/Ascension_TrackerHeader.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CHALLENGE_COMPLETED | function | C_TrackerHeader:CHALLENGE_COMPLETED(arg1, arg2) | function C_TrackerHeader:CHALLENGE_COMPLETED(challengeID, level) |
| CHALLENGE_CRITERIA_COMPLETED | function | C_TrackerHeader:CHALLENGE_CRITERIA_COMPLETED(arg1, arg2, arg3, arg4, arg5, arg6) | function C_TrackerHeader:CHALLENGE_CRITERIA_COMPLETED(challengeID, level, requirementType, value1... |
| CHALLENGE_CRITERIA_FAILED | function | C_TrackerHeader:CHALLENGE_CRITERIA_FAILED(arg1, arg2, arg3, arg4, arg5, arg6) | function C_TrackerHeader:CHALLENGE_CRITERIA_FAILED(challengeID, level, requirementType, value1, v... |
| CHALLENGE_DEATH_UPDATE | function | C_TrackerHeader:CHALLENGE_DEATH_UPDATE(arg1, arg2, arg3) | function C_TrackerHeader:CHALLENGE_DEATH_UPDATE(challengeID, remainingLives, totalLives) |
| CHALLENGE_FAILURE_ADDED | function | C_TrackerHeader:CHALLENGE_FAILURE_ADDED(arg1, arg2) | function C_TrackerHeader:CHALLENGE_FAILURE_ADDED(challengeID, level) |
| Hide | function | C_TrackerHeader:Hide() | function C_TrackerHeader:Hide() |
| Show | function | C_TrackerHeader:Show(arg1, arg2, arg3, arg4, arg5, arg6, arg7) | function C_TrackerHeader:Show(template, title, subText, sound, fadeInDuration, holdTime, fadeOutD... |
| ChallengeCompleted.subTextY | number | C_TrackerHeader.ChallengeCompleted.subTextY |  |
| ChallengeCompleted.titleY | number | C_TrackerHeader.ChallengeCompleted.titleY |  |
| ChallengeCriteriaFailed.subTextY | number | C_TrackerHeader.ChallengeCriteriaFailed.subTextY |  |
| ChallengeCriteriaFailed.titleY | number | C_TrackerHeader.ChallengeCriteriaFailed.titleY |  |
| ChallengeCriteriaSuccess.subTextY | number | C_TrackerHeader.ChallengeCriteriaSuccess.subTextY |  |
| ChallengeCriteriaSuccess.titleY | number | C_TrackerHeader.ChallengeCriteriaSuccess.titleY |  |
| ChallengeDeath.subTextY | number | C_TrackerHeader.ChallengeDeath.subTextY |  |
| ChallengeDeath.titleY | number | C_TrackerHeader.ChallengeDeath.titleY |  |
| ChallengeFailed.subTextY | number | C_TrackerHeader.ChallengeFailed.subTextY |  |
| ChallengeFailed.titleY | number | C_TrackerHeader.ChallengeFailed.titleY |  |
| ChallengeRedemption.subTextY | number | C_TrackerHeader.ChallengeRedemption.subTextY |  |
| ChallengeRedemption.titleY | number | C_TrackerHeader.ChallengeRedemption.titleY |  |
| Alliance.Banner | string | C_TrackerHeader.Alliance.Banner |  |
| ChallengeCompleted.Banner | string | C_TrackerHeader.ChallengeCompleted.Banner |  |
| ChallengeCriteriaFailed.Banner | string | C_TrackerHeader.ChallengeCriteriaFailed.Banner |  |
| ChallengeCriteriaSuccess.Banner | string | C_TrackerHeader.ChallengeCriteriaSuccess.Banner |  |
| ChallengeDeath.Banner | string | C_TrackerHeader.ChallengeDeath.Banner |  |
| ChallengeFailed.Banner | string | C_TrackerHeader.ChallengeFailed.Banner |  |
| ChallengeRedemption.Banner | string | C_TrackerHeader.ChallengeRedemption.Banner |  |
| Horde.Banner | string | C_TrackerHeader.Horde.Banner |  |
| Alliance | table | C_TrackerHeader.Alliance |  |
| ChallengeCompleted | table | C_TrackerHeader.ChallengeCompleted |  |
| ChallengeCriteriaFailed | table | C_TrackerHeader.ChallengeCriteriaFailed |  |
| ChallengeCriteriaSuccess | table | C_TrackerHeader.ChallengeCriteriaSuccess |  |
| ChallengeDeath | table | C_TrackerHeader.ChallengeDeath |  |
| ChallengeFailed | table | C_TrackerHeader.ChallengeFailed |  |
| ChallengeRedemption | table | C_TrackerHeader.ChallengeRedemption |  |
| Horde | table | C_TrackerHeader.Horde |  |
