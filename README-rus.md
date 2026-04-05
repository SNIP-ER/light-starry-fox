# :page_with_curl: Содержание
- :bangbang: [ВНИМАНИЕ](#light_starryFox)
- :dna: [Изменения](#change)
- :inbox_tray: [Установка](#install)
- :point_up_2: [Использование](#using)

---

##  <a id="light_starryFox">:star2: Light StarryFox</a>
<p>
<h4>:bangbang: Изображение логотипа, название "Firefox" и задний фон, а так же идея, были взяты от <a href="https://github.com/sagars007/starry-fox" target="_blank">сюда</a></h4>
</p>

---

## <a id="change">:dna: Изменения :</a>
2. Версия 2
 - Изменены кнопки **"Add new tab"**, **"Reload"**, **"Back"** and **"Forward"**
 - Изменены кнопки управления окном
 - Добавлен задний фон для использования без расширения *(в файле **"userChrome.css"** уберите /\* и \*/)*

1. Версия 1 (Название папки - chrome)
 - Изменен **задний фон**:desktop_computer:, **логотип**:fox_face:, **надпись Firefox**:page_facing_up: на домашней странице *(изображение и их положение)*
 - Увеличились иконки в панели закладок и расстояние между ними
 - Убраны кнопки **'Sidebar'** и **'List of all tabs'**
 - Изменены кнопки закрытия :x: вкладок и открытия новой :heavy_plus_sign:

---

## <a id="install">:inbox_tray: Установка :</a>
**1.** :anger: Введите **"about:config"** в адресную строку, в поиск введите **"toolkit.legacyUserProfileCustomizations.stylesheets"** и поменяйте значение на **"True"** *(это нужно, чтобы браузер применял CSS темы)* <br/>

**2.** :envelope_with_arrow: Скачайте нужную версию с репозитория и перейдите в папку профиля браузера *(введите **"about:support"** в адресную строку, после нажмите на кнпопку **"Open Folder"** после **"Profile Folder"**)* <br/>

**3.** :electric_plug: Перезапустите браузер

---

## <a id="using">:point_up_2: Использование :</a>
- Рекомендуется использовать расширение - [Adaptive Tab Bar Colour](https://github.com/easonwong-de/Adaptive-Tab-Bar-Colour) :sparkles:
- Если вы хотите изменить :scissors: обои главной страницы:
  1. Откройте папку **'chrome'** :file_folder: *(смотри установку)*
  2. Поместите свою image/gif в папку **'image'** :file_folder:
  3. Открой файл **'userContent.css'** :file_cabinet: в любом текстовом редакторе *(можно даже блокнот Windows)*
  4. Найли где написан этот файл **'Animation_Of_Stars-25-fps-compress.gif'** и замени :scissors: на название своего

  ```
  body {
		background: url("images/Animation_Of_Stars-25-fps-compress.gif") no-repeat fixed !important;
		background-size: cover !important;
	}
  ```
