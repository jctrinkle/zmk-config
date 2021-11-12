# Changing your Keymap in ZMK
1. Make the desired edits to your [peilert_cyboard.keymap file](config/boards/shields/peilert_cyboard/peilert_cyboard.keymap) and commit them.
2. GitHub will automatically run an Action to build your firmware. this takes approximately 2 minutes for most changes.
3. Once the Action is successful, there will be a firmware "artifact" in the Action which you can download and unzip.
4. Connect the left (central) half of your Cyboard to your computer via USB.
5. Put your Cyboard in bootloader mode.
6. Copy the .uf2 file into the USB device named Nice Nano.
7. You're done! You can now disconnect your Cyboard from your computer.
