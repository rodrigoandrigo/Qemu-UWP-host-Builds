## Qemu-UWP-host-Builds
Builds, dependencies, and instructions

Qemu-UWP-host_1.0.0.2_FIX1.msixbundle
- In normal mode, with the virtual keyboard closed:
- `X Button` = left mouse click.
- `Y Button` = right mouse click.
- With the virtual keyboard open, the behavior remains:
- `X Button` presses the selected key.
- `Y Button` closes the virtual keyboard.



## Dependence 

Microsoft.VCLibs.x64.Debug.14.00.appx



## Instructions for compiling the DLLs in UWP format

qemu_uwp_embedding_changes.txt

qemu_uwp_host_rebuild_instructions.txt



## Modified QEMU 11.0.2 files

https://github.com/rodrigoandrigo/Qemu-Dll-shadps4



## Gamepad inputs (introduced in version 1.0.0.2)

| Controller input | Action |
| --- | --- |
| Left analog stick | Moves the guest mouse pointer |
| Directional Pad Up | Sends QEMU Up arrow |
| Directional Pad Down | Sends QEMU Down arrow |
| Directional Pad Left | Sends QEMU Left arrow |
| Directional Pad Right | Sends QEMU Right arrow |
| A Button | Sends QEMU Enter |
| Left Trigger + Right Trigger | Shows or hides the virtual keyboard |
| Directional Pad | Moves the selected key in the virtual keyboard |
| X Button | Presses the selected virtual key |
| Y Button | Closes the virtual keyboard |
| Left Bumper + Right Bumper | Toggles mouse and keyboard capture, same as `Ctrl+Alt+M` |



## Qemu-UWP-host_1.0.0.2_FIX1

[![YouTube](https://img.youtube.com/vi/TbSgt6bOaEI/0.jpg)](https://www.youtube.com/watch?v=TbSgt6bOaEI)



## References

https://github.com/rodrigoandrigo/Qemu-Libretro-UWP/tree/main
