# Reminders

___Set reminders for yourself___

What you can do with Reminders:

- Set recurring reminders
- Schedule notifications
- Sort, filter, and search for reminders
- Mark reminders as important or complete
- Organize reminders using lists
- Optionally play a sound when notifications are sent
- Optionally sync with Microsoft To Do

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub io.github.dgsasha.Remembrance
flatpak run flathub io.github.dgsasha.Remembrance
```

## Building

```
git clone git@github.com:flathub/io.github.dgsasha.Remembrance.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.dgsasha.Remembrance.yml
```
