# C_PlayerPoll



**Members:** 9  •  **Functions:** 9  •  **Interface calls:** 26 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanChangeQuestionChoice | function | C_PlayerPoll.CanChangeQuestionChoice(arg1) | if C_PlayerPoll.CanChangeQuestionChoice(i) then |
| CanSubmitAnswer | function | C_PlayerPoll.CanSubmitAnswer(arg1, arg2, arg3) | local canSubmit = C_PlayerPoll.CanSubmitAnswer(self.questionIndex, self.selectedIndex, self.Addit... |
| GetNumQuestionChoices | function | C_PlayerPoll.GetNumQuestionChoices(arg1) | for j = 1, C_PlayerPoll.GetNumQuestionChoices(i) do |
| GetNumQuestions | function | C_PlayerPoll.GetNumQuestions() | if C_PlayerPoll.GetNumQuestions() > 0 then |
| GetQuestionChoiceInfo | function | C_PlayerPoll.GetQuestionChoiceInfo(arg1, arg2) | local _, isSelected = C_PlayerPoll.GetQuestionChoiceInfo(i, j) |
| GetQuestionInfo | function | C_PlayerPoll.GetQuestionInfo(arg1) | local _, questionText = C_PlayerPoll.GetQuestionInfo(self.index) |
| HasUnansweredQuestions | function | C_PlayerPoll.HasUnansweredQuestions() | if C_PlayerPoll.HasUnansweredQuestions() then |
| RequestQuestionList | function | C_PlayerPoll.RequestQuestionList(...) |  |
| SubmitAnswer | function | C_PlayerPoll.SubmitAnswer(arg1, arg2, arg3) | C_PlayerPoll.SubmitAnswer(self.questionIndex, self.selectedIndex, additionalInfo) |
