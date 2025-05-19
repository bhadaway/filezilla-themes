The Dark and Flat FileZilla themes are using free icons from Font Awesome (https://github.com/FortAwesome/Font-Awesome?tab=readme-ov-file#license).

There aren't many FileZilla themes or resources on how to actually add or create your own custom FileZilla themes, so here are some...

## Helpful notes:

1. FileZilla themes aren't themes in the traditional sense, like you'd think of a WordPress theme. Rather, they're just custom icon packs for some of the FileZilla client UI buttons.
2. You can't install or import themes into FileZilla in a traditional sense; they need to be manually added into FileZilla's configuration files. I'll add instructions for both Windows and Mac below.
3. You can't explicitly set FileZilla to light or dark mode; it automatically follows your OS settings for this. *Flat* is meant for light mode and *Dark* for dark mode.

## How to add a custom FileZilla theme on Windows

1. Download a FileZilla theme like *Dark* and copy the theme folder (example: */dark/* — it'll contain icon image files and a *theme.xml* file)
2. Right-click on the FileZilla program icon and then click "Open file location" (example: *Program Files > FileZilla FTP Client > resources*)
3. Paste the theme folder (example: */dark/*) into the */resources/* folder
4. Open (or close and then reopen if it's already open) FileZilla
5. From the program menu, navigate to: *FileZilla > Settings > Interface > Themes*
6. Select your new theme from the dropdown and click "OK" (part of the theme may take effect immediately, but you might also need to restart FileZilla for it to take effect fully)

## How to add a custom FileZilla theme on Mac

1. Download a FileZilla theme like *Dark* and copy the theme folder (example: */dark/* — it'll contain icon image files and a *theme.xml* file)
2. Right-click on the FileZilla app icon and then click "Show Package Contents" (example: *Applications > FileZilla.app > SharedSupport > resources*)
3. Paste the theme folder (example: */dark/*) into the */resources/* folder
4. Open (or close and then reopen if it's already open) FileZilla
5. From the app menu, navigate to: *FileZilla > Settings > Interface > Themes*
6. Select your new theme from the dropdown and click "OK" (part of the theme may take effect immediately, but you might also need to restart FileZilla for it to take effect fully)

## How can we improve?

Let me know: https://github.com/bhadaway/filezilla-themes/issues

From the icon sizing and padding to the icons themselves.

I tried to pick the most logical icons for what they're meant to represent, but some might be confusing and require either an entirely different icon or some custom element to make their function more clear.

You can browse icons here for suggestions (make sure to set the filter to "Free"): https://fontawesome.com/icons

Thanks!
