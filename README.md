# attachments
 
 
 1. Import the qb-weapons 'config' file
 2. Then you need to add the attachments items to shared.lua (Are in the folder).
 3. Add these to Server-Main.lua at the bottom 


QBCore.Functions.CreateUseableItem('flashlight', function(source, item)
    TriggerClientEvent('weapons:client:EquipAttachment', source, item, 'flashlight')
end)

QBCore.Functions.CreateUseableItem('grip', function(source, item)
    TriggerClientEvent('weapons:client:EquipAttachment', source, item, 'grip')
end)

QBCore.Functions.CreateUseableItem('drum', function(source, item)
    TriggerClientEvent('weapons:client:EquipAttachment', source, item, 'drum')
end)

QBCore.Functions.CreateUseableItem('scope', function(source, item)
    TriggerClientEvent('weapons:client:EquipAttachment', source, item, 'scope')
end)

QBCore.Functions.CreateUseableItem('suppressor', function(source, item)
    TriggerClientEvent('weapons:client:EquipAttachment', source, item, 'suppressor')
end)


 5. And then youre done :) Good Luck



QBCore

Made by Kimmers

Contact: ! Kimmers#8808 if you have questions
   
