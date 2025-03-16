# :page_with_curl: Table of Contents
- [WARNING](#light_starryFox)
- [Change](#change)
- [Installation](#install)
- [Using](#using)

---

![Example]()

---

##  <a id="light_starryFox">:star2: Light StarryFox</a>
<p>
<h4>:bangbang: The image of the logo and the name "Firefox" and background <em>(also their connection)</em>, as well as the idea, was taken <a href="https://github.com/sagars007/starry-fox" target="_blank">detail</a></h4>
</p>

---

## <a id="change">:dna: Change :</a>
- Changed **background**:desktop_computer:, **logo**:fox_face:, **name Firefox**:page_facing_up: on the home screen *(images and their location)*
- Bookmarks slightly larger and more space between bookmarks
- Removed buttons **'Sidebar'** and **'List of all tabs'**
- Changed tab close button :x: and new tab creation button :heavy_plus_sign:

---

## <a id="install">:inbox_tray: Installation :</a>
**1.** :anger: Type **"about:config"** in the search bar, insert **"toolkit.legacyUserProfileCustomizations.stylesheets"** there, and set the value to **"True"** *(this is needed for the browser to apply CSS themes)* <br/>

**2.** :envelope_with_arrow: Download the **"chrome"** folder from this repository and move it to the browser profile folder *(type **"about:support"** in the search bar, then click **"Open Folder"** next to **"Profile Folder"**)* <br/>

**3.** :electric_plug: Restart Firefox browser

---

## <a id="using">:point_up_2: Using :</a>
- Best use this topic with extension [Adaptive Tab Bar Colour](https://github.com/easonwong-de/Adaptive-Tab-Bar-Colour) :sparkles:
- You need to replace :scissors: the wallpaper in the:
  1. Go to **'chrome'** :file_folder: *(see installation)*
  2. Move your image/gif to the **'image'** :file_folder:
  3. Open **'userContent.css'** file :file_cabinet: in any text editor *(even a notepad will work)*
  4. Find this item and replace :scissors: **'Animation_Of_Stars-25-fps-compress.gif'** with the name of your image/gif

  ```
  body {
		background: url("images/Animation_Of_Stars-25-fps-compress.gif") no-repeat fixed !important;
		background-size: cover !important;
	}
  ```
