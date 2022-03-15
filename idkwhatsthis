print("HI")
workspace.__THINGS.__REMOTES.MAIN:FireServer("b", "bank withdraw")
local function Bank(id)
   local self = {}
   function self:withdraw(pets, gems)
local A_1 = 
{
    [1] = id, 
    [2] = 
{
}, 
    [3] = gems
}
        local Event = game:GetService("Workspace")["__THINGS"]["__REMOTES"]["bank withdraw"]
        Event:InvokeServer(A_1)
   end
   return self
end
--//
local bankid = "8d4144c3-7114-4f55-9cc6-77f92b24e892"--bank
for i=1, 1000 do
   Bank(bankid):withdraw({}, 1)
   print('withdrawed 1 gem')
   task.wait(1.7)
end
