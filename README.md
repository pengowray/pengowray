### Pengo Wray

I'm a developer with experience mainly in C#, Rust, and JavaScript. My interests include endangered species conservation. I started Beastie Bot to help keep threatened species articles on Wikipedia up to date with public data from the [IUCN](https://en.wikipedia.org/wiki/International_Union_for_Conservation_of_Nature).

Contributions to open source projects include discovering and helping patch a security vulnerability in a tool from the Internet Archive (CVE-2025-58438); I also identified and helped patch a bug in the Microsoft's dotnet runtime (timespan parsing). I've followed machine learning developments for a long time with code contributions to [gensim](https://en.wikipedia.org/wiki/Gensim) and other machine learning projects which predate the release of ChatGPT.

Most personal projects listed here are simply scratching an itch, such as [an online tool which can tell you how long an ebook file is](https://pengowray.github.io/word-count-epub/) (without upload it or downloading an app); an [online generator of sine sweeps](https://pengowray.github.io/sweep/) for messing around with impulse response recordings; and a tool used to switch off the PC screen when I turn off the light ([ScreenSleeper](https://github.com/pengowray/ScreenSleeper)).

Several of my projects are experiments in _information design_, searching for ways to present complex information in a way it can be understood efficiently, effectively and simply. Examples include: [FT8 Player](https://pengowray.github.io/ft8play/) which visualizes amateur radio data packets; [wasm-ops](https://pengowray.github.io/wasm-ops/) which lays out the set of operations (op codes) available to high-performance web applications through [WebAssessmbly](https://en.wikipedia.org/wiki/WebAssembly); Qubero hex editor, an early project of mine which aimed to open up complex binary files with a spreadsheet-like interface. Also the aforementioned Beastie Bot, although it outputs text styled for wikis and not visualizations, is also an information design project with the same prinicples. It aims to present the rich data relating to the risk of exinction of plant and animal species in a way which is effective, accurate and easily understood.

I run a Discord bot (Sprinto) which helps authors and writing groups stay focused on their craft.

General projects:
- [Sprinto](https://sprintobot.com) | [github](https://github.com/pengowray/sprinto) — Discord bot for writers/authors/nanowrimo, to run writing sprints, to help you focus on your work. Now found on 50,000 Discord servers [currently closed source] (C#)
- [TimeSpanParser](https://github.com/pengowray/TimeSpanParser) — Parser for any human input of a time span such as "5 mins" (C# library)
- [Streamling Overlay app](https://pengowray.itch.io/streamling) [itch.io] Find what music is playing on Spotify, VLC, Winamp, etc and display it (e.g. in OBS) via a built-in webserver, for streamers. (C# and JavaScript; closed source for now)
- [wasm-ops](https://pengowray.github.io/wasm-ops/) — Online Chart of WebAssembly Instructions (web page, JavaScript)
- [Online Sine Sweep Generator](https://pengowray.github.io/sweep/) — Online tool to generate high-fidelity test signals focused on capturing impulse responses. (JavaScript)
- [Online Word Counter for .epub ebooks](https://pengowray.github.io/word-count-epub/) — How long is that book? (for EPUB files)
- [beastie bot 3](https://github.com/pengowray/beastiebot3) — Generate lists of threatened species, formatted for Wikipedia. Plus related data wrangling tools (C#)
- [CommentedList](https://github.com/pengowray/CommentedList) — Format for managing lists of text for use in random selection such as quote-of-the-day. Allows for comments with hashtags and key-value pairs. (C# library)
- [ScreenSleeper](https://github.com/pengowray/ScreenSleeper) — MQTT listener for Windows to turn on/off the screen for home automation (C#)
- [a2max](https://github.com/pengowray/a2max) — Integer Basic boot loader with maximum compatibility for the Apple II series and emulators
- [send em tiny](https://github.com/pengowray/sendemtiny) Windows utility to send Unicode characters, configured by renaming an .exe file, to improve functionality of old mouse/keyboard utilities (C#) 
- [youtube-speed-tweak](https://github.com/pengowray/youtube-speed-tweak) — A Firefox extension to increase youtube playback speed beyond 2x
- "[Worst Wordle](https://github.com/pengowray/WorstWordle)" — Script to find the most ambiguous ("worst") four-letter combos in Wordle, namely "__IGHT" (C#)
- [HomeConfig](https://github.com/pengowray/homeconfig) — Library to quickly find and read a config file (C#)
- [qubero](https://github.com/pengowray/qubero) — Hex Editor project with support for inserting or deleting single bits (Java)
- [snakey](https://pengowray.github.io/snakey/js-dos/) — Snakey: DOS era game written in C (playable in browser)
- Other/private/undocumented projects: PebblyPop, LorenzLorentz, UnicodeWatch, LiteraryWatch, mpegdemo/h264demo, ...

Amateur radio specific projects:
- [Online FT8 Player](https://pengowray.github.io/ft8play/) — Online visualizer and player for FT8, which is a mode for sending short messages popular with amateur radio enthusiasts. (JavaScript/WASM)
- [upSidetone](https://github.com/pengowray/upsidetone) — Low latency morse code keyer app for Windows (C#)
- [Online Random Wire Calculator](https://pengowray.github.io/random-wire-calc/) — Online long-wire length calculator and plot for amateur radio enthusiasts. (JavaScript)
- [VaraHuffmanNet](https://github.com/pengowray/VaraHuffmanNet) — Reimplement and document the compressed VARA protocol format associated with Winlink for amateur radio (C# rewrite of VB6 code)

Projects with code contributions:
- [dotnet runtime](https://github.com/dotnet/runtime) — discovered bug and contributed fix for TimeSpan.Parse(string) in dotnet system library ([pull request](https://github.com/dotnet/coreclr/pull/21077) Note my previous github username was Quole)
- [ia: official command-line interface tool for the Internet Archive (archive.org)](https://github.com/jjjake/internetarchive) — discovered path traversal vulnerability (CVE-2025-58438)[https://github.com/advisories/GHSA-wx3r-v6h7-frjp]; contributed code for patch
- [word2vec-api](https://github.com/pengowray/word2vec-api) (Python) Simple web service providing a word embedding model (contributions: updated from python 2 → 3; added a new setting)
- [LiveSplit](https://github.com/LiveSplit/LiveSplit) — minor contributions to simplify time formatting. [PR](https://github.com/LiveSplit/LiveSplit/pull/1457) (C#)
- [TimTheWordWarBot](https://github.com/pengowray/TimTheWordWarBot) — Contributed minor fix (Java)
- [standingwave3](https://github.com/pengowray/standingwave3) — AS3 (ActionScript3) audio library; contribution: bug fixes
- [Gensim](https://github.com/RaRe-Technologies/gensim) — Python library for natural language processing (NLP); contribution: better word2vec file support [PR](https://github.com/RaRe-Technologies/gensim/pull/1318)

<!--
- 🔭 I’m currently working on some things and also Sprinto.
- 💬 Ask me about threatened species
- 🤔 I’m looking for help with ...
- 📫 How to reach me: ...
- ⚡ Fun fact: ...
-->

<a rel="me" href="https://mastodon.gamedev.place/@pengowray">Mastodon</a>
