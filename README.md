# org.kde.krita

## Workarounds

- Select recording directory opens file selector instead of folder selector with KDE portal. Related Issue [#50](https://github.com/flathub/org.kde.krita/issues/50).

  Modify the file at ``~/.var/app/org.kde.krita/config/kritarc`` to set the directory.
  ```
  recorder/snapshotdirectory=/var/home/user/KritaRecording
  recorder_export/videodirectory=/var/home/user/Videos
  ```

## FAQ

- Why is this not using the KDE Platform?

See https://github.com/flathub/org.kde.krita/issues/44

## Special permissions

- `--system-talk-name=org.freedesktop.ColorManager`: Needed for colord to work
