<div align="center">
  <img src="assets/banner-profile.svg" width="100%" alt="Salcedo Andrew — wedding film and photo, macOS tools">
</div>

<p align="center">
  Wedding film and photo by trade. I re-built the macOS tools that fit into my workflow mainly in file management because the ones that existed did not fit the way I work.
</p>

<p align="center">
  <a href="https://github.com/Salcedoandrew?tab=repositories"><img alt="repositories" src="https://img.shields.io/badge/repositories-0B0C0E?style=flat-square&logo=github&logoColor=C8C4B8"></a>
  <img alt="wedding film and photo" src="https://img.shields.io/badge/wedding-film%20%26%20photo-0B0C0E?style=flat-square">
  <img alt="macOS tooling" src="https://img.shields.io/badge/macOS-C%2B%2B%20%C2%B7%20Swift%20%C2%B7%20Rust-D8A24A?style=flat-square&labelColor=0B0C0E">
</p>

## Now

- Shooting and cutting weddings, then culling the day in **Apature**, which I keep patched to my own Photo Mechanic loop.
- Ship-ready offloading: **Offload** writes a card to several drives at once, hashes each copy, reads it back, and leaves an MHL report on the drive.
- Moving the archive into Immich through **SalcedoSync**, and re-encoding the keepers with **HandBrakeBatch**.

## On the bench

What is public and has a release. The state column is the honest one.

| Repo | What it does | State |
|---|---|---|
| [freefilesync-offload](https://github.com/Salcedoandrew/freefilesync-offload) | FreeFileSync fork: verified card offload for macOS, with a native window | released, `v0.4.0` |
| [SalcedoSync](https://github.com/Salcedoandrew/SalcedoSync) | Uploads photos to Immich with album choices, compression and in-app progress | released, `v1.5.2-mod` |
| [Salcedos-Apature](https://github.com/Salcedoandrew/Salcedos-Apature) | Keyboard-first culler, adapted from Apature for the way I cull a wedding | released, `v0.1.2` |
| [HandBrakeBatch](https://github.com/Salcedoandrew/HandBrakeBatch) | Batch encoding for the archive, modernised after the original stopped moving | released, `v1.4.0` |
| [DupeCleaner](https://github.com/Salcedoandrew/DupeCleaner) | Finds duplicate files across drives that have been copied too many times | released, `v4.4.0` |

## Toolbox

Grouped by the job, not by logo count.

| Work | Tools |
|---|---|
| macOS apps | C++ · Swift and SwiftUI · Rust · wxWidgets |
| Glue and automation | Python · shell · launchd · ffmpeg |
| Photo workflow | Photo Mechanic-style culling · Immich · HandBrake · ASC MHL |
| Taking things apart | Ghidra · IDA · REA, to see how an app actually does it before I replace it |

## Where the work is

Start with **[Offload](https://github.com/Salcedoandrew/freefilesync-offload)** if you shoot cards and want proof the copy landed, and **[Apature](https://github.com/Salcedoandrew/Salcedos-Apature)** if you cull for a living. Both exist because a wedding workflow needed them, not because macOS needed another app.

<div align="center">
  <img src="assets/rule-filmstrip.svg" width="100%" alt="">
  <sub>Salcedo Andrew · <a href="https://github.com/Salcedoandrew?tab=repositories">all repositories</a> · <a href="#top">back to the top</a></sub>
</div>

<!--
  Add these once you want them public, in the same style as the badges above:

  <a href="https://your-portfolio"><img alt="portfolio" src="https://img.shields.io/badge/portfolio-0B0C0E?style=flat-square&logo=safari&logoColor=C8C4B8"></a>
  <a href="mailto:you@example.com"><img alt="email" src="https://img.shields.io/badge/email-0B0C0E?style=flat-square&logo=maildotru&logoColor=C8C4B8"></a>

  The banner is assets/banner-profile.svg — its text is real SVG text, so edit the
  words there rather than editing the image. If a repo stops having a release, move its
  row out of "On the bench" instead of letting the state column go stale.
-->
