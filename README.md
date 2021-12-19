# Aesthetics of Death - grub theme

This theme is optimized for 3456x2160 screen resolution

---

To make sure that everything is ok, I recommend you to set the certain resolution into `/etc/default/grub`

Like this:

```bash
GRUB_GFXMODE=3456x2160
```

On my notebook it looks like this:

![installed theme screenshot](https://raw.githubusercontent.com/nikelborm/aesthetics_of_death_grub_theme/main/screenshot.png?raw=true)

---

Photo was taken from [Unsplash](https://unsplash.com/) and made by [Mathew MacQuarrie](https://unsplash.com/@matmacq) (this message from future, when I updated screenshot)

There are really cool photos

---

There is also [one useful guide](wiki.rosalab.ru/en/index.php/Grub2_theme_tutorial) on how to make a theme for grub

A lot of thanks to it`s author

And I used `grub-mkfont` to get special grub font `.pf2` type:

```bash
grub-mkfont -s 72 -o dersu_uzala_brush_72.pf2 ./Aesthetics_of_death/Dersu\ Uzala\ brush.ttf
```

[This article](wiki.rosalab.ru/en/index.php/Grub2_theme_tutorial#Font_creation_guide) describes how to use this tool

---

Also my respects to [author](https://github.com/semimqmo) of [original Sekiro theme](https://github.com/semimqmo/sekiro_grub_theme)

![original theme screenshot](https://raw.githubusercontent.com/nikelborm/aesthetics_of_death_grub_theme/main/original_screenshot.png?raw=true)
