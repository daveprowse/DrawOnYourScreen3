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

## Installation

> Note: We are working on getting the extension approved by GNOME so that it will be listed on https://extensions.gnome.org (E.G.O.) 

> Stay tuned! Click [here](https://daveprowse.github.io/DrawOnYourScreen3/blog/) for updates.

---

1. Copy the following command to your Bash terminal and press `enter` to run it:

   ```bash
   bash <(wget -qO- https://raw.githubusercontent.com/daveprowse/scripts/refs/heads/main/doys-install.sh)
   ```

   The script will attempt to identify your version of GNOME and install the correct version of the extension automatically.

   > Note: Currently, the script will identify GNOME v47 through v40 and back all the way to v3.xx.

   > **IMPORTANT!!** Always check scripts before running them! If you are uncomfortable running the script, or cannot run the script, then install manually with an option listed in the [Documentation](https://daveprowse.github.io/DrawOnYourScreen3/installation/).

2. Logout and log back in.

3. Enable the extension:

- In the CLI:

  ```console
  gnome-extensions enable draw-on-your-screen3@daveprowse.github.io
  ```

- Or in the GUI
  - Open the GNOME Extensions App:

      `gnome-extensions-app`

  - Locate Draw On Your Screen 3 and enable it.

   > Note: You can install the Gnome Extensions App with the package `gnome-shell-extensions-prefs` within your Linux distribution.

4. Now go forth and use the tool by pressing `Super + Alt + D`.

   > Note: You can discover the keyboard shortcuts by pressing `Ctrl + F1`.

It's back to the drawing board my friends! Enjoy! 😎

---

### Note about GNOME 48

I am not supporting GNOME version 48 until final release. However you can run the extension on GNOME 48 if you do the following:

1. Edit the following file:

    ```
    ~/.local/share/gnome-shell/extensions/draw-on-your-screen3@daveprowse.github.io/metadata.json
    ```

2. Add "48" as shown below.

```json
    "shell-version": [
        "46",
        "47",
        "48"
    ],
```

Functionality is not guaranteed, but it "appears" to work fine for now. This is updated in the "main" branch, but not in the releases yet.

---

## Manual Installs

📖 For manual installation procedures (git clone and tarball) see the **[Documentation](https://daveprowse.github.io/DrawOnYourScreen3/installation/)**.
