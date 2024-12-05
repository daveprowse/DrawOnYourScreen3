# Draw On Your Screen 3

![DOYS3](https://daveprowse.github.io/DrawOnYourScreen3/images/doys-logo2.png)

Start drawing on your GNOME desktop with **`Super+Alt+D`**.

Documentation is **[here](https://daveprowse.github.io/DrawOnYourScreen3/)**. For updates, click **[here](https://daveprowse.github.io/DrawOnYourScreen3/blog/)**.

- Forked from: https://github.com/zhrexl/DrawOnYourScreen2
- Original fork: https://codeberg.org/som/DrawOnYourScreen

Thank you to all the contributors! 😎

## Features

- Draw over applications
- Basic shapes (rectangle, circle, ellipse, line, curve, polygon, polyline, arrow, text, image, free)
- Basic transformations (move, rotate, resize, stretch, mirror, inverse)
- Blackboard and Grid
- Keep drawings on desktop background with persistence
- Multi-monitor support
- Save your work with `Ctrl+S`!!

## Installation Methods for GNOME v47 and v46

> Note: We are working on getting the extension approved by GNOME so that it will be listed on https://extensions.gnome.org (E.G.O.) 

> Stay tuned! Click [here](https://daveprowse.github.io/DrawOnYourScreen3/blog/) for updates.

### Option 1: Use the Automated Script

Copy the following command to your Bash terminal and press `enter` to run it:

```bash
bash <(wget -qO- https://raw.githubusercontent.com/daveprowse/scripts/refs/heads/main/doys-install.sh)
```

> **IMPORTANT!!** Always check scripts before running them! If you are uncomfortable running the script, or cannot run the script, then install manually with [Option #2](#option-2-install-manually-from-the-release-or-repository-branch) below.

The script will identify your version of GNOME (if it is between v42 and v47) and install the correct version of the extension automatically.

When complete, logout and log back in 

Then enable the extension:

- In the CLI:

  ```console
  gnome-extensions enable draw-on-your-screen3@daveprowse.github.io
  ```

- In the GUI
  - Open the GNOME Extensions App:

      `gnome-extensions-app`

  - Locate Draw On Your Screen 3 and enable it.

   > Note: You can install the Gnome Extensions App with the package `gnome-shell-extensions-prefs` within your Linux distribution.

Now go forth and use the tool by pressing `Super + Alt + D`.

> Note: You can discover the keyboard shortcuts by pressing `Ctrl + F1`.

It's back to the drawing board my friends!

### Option 2: Install Manually from the Release or Repository Branch

> Note: For GNOME versions other than 47 & 46, see [Other GNOME Versions](#other-gnome-versions) below.

1. Download or clone
   - Download option:
  
      ```console
      wget https://github.com/daveprowse/DrawOnYourScreen3/releases/download/v15.0-GNOME-v47/GNOMEv47.tar.xz
      ```

      Then, decompress the tar file: `tar -xvf GNOMEv47.tar.xz`

   - Clone option:
  
      ```console
      git clone https://github.com/daveprowse/DrawOnYourScreen3
      ```

2. Place the directory (the one that contains `metadata.json`) in `~/.local/share/gnome-shell/extensions`
3. Change the directory name to `draw-on-your-screen3@daveprowse.github.io`
4. Restart your session: 

   - (Wayland) - Log out and log back in
   - (Xorg) - Type `alt + F2` and `r` to restart the gnome-shell

5. Enable the extension with GNOME Extensions command or application
6. `Super + Alt + D` to test

*Issues?* Let us know at [this link](https://github.com/daveprowse/DrawOnYourScreen3/issues).

**ENJOY!**

---

### Other GNOME Versions

If you prefer not to use the script above, and have an older version of GNOME, choose from a download method below and then follow steps 2 through 6 above.

#### GNOME v45

Download or clone this repository branch
   - Download option: 
  
      ```console
      wget https://github.com/daveprowse/DrawOnYourScreen3/releases/download/v14.0-GNOME-v45/GNOMEv45.tar.xz
      ```

      Then, decompress the tar file: `tar -xvf GNOMEv45.tar.xz`

   - Clone option:
  
      ```console
      git clone -b GNOMEv45 https://github.com/daveprowse/DrawOnYourScreen3

#### GNOME v42 - 44

Download or clone this repository branch
   - Download option: 
  
      ```console
      wget https://github.com/daveprowse/DrawOnYourScreen3/releases/download/v13.0-GNOME-v42-v44/GNOMEv42.tar.xz
      ```

      Then, decompress the tar file: `tar -xvf GNOMEv42.tar.xz`

   - Clone option:
  
      ```console
      git clone -b GNOMEv42 https://github.com/daveprowse/DrawOnYourScreen3
      ```
