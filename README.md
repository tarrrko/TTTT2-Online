# TTTT2 Online

**An unofficial, free fan project that lets you play your own copy of Tekken Tag Tournament 2 (Xbox 360) on a Windows PC, with
rollback online play.**

> [!IMPORTANT]
> **You need your own legal copy of the game.** This project contains no game files, and it never downloads any. The app
> builds the game on your PC from a disc image you made from a disc you own. If you do not own the game, this project is not
> for you.
>
> **This project does not provide or link to game files, and it will not help you find them.** Requests for them will be
> closed. Using any copy that you did not obtain legally is not allowed, and the authors accept no responsibility for it.
>
> This is not an official product. It is not made, approved or supported by Bandai Namco Entertainment or Microsoft.

## What you get

### An app that gets out of your way

- A clean, modern app with everything one click away: **Ranked, Casual, Lobby, Practice, Controls and Settings**.
- The whole app works with a controller. It shows the right button icons for Xbox, PlayStation and Switch controllers.
- Several accounts on one PC, each with its own team, side, controls and match history.
- Your team stands under its cards in the costumes you picked, and your fighter can be your account photo.
- Updates are automatic: a gold button appears when a new version is out, and one press installs it. Every update is signed.

### Online play

- **GGPO rollback netcode**, with an automatic input delay of 1 to 2 frames.
- **Ranked:** search for a player near your rank. Every fighter has its own rank, from Beginner to True Tekken God.
- **Casual:** search for anyone, with no effect on your ranks.
- **Lobby:** play a friend with a 6-letter code. No IP addresses to type or share.
- **Rematch without leaving the game:** the next fight is ready in about 10 seconds.
- A live display of ping, input delay and rollbacks, which also shows whose PC is struggling.
- Your win streak against an opponent, shown in the game's own WINS display.

### Play on the side you want

- **Pick left or right, online and in practice.**
- If both players want the same side, both get it. One player sees the fight from the far side of the stage, so each player sees
  their own fighter on the side they chose. Life bars, sound and sidesteps all follow, and the fight stays identical on both PCs.

### Improvements

- **Quicker buttons:** the game's own 2-frame input delay is removed, online, in practice and offline.
- **Higher resolution:** Standard, High and Ultra picture settings, up to 3 times the original resolution, for sharp pictures up
  to 4K.
- **No title update needed:** the game runs from the base disc alone.
- **The ten extra fighters are ready to play:** Miharu, Sebastian, Slim Bob, Ancient Ogre, Angel, Kunimitsu, Michelle, Violet,
  Dr. Bosconovitch and Unknown are already on the disc. The game used to unlock them over Xbox Live. The app does that step
  itself, with no game data and no download.
- **Practice starts straight in the game**, with an input history and your choice of side.
- **Full control:** remap any controller, or use the keyboard with its presets.

## What you need

| | |
|---|---|
| **Game** | Your own Tekken Tag Tournament 2 for Xbox 360, USA / Europe release (title 4E4D0859), as a disc image (.iso) made from your disc |
| **System** | Windows 10 or 11 (64-bit), a DirectX 12 graphics card, a CPU with SSE4.1, about 20 GB free |
| **Online** | Both players on the same version. UDP port 7000 must be reachable: the app asks your router to open it, and if that fails you need to forward it yourself |

The builder only accepts the unmodified retail version of the game. It cannot tell how a copy was obtained: that is your
responsibility.

## How to install

1. Download `TTTT2Online-v<number>.zip` from [Releases](../../releases) and unzip it to a normal folder, not inside Program Files.
2. Start `TTTT2 Online.exe`.
3. Open **Settings - Build Game - Build From My Copy** and pick your disc image. This takes a few minutes and is done once.
4. Pick your team and play.

## Known limits

- There is no leaderboard yet.
- Ranks are stored on each player's own PC, so treat them as a guide.
- Matchmaking uses free public relay services, so it can go down without warning.
- Matches connect directly between two PCs. Some internet providers and routers do not allow that, so some pairs of players cannot
  connect.
- A rare crash can still happen at about 100 ms ping.
- Lobbies are for two players for now. Saved custom costumes and Customize mode are not available.

