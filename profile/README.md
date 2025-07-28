# Backup-chan

Backup-chan is an automatically managed, deduplicated, modular backup system.

## Get started

1. [Install and configure the server](https://github.com/Backupchan/server?tab=readme-ov-file#setting-up).
2. Install the [CLI](https://github.com/Backupchan/cli):
   * ```bash
     pip install backupchan-cli
     ```
4. Configure the CLI:
   * ```bash
     # Interactively
     backupchan config new -i

     # Pass new configuration with arguments
     backupchan config new -H host -p port -a api-key
     ```
5. All done! You can run the server and access it through the CLI now.

> [!NOTE]
> You can also access your Backup-chan server through a web browser (assuming the web UI is enabled in your config), however I recommend using the CLI as it's faster
> and cooler.

## A word on stability

At the moment, Backup-chan is pretty stable: it works and doesn't regularly explode, but until I personally have used it for long enough to ensure it actually works
well, I'm calling it beta-quality software. Use at your own risk, and maybe open an issue or two if something's seriously broken.
