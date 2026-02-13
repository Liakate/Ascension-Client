# C_PlayerTicket



**Members:** 14  •  **Functions:** 14  •  **Interface calls:** 17 (across up to 3 files)




**Defined in Interface Lua:** no




**Definition / evidence:** not defined in Interface Lua (likely native client API)




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CanCloseTicket | function | C_PlayerTicket.CanCloseTicket() | local canClose, reason = C_PlayerTicket.CanCloseTicket() |
| CanCreateTicket | function | C_PlayerTicket.CanCreateTicket(arg1, arg2, arg3, arg4, arg5) | local canCreate, reason = C_PlayerTicket.CanCreateTicket(priority, category, title, content, char... |
| CanMarkResponseSeen | function | C_PlayerTicket.CanMarkResponseSeen(...) |  |
| CanReopenTicket | function | C_PlayerTicket.CanReopenTicket() | if C_PlayerTicket.CanReopenTicket() then |
| CanSendTicketMessage | function | C_PlayerTicket.CanSendTicketMessage(arg1, arg2, arg3) | local canSend, reason = C_PlayerTicket.CanSendTicketMessage(nil, message, false) |
| CloseTicket | function | C_PlayerTicket.CloseTicket() |  |
| CreateTicket | function | C_PlayerTicket.CreateTicket(arg1, arg2, arg3, arg4, arg5) | if C_PlayerTicket.CreateTicket(priority, category, title, content, characterName) then |
| GetCurrentTicket | function | C_PlayerTicket.GetCurrentTicket() | local hasTicket = C_PlayerTicket.GetCurrentTicket() ~= nil |
| GetTicketMessage | function | C_PlayerTicket.GetTicketMessage(...) |  |
| GetTicketMessages | function | C_PlayerTicket.GetTicketMessages() | local messages = C_PlayerTicket.GetTicketMessages() |
| IsResponseSeen | function | C_PlayerTicket.IsResponseSeen(arg1) | if self:GetID() ~= 0 and not C_PlayerTicket.IsResponseSeen(self:GetID()) then |
| MarkResponseSeen | function | C_PlayerTicket.MarkResponseSeen(arg1, arg2) | C_PlayerTicket.MarkResponseSeen(nil, self:GetID()) |
| ReopenTicket | function | C_PlayerTicket.ReopenTicket() | C_PlayerTicket.ReopenTicket() |
| SendTicketMessage | function | C_PlayerTicket.SendTicketMessage(arg1, arg2, arg3) | if C_PlayerTicket.SendTicketMessage(nil, message, false) then |
