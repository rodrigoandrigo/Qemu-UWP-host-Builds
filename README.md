# Qemu-UWP-host-Builds
Builds, dependencies, and instructions



## Dependence 

Microsoft.VCLibs.x64.Debug.14.00.appx



## Instructions for compiling the DLLs in UWP format

qemu_uwp_embedding_changes.txt

qemu_uwp_host_rebuild_instructions.txt



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
