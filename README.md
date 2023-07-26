# AdvancedMap

[Lilu][1] plugin for enabling modern maps on non-Apple Silicon hardware.

Advanced maps were added in macOS 12 Monterey, and worked fine on Intel hardware in the early betas. Later betas blocked the support. I suspect Apple aren't fully testing it on Intel, so perhaps not all hardware is supported, but it works well for me.

It _seems_ like it requires a dGPU (see below for support). Please let me know if it works/doesn't work for you!

## Example Screenshots

### 3D Globe

![](https://i.imgur.com/fgxOGhS.png)

### Improved POI Markers

![](https://i.imgur.com/vN51oTH.png)

### Road Markings & Trees

![](https://i.imgur.com/NCIxf0D.png)

## Confirmed Supported GPUs

- AMD RX570
- AMD 5500XT
- AMD 5700XT

## Confirmed Unsupported GPUs

- UHD630

### Configuration

- Add `-advmapoff` to disable AdvancedMap
- Add `-advmapbeta` to enable AdvancedMap on unsupported OS versions (14.x is supported by
  default)

### Downloads

Available on the [releases][2] page.

[1]: https://github.com/acidanthera/Lilu
[2]: https://github.com/notjosh/AdvancedMap/releases
