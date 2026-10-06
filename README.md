<p align="center">
    <img src="https://raw.githubusercontent.com/s4n-sunix/ghoul-windows-rice/refs/heads/main/Assets/Icon.jpg" width="80" />
    <h2 align="center"> deadinside✓emo✓drain✓epileptic✓paranoid✓toxic✓bipolar✓depressed✓tilted✓antisocial✓sad✓broken✓aggressive✓psycho✓apathetic✓broken-hearted✓</h2>
</p>

**DISCLAIMER:** Some files i took from other authors or changed them or made by myself.
I do not claim ownership of any copyrights

## Dependencies 📦

| Component         | Program    |
|-------------------|------------|
| Terminal 🖥️       | [Powershell 7+](https://apps.microsoft.com/detail/9mz1snwt0n5d)        |
| Shell 🐚          | [Oh-My-Posh](https://ohmyposh.dev/) / [Theme](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/wholespace.omp.json) |
| Fetch 🖼️          | [Fastfetch](https://github.com/fastfetch-cli/fastfetch) / [Logo](https://github.com/s4n-sunix/ghoul-windows-rice/blob/main/output.six) |
| File Manager 📁   | **DEFAULT**      |
| Editor 📝         | [Zed](https://zed.dev/) / Theme - Monochromator Dark Ruby     |
| Browser 🌐        | [Zen](https://zen-browser.app/) |
| Bar 📊            | [YASB](https://yasb.dev/)      |
| Customization 🎨  | [Windhawk](https://windhawk.net/)      |
| Music Player 🎵   | [Spotify](https://open.spotify.com/) / [Theme](https://github.com/Astromations/Hazy)      |
| Visualiser 📊     | [Cava](https://github.com/karlstav/cava)          |
| Context Menu 🔎   | [Nilesoft Shell](https://nilesoft.org/)          |
| Launcher 🚀 | [Flow Launcher](https://www.flowlauncher.com/)|
| Image converter 🖼️ | [ImageMagick](https://imagemagick.org)|
| Font 💬 | [JetBrainsMono](https://www.jetbrains.com/lp/mono/)|

<p align="center">
    <h2 align="center"> 🤍❤️ Preview </h2>
</p>

![1](https://github.com/s4n-sunix/ghoul-windows-rice/blob/main/Preview1.png)
![2](https://github.com/s4n-sunix/ghoul-windows-rice/blob/main/Preview2.png)
![3](https://github.com/s4n-sunix/ghoul-windows-rice/blob/main/Preview3.png)

## Manual Installation 📚

## Credits 📝
Most of "dotfiles" was taken from this guy --> [MrDLingters](https://github.com/MrDLingters)

### 1. Clone Repository (or download zip and unzip it)
```bash
git clone https://github.com/s4n-sunix/ghoul-windows-rice.git
```

### 2. Install all dependencies

### 3. Windhawk Setup
- **Taskabr Styler** | Theme: TranslucentTaskbar
- **Start Menu styler** | Theme: LiquidGlass (Legacy)
- **Notification Center Styler** | Theme: TranslucentShell
- **File Explorer Styler** | Theme: Translucent Explorer11 / Effect: Blur / Region: Entire window
- **Translucent Windows** | Effect: Blur
- **Taskbar tray system icon tweaks** | Hide microphone icon
- **Resource Redirect** | Icon theme: Papirus Red

### 4. Terminal Setup
-- To install theme for oh-my-posh

Open powershell.

```shell
New-Item -Path $PROFILE -Type File -Force
notepad $PROFILE
```

In notepad paste this line, save and reload powershell:

```
oh-my-posh init pwsh --config "path/to/theme" | Invoke-Expression
```
-- For fastfetch put *config.jsonc* in *users/"USERNAME"/.config/fasfetch.* **if folders don't exist, create them.**
In *config.jsonc* replace this line:
```json
"source": "E:\\GithubRepositories\\output.six"
```
with your path to logo.

### 5. Zen Browser configuration
1. Go to Settings
2. Mods for Zen
3. Import mods
4. Select my **"zen-mods-export.json"**

### 6. YASB configuration
1. Press RMB on YASB Icon in tray
2. "Open Config"
3. Move the contents of the folder *"YASB"* from repo into the folder that just opened. Replace if will need.

### 7. Spotify configuration
1. Install spicetify (with marketplace)
```shell
iwr -useb https://raw.githubusercontent.com/spicetify/cli/main/install.ps1 | iex
```
2. In marketplace press setting button
3. "Backup and Restore" --> Open
4. Import --> select settings.json from Spicetify folder
