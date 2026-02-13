# C_Gossip



**Members:** 41  •  **Functions:** 29  •  **Interface calls:** 53 (across up to 6 files)




**Defined in Interface Lua:** yes




**Definition / evidence:** `FrameXML/Util/C_Gossip.lua` line 1




## Members



| Member | Kind | Syntax / access | Example (from Interface) |
| --- | --- | --- | --- |
| CheckHookItemHide | function | C_Gossip:CheckHookItemHide(arg1) | function C_Gossip:CheckHookItemHide(id) |
| CheckHookItemShow | function | C_Gossip:CheckHookItemShow(arg1) | function C_Gossip:CheckHookItemShow(id) |
| CheckHookNPCHide | function | C_Gossip:CheckHookNPCHide(arg1) | function C_Gossip:CheckHookNPCHide(id) |
| CheckHookNPCShow | function | C_Gossip:CheckHookNPCShow(arg1) | function C_Gossip:CheckHookNPCShow(id) |
| CheckItemHide | function | C_Gossip:CheckItemHide(arg1) | function C_Gossip:CheckItemHide(id) |
| CheckItemShow | function | C_Gossip:CheckItemShow(arg1) | function C_Gossip:CheckItemShow(id) |
| CheckNPCHide | function | C_Gossip:CheckNPCHide(arg1) | function C_Gossip:CheckNPCHide(id) |
| CheckNPCShow | function | C_Gossip:CheckNPCShow(arg1) | function C_Gossip:CheckNPCShow(id) |
| GOSSIP_CLOSED | function | C_Gossip:GOSSIP_CLOSED() | function C_Gossip:GOSSIP_CLOSED() |
| GOSSIP_SHOW | function | C_Gossip:GOSSIP_SHOW() | function C_Gossip:GOSSIP_SHOW() |
| HookItem | function | C_Gossip:HookItem(arg1, arg2, arg3) | function C_Gossip:HookItem(id, show, hide) |
| HookItems | function | C_Gossip:HookItems(arg1, arg2, arg3) | function C_Gossip:HookItems(group, show, hide) |
| HookNPC | function | C_Gossip:HookNPC(arg1, arg2, arg3) | function C_Gossip:HookNPC(id, show, hide) |
| HookNPCs | function | C_Gossip:HookNPCs(arg1, arg2, arg3) | function C_Gossip:HookNPCs(group, show, hide) |
| MakeGroup | function | C_Gossip:MakeGroup(arg1) | local arenaNPCs = C_Gossip:MakeGroup(18897, 19856, 19861, 29534, 30611, |
| RedirectItem | function | C_Gossip:RedirectItem(arg1, arg2, arg3) | function C_Gossip:RedirectItem(id, show, hide) |
| RedirectItems | function | C_Gossip:RedirectItems(arg1, arg2, arg3) | function C_Gossip:RedirectItems(group, show, hide) |
| RedirectNPC | function | C_Gossip:RedirectNPC(arg1, arg2) | C_Gossip:RedirectNPC(npcID, GenerateClosure(self.OnGossipShow, self), GenerateClosure(self.OnGoss... |
| RedirectNPCs | function | C_Gossip:RedirectNPCs(arg1, arg2, arg3) | C_Gossip:RedirectNPCs(arenaNPCs, OnShowGossip) |
| RemoveHookItem | function | C_Gossip:RemoveHookItem(arg1) | function C_Gossip:RemoveHookItem(handle) |
| RemoveHookNPC | function | C_Gossip:RemoveHookNPC(arg1) | function C_Gossip:RemoveHookNPC(handle) |
| RemoveRedirectItem | function | C_Gossip:RemoveRedirectItem(arg1) | function C_Gossip:RemoveRedirectItem(id) |
| RemoveRedirectItems | function | C_Gossip:RemoveRedirectItems(arg1) | function C_Gossip:RemoveRedirectItems(group) |
| RemoveRedirectNPC | function | C_Gossip:RemoveRedirectNPC(arg1) | function C_Gossip:RemoveRedirectNPC(id) |
| RemoveRedirectNPCs | function | C_Gossip:RemoveRedirectNPCs(arg1) | function C_Gossip:RemoveRedirectNPCs(group) |
| RestoreGossip | function | C_Gossip:RestoreGossip() | C_Gossip:RestoreGossip() |
| SilentHideGossip | function | C_Gossip:SilentHideGossip() | C_Gossip:SilentHideGossip() |
| _hookItem.generateHandle | function | C_Gossip._hookItem.generateHandle(...) |  |
| _hookNPC.generateHandle | function | C_Gossip._hookNPC.generateHandle(...) |  |
| _hookItem | table | C_Gossip._hookItem |  |
| _hookItem.hide | table | C_Gossip._hookItem.hide |  |
| _hookItem.show | table | C_Gossip._hookItem.show |  |
| _hookNPC | table | C_Gossip._hookNPC |  |
| _hookNPC.hide | table | C_Gossip._hookNPC.hide |  |
| _hookNPC.show | table | C_Gossip._hookNPC.show |  |
| _redirectItem | table | C_Gossip._redirectItem |  |
| _redirectItem.hide | table | C_Gossip._redirectItem.hide |  |
| _redirectItem.show | table | C_Gossip._redirectItem.show |  |
| _redirectNPC | table | C_Gossip._redirectNPC |  |
| _redirectNPC.hide | table | C_Gossip._redirectNPC.hide |  |
| _redirectNPC.show | table | C_Gossip._redirectNPC.show |  |
