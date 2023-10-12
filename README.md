# what you need :

1. revert roblox uwp first from : https://github.com/cerealwithmilk/uwp/releases

2. download fiddler : https://www.telerik.com/download/fiddler

3. make a folder anywhere on pc and put this text inside it : {"data":{"UpgradeAction":"None"}}

# tutorial

youtube video : https://www.youtube.com/watch?v=w1OtCf70P7s&ab_channel=farzad

1. download fiddler from : `https://www.telerik.com/download/fiddler` ( its trusted )
2. make sure you're on 32 bit roblox if not download : `https://github.com/cerealwithmilk/uwp/releases` ( Roblox 2.597.663 [hyperion-secured] )
3. Open fiddler
4. goto Tools, Options, HTTPS, and enable Decrypt HTTPS traffic
5. Run Roblox
6. in the output on Fiddler look for "www.roblox.com" and rightclick and then "copy" and click "just url"
7. goto AutoResponder and eanble "Enable rules" and "Unmatched requestpassthrough"
8. make a .txt file anywhere on ur pc and put inside it this code : `{"data":{"UpgradeAction":"None"}}` and save it
9. click "Add rule" and in "Rule Editor" put in the link you copied from 6.
10. in under it click on the dropdown and go open the .txt file from 8.
11. click save
12. open roblox boom done

# information

if you dont see www.roblox.com this is the url link u need ```https://www.roblox.com/mobileapi/check-app-version?appVersion=AppUWPV2.592.586```
