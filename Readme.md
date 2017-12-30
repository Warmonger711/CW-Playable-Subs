---
### Recent Major Changes
* 12/30/2017 - New Class: Nautilus Class SSN (USA), original and improved 1974 versions. We've also updated the Sonar Signature list - now, when you're trying to classify a contact on the Sonar screen, scrolling RIGHT will take you straight to the NATO subs, and scrolling back to the LEFT will take you straight to the Russian subs. The sorting images should still work properly. Also updated the vessel lists for all campaigns and single missions to match the order of the Reference screen.

* 12/23/2017 - We're now up to 4 total playable surface ships: Perry Class Frigate, Iowa Class Battleship, Poti Class Corvette, and Kirov Class Battlecruiser. We've added Single Missions 37 and 38, convoy strike missions, for the new ships. Be aware that the stats on these ships are beefed up for gameplay purposes, since surface warfare wasn't intended in this game - they're not real world stats and never will be.

* 12/21/2017 - Typhoon periscope depth has finally been fixed! Due to a small bug, we have to set the Typhoon at 60ft for periscope depth right now, which can cause the sail to become exposed during high sea states, but hopefully that small bug will be fixed soon and we can change it to 65ft, which is the ideal depth. All other bugs with the Typhoon should now be resolved.

-----
### Info For Players
* To download the latest version of the mod, simply click the green "Clone or Download" button above and choose "Download ZIP". This will download the latest override file to your PC, then you just install it like you normally would.

* The mod is under constant development and will undergo changes at random. You can see the latest updates to the mod listed next to the override folder, along with how recently the mod itself was changed. If you'd like to see the history of all recent changes, you can click the "### Commits" button right below the title text of the page and you'll see a list of every change submitted to the mod, which you can click on their numbers and see any notes left.

* We will attempt to list all recent major changes to the mod on this page right below this section. You won't see minor bug fixes listed, but when we change something major, we'll try to post it below.

* If you have a bug report, the best place to let us know about it is the Discord channel (linked at the top of this page), however you can also post on the forums on Steam (http://steamcommunity.com/app/541210/discussions/3/1353742967803190823) or Subsim (http://www.subsim.com/radioroom/showthread.php?t=231690) and we'll see it there as well.

-----
## Developer Announcements
_Important & urgent information for the mod developers will appear in this section._

* ### **URGENT: All developers need to keep their Github branches up to date! We are losing changes and reverting back to old versions of files way too often. Before beginning to work on your own files, make sure you use the Github Desktop App to Sync the latest files from the master branch!! THIS IS ABSOLUTELY VITAL!!**

* **When adding a new sub class to the mod, please also add it to the campaign files and the appropriate single mission files so that it's available for use by players. I can't continue to keep track of this alone. Please make sure you add your new class in the appropriate spot on the sub list (keep the same nations grouped together). These are the files that must be updated when a new class is added:**
  * override\campaign\campaign001\summary.txt
  * override\campaign\campaign002\summary.txt
  * override\campaign\campaign003\summary.txt
  * override\campaign\campaign004\summary.txt
  * override\campaign\campaign005\summary.txt
  * override\campaign\campaign006\summary.txt
  * Single Missions 1 & 3 - NATO Subs Only
  * Single Missions 2 & 4 - Russian Subs Only
  * Single Mission 5 - NATO SSBNs Only
  * Single Mission 6 - Russian SSBNs Only
  * Single Mission 7 - All Subs
  * Single Mission 9 - Advanced Modern Subs Only
  * Single Missions 10 thru 27 - All Subs
  * Single Mission 28 - ANY new units sections 1 and 3. All playable subs sections 1 and 2 and "campaign/maps/norwegian_sea_traffic.txt".
  * Single Mission 30 - NATO SSBNs Only (Must have working SLBMs!)
  * Single Mission 31 - Russian SSBNs Only (Must have working SLBMs!)
  * Single Mission 32 & 34 - NATO Subs Only
  * Single Mission 33 & 35 - Russian Subs Only
  * Single Mission 36 - All Playable Surface Ships
  * Single Mission 37 - NATO Playable Surface Ships
  * Single Mission 38 - Russian Playable Surface Ships
  
  ##Any units are now to be added into the "campaign/maps/norwegian_sea_traffic.txt" file in the OtherVessels section (Vessel List order) so that they will appear in the in-game reference and sonar. Everything now pulls from this one file.
-----

### Info For Developers
* If you'd like to become a mod contributor, please contact CaptainX3 on the Discord channel located here: https://discord.gg/mMvpzSV
* Being a developer requires you to be on the Discord server. This is our primary method of communication.
* We'd like to keep this mod at the highest quality, so we ask and expect that all developers contribute work that is close to or equal to the original vanilla quality of the game. Substandard work will be rejected, and repeated issues will result in you being removed as a mod developer.
* When creating new units for the game, we use Wikipedia as our first choice for stats. If Wikipedia does not have stats available for your chosen unit, then you may seek alternative sources, however they must be at least credible enough to cite to the general public. **If Wikipedia has stats on your chosen unit, you are expected to use those unless you have a disputing credible source that you believe to be more correct than Wikipedia. Do not create units with stats "pulled out of the air."**
* Respect each other's work. If you didn't create something in the mod but you'd like to change it, talk to the original creator first if possible. It's rude to change others' work without asking.
