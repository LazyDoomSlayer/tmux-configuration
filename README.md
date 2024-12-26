Here's an updated README reflecting your custom `Ctrl + Space` prefix key:

---

# Tmux Plugin Manager (TPM) Setup Guide

This guide helps you set up the Tmux Plugin Manager (TPM) to easily manage plugins in Tmux.

## 1. Installation

To install TPM, clone the repository into your `.tmux` plugins directory:

```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## 2. Configure Plugins in `.tmux.conf`

Add the following lines to your `~/.tmux.conf` file to enable TPM and any other plugins you'd like to use.

```tmux
# Initialize TPM (this is required for TPM to work)
set -g @plugin 'tmux-plugins/tpm'

# Add additional plugins here
set -g @plugin 'tmux-plugins/tmux-sensible'  # Sensible default Tmux configurations

# Ensure this line is at the very bottom of ~/.tmux.conf
run '~/.tmux/plugins/tpm/tpm'
```

## 3. Applying Changes

If Tmux is already running, reload your configuration with this command:

```bash
tmux source ~/.tmux.conf
```

## 4. Installing Plugins

Once you've configured your plugins, use the following key combination within a Tmux session to install them:

1. Press the prefix key (`Ctrl + Space` in your setup).
2. Then press `I` (uppercase i) to install the plugins specified in `~/.tmux.conf`.

This will download and install all the plugins listed.

---

Now you're ready to use TPM and easily manage your Tmux plugins!
