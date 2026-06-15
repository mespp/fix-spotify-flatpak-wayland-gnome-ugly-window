# Fix Spotify (Flatpak) Window Decoration Bug in GNOME (Wayland)

Fix for the **ugly, misaligned blue title bar** that appears on the Spotify Linux client when running natively on **Wayland** inside GNOME-based desktop environments.

---

## 🛠️ Fix

Run the following command in your terminal:

```bash
flatpak override --user --nosocket=wayland com.spotify.Client
```

To apply the changes immediately by killing any background process:

```bash
flatpak kill com.spotify.Client
```
