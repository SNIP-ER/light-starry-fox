# :star2: Light StarryFox 
<p>
<h4>:bangbang: The image of the logo and the name "Firefox" and background <em>(also their connection)</em>, as well as the idea, was taken <a href="https://github.com/sagars007/starry-fox" target="_blank">detail</a></h4>
</p>

---

# :dna: Change : 
- Changed **background**:desktop_computer:, **logo**:fox_face:, **name Firefox**:page_facing_up: on the home screen *(images and their location)*
- Bookmarks slightly larger and more space between bookmarks
- Removed buttons **'Sidebar'** and **'List of all tabs'**
- Changed tab close button :x: and new tab creation button :heavy_plus_sign:

---

# :point_up_2: Using :
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

---

//Установка:
// Набрать в поисковой строке "about:config", там вставить "toolkit.legacyUserProfileCustomizations.stylesheets" и сделайте его значение "True" (это нужно чтобы браузер подключал css темы)
// Скачать папку chrome и переместить её в папку с профилем браузера (ввести в поисковик "about:support", нажать "Открыть папку" справа от "Папка профиля")
// Перезапустить браузер
