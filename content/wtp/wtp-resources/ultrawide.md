---
title: "Ultrawide Support"
weight: 2
type: docs
description: >
  UI patch and support for ultrawide monitors.
---

For users with a monitor resolution of 21:9 (ultrawide), manually changing the resolution is required as well as a patch for the interface.

## Changing the resolution

- Open the INI editor in Mod Organizer 2.

![Open INI Editor](/Pictures/wtp/installation/mo2-ini-editor.png)

- Switch to the fallout4prefs.ini tab and scroll down to the [Display] section.
- Replace the following two lines with the set matching your monitor resolution:
  - `iSize W=`
  - `iSize H=`
- Click **Save** and close the window.

**For 2560x1080**

```
iSize W=2560
iSize H=1080
```

**For 3440x1440**

```
iSize W=3440
iSize H=1440
```

## TruBy9 Ultrawide

The most comprehensive widescreen fix mod for Fallout 4, [TruBy9 Ultrawide](https://www.nexusmods.com/fallout4/mods/2463), is already pre-installed in WTP. All you need to do is activate it and some additional fixes.

- In Mod Organizer 2, scroll to the **ULTRAWIDE SUPPORT (OPTIONAL)** section under **INTERFACE**.
- Check all mods below that separator.

---

#### Continue with the [New Game](/wtp/installation/new-game/) page.
