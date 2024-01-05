my notes
It should also be possible to copy the config files in place rather than cyclicly generating and editing them.

https://d-mp.org/downloads
client and server

# sudo apt install dotnet6
# no -- it really does want mono; dotnet5+ vs dotnet framework?
sudo apt install mono-runtime
mono ./DMPServer.exe

start server; quit; edit Config/Settings.txt
gameMode=CAREER
gameDifficulty=CUSTOM
whitelisted=True

start server; quit; edit Config/GameplaySettings.txt
allowStockVessels=True
autoHireCrews=False
bypassEntryPurchaseAfterResearch=False
allowNegativeCurrency=True
obeyCrossfeedRules=True
requireSignalForControl=True
occlusionModifierVac=1
occlusionModifierAtm=1
extraGroundstations=False

generate blacklist; copy mod-control.txt (or just the parts list)

start server; /whitelist add <desiredUser>

