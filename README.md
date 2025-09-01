## Actions Images

This repository provides a set of docker images that can be used to
build Flatpaks in a CI environment such as GitHub or Gitlab. These
can be paired with [flatpak-github-actions](https://github.com/flatpak/flatpak-github-actions).

The following images are available:

| Runtime         | Version    | Tag                 | Example                                                                 |
| --------------- | -----------| ------------------- | ------------------------------------------------------------------------|
| Freedesktop SDK | 23.08      | `freedesktop-23.08` | `image: ghcr.io/flathub-infra/flatpak-github-actions:freedesktop-23.08` |
| Freedesktop SDK | 24.08      | `freedesktop-24.08` | `image: ghcr.io/flathub-infra/flatpak-github-actions:freedesktop-24.08` |
| Freedesktop SDK | 25.08      | `freedesktop-25.08` | `image: ghcr.io/flathub-infra/flatpak-github-actions:freedesktop-25.08` |
| GNOME           | 47         | `gnome-47`          | `image: ghcr.io/flathub-infra/flatpak-github-actions:gnome-47`          |
| GNOME           | 48         | `gnome-48`          | `image: ghcr.io/flathub-infra/flatpak-github-actions:gnome-48`          |
| KDE             | 5.15-24.08 | `kde-5.15-24.08`    | `image: ghcr.io/flathub-infra/flatpak-github-actions:kde-5.15-24.08`    |
| KDE             | 6.7        | `kde-6.7`           | `image: ghcr.io/flathub-infra/flatpak-github-actions:kde-6.7`           |
| KDE             | 6.8        | `kde-6.8`           | `image: ghcr.io/flathub-infra/flatpak-github-actions:kde-6.8`           |
| KDE             | 6.9        | `kde-6.9`           | `image: ghcr.io/flathub-infra/flatpak-github-actions:kde-6.9`           |
