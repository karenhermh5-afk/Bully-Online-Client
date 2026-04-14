===== Bully Online Launcher =====

The Bully Online Launcher is responsible for starting the game, managing basic configuration,
and handling optional launch parameters. It simply acts as a lightweight entry point between
the user and the game executable.

===== System Requirements =====

Operating System: Windows
CPU: Any modern x86/x64 processor
RAM: 100 MB minimum
Disk Space: Minimal (launcher only)

===== Installation =====

- Extract the launcher files into a directory of your choice.
- Ensure the launcher.config.json is present in the same location as the launcher.
    (launcher won't run without it)
- Run the launcher executable.

You can then start the launcher normally by double-clicking it or via the command line.

The configuration file should not normally be edited manually. The launcher owns and manages
this file during execution, and any changes made while the launcher is running will be overwritten
on exit. Manual edits should only be performed when absolutely necessary.

===== Uninstallation =====

Just delete the launcher directory.

===== Usage =====

The launcher requires you to provide the Steam directory (e.g, C:\Program Files (x86)\Steam) as well as the
Bully Scholarship Edition directory (e.g, C:\Program Files (x86)\Steam\steamapps\common\Bully Scholarship Edition).
This is done in the configuration tab at the top.

Bully Online is already included as one of the listed servers by default. If you
use other instances of derpy's script server you can add them via the launcher as well
by clicking on "Add new server" and specifying the appropriate ip and port.

===== Note =====

Account details for servers are stored inside the config file as plain text.
Do not share or open it in plain view of others!

===== Known Issues & Bugs =====

About tab (unimplemented, cosmetic)
LAA (Large Address Aware) & Hash warnings (unimplemented, no functional impact)

If you encounter any other problems, feel free to report it to the Bully Online Team. :)
