[简体中文](../README.md) | English
--------

Win7Games Language Lite (supports running with Wine)
========
Win7Games Language Lite (retaining only English (en-US) and Simplified Chinese (zh_CN) language versions), and supporting the use of Wine to run them on Linux!

How should I run them?
==========
1. Download file:
- If you have installed Git, you can directly run the following command to clone this repository:
```
git clone https://github.com/Al2SO43/Win7Games.git
```
- If you haven't installed Git, you can click on the "Code" button in this repository and select "Download ZIP" to download the repository file.
- You can also download the corresponding compressed file on the Releases page of this repository, extract it to a specified directory, and open it!

2.Run the game:
- If you are using a Windows system:
  1. You can directly run the corresponding exe executable file of the game and start playing the game.
  2. If there are any issues, please refer to the "Frequently Asked Questions" section below.
- If you are using a Linux system:
  1. Ensure that you have installed Wine and configured the environment (you can search for installation tutorials on your own).
  2. Install some necessary fonts (especially for game versions that use Simplified Chinese language, this repository has prepared some Simplified Chinese fonts in advance, just install them), otherwise it may cause some text display errors or non display issues.
  3. Ensure that Winetracks has been installed (you can search for installation tutorials on your own). 
  4. Install wmp11 (Windows Media Player) in Winetracks or execute the following command on the terminal to install Windows Media Player: ```winetricks -q wmp11```
  5. Open the terminal, switch to the game directory, and use Wine to run the corresponding exe file for the game.
  6. If there are any issues, please refer to the "Frequently Asked Questions" section below.

Frequently Asked Questions and Special Acknowledgements
========
1. Common problem description:
   - Windows:Why is there no response when I click on the game exe executable file?
     1. Please try adjusting the game by right clicking on the game exe executable, selecting "Properties", and then adjusting it in the "Compatibility" tab.
     2. If it still cannot run, please try installing the original Win7GamesForWindows version (not simplified version) directly,[click here to go to the corresponding website](https://win7games.com/).
   - Linux Wine:Why do I have abnormal font display when running games in Wine environment?
     1. Please try installing more fonts related to the language you are using, as this may solve the problem.
     2. If the issue persists, please try running a simplified English language version of the game.
   - Linux Wine:Why is there no sound in my game?
     1. Due to some issues, the current version of the game cannot play these game sound effects, and only a small number of games can play their own sound effects. If you have a better solution, please feel free to contact our warehouse manager!
   - Linux Wine:Why can't I freely control the window size of my game (especially when I change the window size, the game freezes)?
     1. Due to some issues, the current version of the game cannot freely control the window size, but there are times when it is possible. If you have a better solution, please feel free to contact our warehouse manager!
   - Linux Wine:Why is my game too laggy in some scenes?
     1. Due to some issues, the current version of the game may experience screen lag in some scenarios (especially in chess), and you can choose to reduce the screen effect appropriately. If you have a better solution, please feel free to contact our warehouse manager!
   - Linux Wine: Why can't my game run and keep popping up a lot of error messages?
     1. Please try changing to a different wine version or installing more possible dependencies. If the problem cannot be solved, you can search for a solution on your own.
   - Deepin/UOS：Why can't the Windows compatibility engine run these games?
     1. Due to some issues, this game cannot run directly in this environment. But you can run these games by deploying the Wine environment or searching for and installing the Wine runner in the Deepin/UOS app store.
   - Regarding this project: Why are there no more simplified versions available in more languages?
     1. ue to the limited energy of warehouse managers, they can currently only manually create simplified versions in English and Simplified Chinese. If you wish to create more language related simplified versions yourself, you can refer to [this article](./[Windows][ResourceHacker]%20embedding%20mui%20into%20a%20exe%20so%20it%20will%20be%20able%20to%20run%20without%20external%20files,%20and%20even%20if%20the%20Windows%20language%20is%20currently%20different%20than%20the%20one%20you%20are%20embedding%20(reupload).md) (which is a backup of our website, and the original author is [MarcellaVT](https://gist.github.com/MarcellaVT/52f21102a29292d96e20a3033285098b) ), generally, the simplified version made according to this tutorial can support running in the Wine environment!
   - About this project: where can I find "more games" and "Internet game ontology"?
     1. n the "More_Internet_Games" folder of this project, you can find the dll files of "Internet Games" and "More Games" in the simplified language. Please note that we have not made compatible changes to the Wine environment for "Internet Games", and these "Internet Games" servers have also been shut down. If you have special needs, please download them yourself.
   - Regarding this project: This project version is already quite old or I would like to download an updated version of Win7GamesForWindows original version that has not been streamlined. What should I do?
     1. You can visit [this website](https://win7games.com/) to download the original Win7 Games for Windows version, which is the adaptation of the original Windows 7 games to the latest Windows. In general, you can still use the article mentioned earlier to streamline it and adapt it to the Wine environment!
   - Regarding fonts: What specific information do these Simplified Chinese fonts correspond to?
     1. simsun.ttc:SimSun is a very basic Simplified Chinese font in the Windows operating system, widely used for document editing and web page display.
     2. simhei.ttf:SimHei, with its concise and clear lines, is highly favored by users and is suitable for displaying titles or text that requires clarity and modernity.
     3. simfang.ttf： SimFang, commonly used for formal document and book layout, gives people a classical and elegant feeling.
     4. simkai.ttf： SimKai, with a natural and smooth handwriting, is suitable for literary works, notices, letters, etc., and can add artistic and readability to texts.
2. Special thanks:
   - Retained publisher of Win7Games Simplified Tutorial: [MarcellaVT](https://gist.github.com/MarcellaVT/52f21102a29292d96e20a3033285098b)
   - Win7GamesForWindows publisher: [Win7Games](https://win7games.com/)
   - ResourceHacker tool author: [angusj](https://www.angusj.com/resourcehacker/)
   - The inspiration for this project comes from: [The warehouse manager who was idle and suddenly wanted to run a Win7 game on Linux but failed found this article](https://forum.winehq.org/viewtopic.php?t=37417 )
   - Github platform support: [Github](https://github.com/)

Last update：2025.1.23 | [View Protocol](../LICENSE)
--------