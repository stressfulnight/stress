game.ReplicatedStorage.Kick.OnClientEvent:Connect(function()
	local plr = game.Players.LocalPlayer
	plr:Kick("You Have Been Permanently Banned!")
end)
