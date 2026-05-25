# Logs

Brainy stores log files locally on your device. These can be useful for diagnosing issues or reporting bugs.

## Log File Location

Log files are stored in a platform-specific directory:

| Platform | Path | Example |
| -------- | ---- | ------- |
| Linux | `$XDG_DATA_HOME/app.brainylearn/logs` or `$HOME/.local/share/app.brainylearn/logs` | `/home/alice/.local/share/app.brainylearn/logs` |
| macOS | `{homeDir}/Library/Logs/app.brainylearn` | `/Users/Alice/Library/Logs/app.brainylearn` |
| Windows | `{FOLDERID_LocalAppData}/app.brainylearn/logs` | `C:\Users\Alice\AppData\Local\app.brainylearn\logs` |
| Android | `{ConfigDir}/logs` | `/data/data/app.brainylearn/files/logs` |
