    local success = exports['mazebank_pc']:StartMazeBankPC()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end