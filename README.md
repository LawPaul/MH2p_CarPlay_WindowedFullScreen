# PCM5 CarPlay Windowed Full Screen
Changes CarPlay to windowed fullscreen (still shows left and top menu bars).
## License
 - This file is part of PCM5_CarPlay_WindowedFullscreen, licensed under CC BY-NC-SA 4.0.
 - https://creativecommons.org/licenses/by-nc-sa/4.0/
 - See the LICENSE file in the project root for full license text.
 - NOT FOR COMMERCIAL USE
## Compatible vehicles
Please let me know of additional vehicles to add to this list.
 - 19-23 Porsche Macan
## Installation
 - for use with [MH2p SD ModKit](https://github.com/LawPaul/MH2p_SD_ModKit)
## How it works
 - `fc.jar` is copied to MH2p at `/mnt/app/eso/hmi/lsd/jars`
 - jars in that directory are loaded onto the classpath before `lsd.jar` which runs the PCM5 UI
 - classes in `fc.jar` are prioritized over those in `lsd.jar` and can modify functionality
## Credits
 - UncleMacan ([Macan Forum](https://www.macanforum.com/members/unclemacan.173728/)): worked together on Porsche CarPlay true fullscreen; wanting an easier installation method got me started making SD ModKit
 - lprot ([GitHub](https://github.com/lprot), [DRIVE2](https://www.drive2.ru/users/lprot/)): general platform knowledge, MH2p Toolkit
 - [Recaf](https://github.com/Col-E/Recaf): reverse engineering & modifying for CarPlay true fullscreen
 - "experts" selling their "services": motivation to make CarPlay true fullscreen available to all for free
 ## Contact
 - [GitHub](https://github.com/LawPaul)
 - [Macan Forum](https://www.macanforum.com/members/carmines.174281/)
 - [DRIVE2](https://www.drive2.ru/users/lawsen/)
 - [Discord](https://discordapp.com/users/lawsen5734)