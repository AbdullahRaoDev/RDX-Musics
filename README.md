# RDX Musics

[![Download APK](https://img.shields.io/badge/Download-APK-2ea44f?style=for-the-badge&logo=android)](https://github.com/AbdullahRaoDev/RDX-Musics/releases/latest/download/RDX-Musics.apk)

> High-Quality Ad-Free Music Streaming Client for Android • Developed by Abdullah Naeem Rao

RDX Musics is a fast, modern Android music client focused on clean playback, a distraction-free listening experience, and a polished dark interface.

## Key Features

- **High-Bitrate Opus Audio Streaming** for detailed, efficient playback.
- **Built-in Loudness Normalization** using `loudnessDb` for zero headphone clipping.
- **Background Playback** that continues with the screen off.
- **Offline Song Caching** for listening when connectivity is unavailable.
- **Material 3 Dark UI** designed for a comfortable, modern Android experience.

## Tech Stack

- Kotlin
- Jetpack Compose
- Media3 / ExoPlayer
- Dagger Hilt
- Room
- Kotlin Coroutines

## Installation

1. Open the repository's **Actions** tab on GitHub.
2. Select the latest **Build RDX Musics APK** workflow run.
3. Download the **RDX-Musics** artifact.
4. Extract `RDX-Musics.apk` and install it on an Android device running Android 8.0 (API 26) or newer.

You can also build the FOSS release locally with:

```bash
./gradlew assembleFossRelease
```

The generated APK is located under `app/build/outputs/apk/foss/release/`.

## Development

The Android package namespace remains `com.metrolist.music` for compatibility with the existing Hilt, Room, and internal source structure. The installable application ID is `com.rdx.musics`.

## License

RDX Musics is distributed under the GNU General Public License v3.0. This project retains the applicable GPL-3.0 license and attribution obligations from its upstream open-source code. See [LICENSE](./LICENSE) for the full license text.