## Privacy

**Who is responsible:** the maintainer of this project. Contact: tttt2online@proton.me

This project has no server and no accounts on the internet, and nothing is sent to this project. Your accounts, ranks, settings and
match history stay on your PC.

| What | Who gets it | Why |
|---|---|---|
| Your IP address and port | The opponent you are matched with | The two PCs connect directly to play |
| Your IP address | The relay services `broker.emqx.io` and `broker.hivemq.com` | The apps meet there. What they send there is encrypted |
| Your IP address | `api.ipify.org` | It tells the app your public address |
| Your IP address | GitHub | The app checks for updates there |
| Your player name, photo, rank and team | The players you meet | They are shown in the match |
| The match's log, with addresses removed | Your opponent, only when you both turn on Share Logs | Finding a problem together |

**Legal basis:** providing the online play you asked for, and our legitimate interest in keeping it working (GDPR Article 6(1)(b) and (f)).

**How long:** the app keeps the logs of your last 15 games on your PC, and deletes logs received from an opponent after 14 days. The
relay services, `api.ipify.org` and GitHub have their own policies, and some of them are outside your country.

**Your rights:** you can ask about, correct or delete data we hold, object, and complain to your data protection authority. We hold
nothing about you ourselves. You can delete everything on your PC by deleting the app's folder. You can play Practice offline.

## Legal

**Your responsibility.** You may use this software only with a copy of the game that you obtained legally, and only where that is
allowed in your country. Laws on backups, circumvention of copy protection and modding differ between countries, so check yours
first.

**No game content.** This project does not contain or distribute the game's code, data, art, sound or music. These come only from
your own copy and stay on your PC. The one item made from the game is a small file of fighter outlines, which holds no picture of its
own and is only used to cut out the pictures from your copy. **Do not share or upload a built game** (the `native` folder), or anything
made from it.

**No warranty.** This software is provided "as is", without warranty of any kind. The authors are not liable for any claim, damage
or loss arising from its use, including use with an unlawfully obtained copy of the game.

**Not for sale.** This project is free. It must not be sold or bundled with any game files.

**Open-source parts.** The open-source parts of the download stay under their own licenses, listed in the `licenses` folder. Nothing on
this page limits your rights under those licenses.

**Trademarks.** TEKKEN, TEKKEN TAG TOURNAMENT and all related names are trademarks of Bandai Namco Entertainment Inc. Xbox and Xbox
360 are trademarks of Microsoft Corporation. They are used here only to say which game this software works with. This project is
not affiliated with or endorsed by any of them.

**Rights holders.** This is a non-commercial fan project made out of love for the game. If you represent a rights holder and have a
concern, please write to tttt2online@proton.me. We will review it and respond promptly.

## Credits

- **[Tekken 6 Native Online](https://github.com/Ekspym/Tekken6-native-online) by Ekspym:** the app's design and online flow are
  modelled on it, and part of this project's runtime comes from its work.
- **[tekken6-recomp](https://github.com/mahmoud-mess/tekken6-recomp) by mahmoud-mess:** the ReXGlue changes that Tekken 6 Native
  Online was built on.
- **[ReXGlue SDK](https://github.com/rexglue/rexglue-sdk) by Tom Clay**, based on the
  [Xenia](https://xenia.jp) project by Ben Vanik and contributors.
- **[GGPO](https://github.com/pond3r/ggpo)** rollback networking by Tony Cannon and contributors.
- SDL3, FFmpeg, libmspack, GNU binutils' PowerPC disassembler, LLVM / llvm-mingw, Python and the other open-source parts, listed in
  the `licenses` folder of the download. Each stays under its own license.

## Source code

The app's own code is not open source. The source of the GPL and LGPL parts is attached to every release, next to the download, with
the build scripts and tool versions:

- `rexglue.exe`, the code translator, under the GPL: the [ReXGlue SDK](https://github.com/rexglue/rexglue-sdk) with this project's
  patch, including the GNU binutils disassembler
- FFmpeg and libmspack, under the LGPL, which are separate DLLs you can replace
