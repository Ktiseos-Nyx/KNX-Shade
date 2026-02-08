# ✨ Ktiseos Nyx [Reshade](https://reshade.me/) Presets for FFXIV ✨
Welcome to the preset collection for Reshade by **KtiseosNyx**! We're passionate about enhancing the visual experience of Final Fantasy XIV and are excited to share our creations with you.

While we're always learning and perfecting our craft, these presets represent our current best efforts to bring new atmospheres and moods to your Eorzean adventures.

<p align="center">
  <a href="https://xivmodarchive.com/user/539571"><img src="https://img.shields.io/badge/FFXIV%20Compatible-Dawntrail ✔️-blueviolet" alt="Works for Dawntrail"></a>
  <a href="https://ko-fi.com/Z8Z8L4EO"><img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Support us on Ko-fi"></a>
</p>

---

## 🌟 Features
*   A diverse collection of presets to suit various moods and environments.
*   Continuously updated and refined.
*   Designed with Final Fantasy XIV in mind, with confirmed compatibility for Dawntrail!
*   Blood, sweat and Miqo Tears as my GPU screeches at me like an Eagle.

---

## 🛠️ Getting Started: Installing ReShade
Before you can use our presets, you need to have ReShade installed and configured for Final Fantasy XIV.

1.  **Download ReShade:**
    *   Head to the official ReShade website: [reshade.me](https://reshade.me/)
    *   Download the latest version of the ReShade installer.

2.  **Run the ReShade Installer:**
    *   Execute the downloaded `ReShade_Setup_x.x.x.exe` file (the `x.x.x` will be the version number).
    *   A window will appear listing games or prompting you to browse. Click the large button that says **"Click here to select a game and manage its ReShade installation"**.
    *   Navigate to your Final Fantasy XIV game folder and select `ffxiv_dx11.exe`.
        *   *Common path: `C:\Program Files (x86)\SquareEnix\FINAL FANTASY XIV - A Realm Reborn\game\ffxiv_dx11.exe`*
    *   Click "Next".

3.  **Select Rendering API:**
    *   Choose **"Microsoft DirectX 10/11/12"** when prompted for the rendering API.
    *   Click "Next".

4.  **Shader Package Selection (Crucial Step!):**
    *   You'll be asked to select shader packages to install. Our presets utilize shaders from various common repositories.
    *   **Recommended:** For maximum compatibility and to ensure all our presets work out-of-the-box, **select all available shader packages**. This includes "Standard effects," "SweetFX by CeeJay.dk," "qUINT by Marty McFly," AstrayFX, OtisFX, and others that appear in the list.
    *   If you prefer a more minimal installation, ensure at least the following are checked (though you may encounter missing shaders with some presets):
        *   Standard effects
        *   SweetFX by CeeJay.dk
        *   qUINT by Marty McFly
    *   ReShade will then download the selected `.fx` shader files and `.fxh` header files.
    *   For a comprehensive list of known shader repositories that ReShade can pull from, see [this PCGamingWiki page](https://www.pcgamingwiki.com/wiki/ReShade#List_of_known_shader_repositories). You can re-run the ReShade installer later to add more shader packages if needed.
    *   Click "Next" and then "Finish" once the downloads are complete.

5.  **Verify Installation:**
    *   Launch Final Fantasy XIV. You should see a ReShade overlay message at the top of your screen for a few seconds, indicating it has loaded successfully.
    *   You can open the ReShade menu in-game by pressing the `Home` key (this can be changed in ReShade settings).

---

## 💾 Installing Duskfallcrew's Presets
Once ReShade is set up:

1.  **Download Our Presets:**
    *   Click the green "Code" button on this GitHub repository page.
    *   Select "Download ZIP".
    *   Extract the downloaded ZIP file to a convenient location on your computer.

2.  **Place Preset Files:**
    *   Inside the extracted folder, you'll find our `.ini` preset files.
    *   Copy the `.ini` files you wish to use.
    *   Paste them into your FFXIV game directory (the same folder where `ffxiv_dx11.exe` is located).
        *   *Alternatively, you can create a subfolder like `reshade-presets` inside the game directory and place them there. ReShade allows you to navigate to different folders to find presets.*

3.  **Shader Files & Textures:**
    *   Our presets reference various shader files (`.fx`) that should have been downloaded during the ReShade shader package selection step. If a preset isn't working correctly, you might be missing a specific shader package. You can re-run the ReShade installer for `ffxiv_dx11.exe` and select additional shader packages to install.
    *   **Important Note on Shaders:** To the best of our knowledge, all shaders utilized by these presets are freely available from the standard ReShade repositories or their respective authors and **do not include any paid shaders.**
    *   Some presets may also utilize textures (e.g., for effects like LUTs or special overlays, often from shader packs like Pirate Shaders). Where necessary, these textures are either included directly in this repository (check the folders within the downloaded ZIP!) or specific instructions will be provided with the preset. Ensure texture paths in ReShade settings are correctly configured if needed (ReShade usually looks for a `reshade-shaders\Textures` folder within your game directory).

---

## 🎮 How to Use Presets In-Game
1.  Launch Final Fantasy XIV.
2.  Once in-game, open the ReShade menu (usually by pressing the `Home` key).
3.  At the top of the ReShade menu, you'll see a dropdown bar. Click it.
4.  Navigate to and select the desired `.ini` preset file from the list. The effects should apply immediately.
5.  Experiment and enjoy your newly beautified Eorzea!

> **A Note on the "OFF" Preset:** One preset is labeled "OFF". This was an experimental addition, potentially borrowed from elsewhere, and may not render correctly for everyone. It's intended as a quick way to disable effects but use with caution or consider simply unchecking active shaders in the ReShade menu.

---

## 🖼️ Preset Showcase

Here are some examples of what you can expect! Click on an image to see a larger view or get more details (you'll need to set up these links).

*Replace `URL_TO_YOUR_PREVIEW_IMAGE.png` with the actual path to your image and `LINK_TO_FULL_IMAGE_OR_DETAILS` with the desired link destination. Adjust `width` as needed.*

<table>
  <tr>
    <td align="center" width="33%">
      <a href="https://github.com/user-attachments/assets/b3ac6e4a-6e80-4ca3-b381-2edbc61d6de5">
        <img src="https://github.com/user-attachments/assets/b3ac6e4a-6e80-4ca3-b381-2edbc61d6de5" alt="In Living a Lie" width="250px" />
      </a>
      <br />
      <em>In Living a Lie Preset Pack</em>
      <br />
      🎨🌟✨
    </td>
    <td align="center" width="33%">
      <a href="https://github.com/user-attachments/assets/4589c2fc-c8a3-4d9d-a8e6-0ffe5d3f727c">
        <img src="https://github.com/user-attachments/assets/4589c2fc-c8a3-4d9d-a8e6-0ffe5d3f727c" alt="Memories Full Set" width="250px" />
      </a>
      <br />
      <em>Memories Full Set</em>
      <br />
      📸💭💖
    </td>
    <td align="center" width="33%">
      <a href="https://github.com/user-attachments/assets/cd646661-245d-4c8e-8ebe-c25eb1ad8e3b">
        <img src="https://github.com/user-attachments/assets/cd646661-245d-4c8e-8ebe-c25eb1ad8e3b" alt="Ultima Thule Inspired" width="250px" />
      </a>
      <br />
      <em>Ultima Thule Inspired</em>
      <br />
      🌌🌠🔮
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="https://github.com/user-attachments/assets/f450bcaa-5a2f-42c5-9289-632d2739f155">
        <img src="https://github.com/user-attachments/assets/f450bcaa-5a2f-42c5-9289-632d2739f155" alt="Graphic Contrast" width="250px" />
      </a>
      <br />
      <em>Graphic Contrast</em>
      <br />
      💥🎞️👁️
    </td>
    <td align="center" width="33%">
      <a href="https://github.com/user-attachments/assets/42a8468c-ba59-4554-b47e-fefc631f7674">
        <img src="https://github.com/user-attachments/assets/42a8468c-ba59-4554-b47e-fefc631f7674" alt="Wedding Thule" width="250px" />
      </a>
      <br />
      <em>Wedding Thule</em>
      <br />
      💍💒💫
    </td>
    <td align="center" width="33%">
      <a href="https://github.com/user-attachments/assets/01ecda67-0a6a-4c2c-b322-77c4d1d119f3">
        <img src="https://github.com/user-attachments/assets/01ecda67-0a6a-4c2c-b322-77c4d1d119f3" alt="Pepperoni Presets" width="250px" />
      </a>
      <br />
      <em>Pepperoni Presets</em>
      <br />
      🍕🌶️🔥
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <a href="https://github.com/user-attachments/assets/52824087-e362-4e76-a978-1a902fb39fb3">
        <img src="https://github.com/user-attachments/assets/52824087-e362-4e76-a978-1a902fb39fb3" alt="Seneschal" width="250px" />
      </a>
      <br />
      <em>Seneschal</em>
      <br />
      👑📜⚔️
    </td>
    <td align="center" width="33%">
      <a href="https://github.com/user-attachments/assets/af2a0889-bde8-43d7-97e9-ab22e9709981">
        <img src="https://github.com/user-attachments/assets/af2a0889-bde8-43d7-97e9-ab22e9709981" alt="Mogtome Season" width="250px" />
      </a>
      <br />
      <em>Mogtome Season</em>
      <br />
      📚⏰🌙
    </td>
    <td align="center" width="33%">
      <!-- Add your next preset here -->
      <a href="LINK_TO_FULL_IMAGE_OR_DETAILS">
        <img src="URL_TO_YOUR_PREVIEW_IMAGE.png" alt="New Preset Name" width="250px" />
      </a>
      <br />
      <em>New Preset Name</em>
      <br />
      💡✨🆕
    </td>
  </tr>
  <!-- Add more <tr> sections for more rows of images -->
</table>

---

## 📜 License & Permissions
We want you to enjoy and build upon our work!

**🚫 You MAY NOT:**
*   Sell these presets or any derivatives for monetary gain. (We'd be very sad!)
*   Use these presets for any toxic, harmful, illegal, or regulation-violating purposes.

**✅ You CAN:**
*   Remix, adapt, and improve upon these presets.
*   Rename your modified versions.
*   Share your creations (please credit the original work if you do!).

---

## 🧑‍🤝‍🧑 Credits & Thanks
These presets wouldn't be possible without the incredible work of the shader development community. Our deepest thanks to the authors of the shaders we've utilized:

*   [MartymcModding/Pascal Glicher](https://github.com/martymcmodding) 
*   [OtisFX](https://github.com/FransBouma/OtisFX) 
*   [FGFX](https://github.com/AlexTuduran/FGFX)
*   [Radegast](https://github.com/Radegast-FFXIV/Warp-FX)
*   [Pirate Shaders](https://github.com/Heathen/Pirate-Shaders) 
*   [RSRetroArch (RetroArch shaders adapted for ReShade)](https://github.com/Matsilagi/RSRetroArch/)
*   [PD80  ](https://github.com/prod80/prod80-ReShade-Repository)
*   [Luluco250](https://github.com/luluco250/FXShaders)
*   [Fubax](https://github.com/Fubaxiusz/fubax-shaders)
*   [AstrayFX](https://github.com/BlueSkyDefender/AstrayFX)
*   [CobraFX](https://github.com/LordKobra/CobraFX)
*   [CorgiFX](https://github.com/originalnicodr/CorgiFX)
*   [Daodan](https://github.com/Daodan317081/reshade-shaders)
*   [Akgunter](https://github.com/akgunter)
*   [Brussell](https://github.com/brussell1/Shaders)

...and any others we may have inadvertently missed! (If you see a shader you wrote and aren't credited, please let us know!)

*We aim to provide direct links to shader repositories or author pages in the future for easier discovery.*

---

## 📢 Updates & News

### October 2024 Update:
Texture backgrounds can be used for ANY of the depth slice setups. While certain ones are formatted specifically, most are designed for a 1920x1080 resolution, which remains a fairly standard sizing. Ensure textures are placed in the `reshade-shaders\Textures` folder within your FFXIV game directory for ReShade to find them.

### 2025 Update:
This repository has been moved to our coding arm, **Ktiseos Nyx**, for better organization and clarity. Future presets from Azem, K'rhis (Dusk/Earth), or other members may also be consolidated here and on our respective modding platform accounts. More presets have been added!

---

## ❤️ Support Us & Connect

If you enjoy our presets and want to support our work, consider buying us a coffee! It helps us dedicate more time to creating and refining these visual enhancements.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z8L4EO)

You can also find us on various platforms:

| Platform       | Link                                                                             |
| -------------- | -------------------------------------------------------------------------------- |
| Discord        | [Duskfallcrew Community](https://discord.gg/5t2kYxt7An)                         |
| Resources      | [Capsekai Resources](https://capsekai.carrd.co/)                                 |
| YouTube        | [Duskfallcrew Channel](https://www.youtube.com/channel/UCk7MGP7nrJz5awBSP75xmVw) |
| TikTok         | [@duskfallcrew](https://www.tiktok.com/@duskfallcrew)                           |
| Twitch         | [duskfallcrew](https://twitch.tv/duskfallcrew)                                  |
| Ko-Fi          | [Duskfallcrew](https://ko-fi.com/duskfallcrew/)                                  |
| BlueSky        | [@duskfallcrew.bsky.social](https://bsky.app/profile/duskfallcrew.bsky.social)   |

---

*We appreciate your interest and hope these presets bring a new dimension to your game! If you have any issues or feedback, feel free to open an issue on this repository or reach out to us on Discord.*
