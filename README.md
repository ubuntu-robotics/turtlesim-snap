# turtlesim-snap

Snap packaging for the ROS 2 `turtlesim` graphical application on Ubuntu Core 24.

## Build locally

```bash
snapcraft
```

## Install locally

```bash
sudo snap install ./turtlesim_*.snap --dangerous
```

## Launch

```bash
snap run turtlesim.turtlesim
```

## Notes

- This snap uses `core24` and the `ros2-jazzy` extension.
- Because `turtlesim` is graphical, the app also uses the `kde-neon-6` extension and plugs `x11`, `wayland`, and `opengl`.
