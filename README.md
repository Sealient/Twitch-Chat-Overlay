# Stream Chat Overlay

A lightweight desktop chat overlay for streams. It can connect to Twitch chat or display a universal URL/WebSocket source while staying on top of other windows.

## Download

Download the Windows installer here OR Head over to the Releases to get it:

[Download Stream Chat Overlay 2.0.0](https://github.com/Sealient/Twitch-Chat-Overlay/releases/download/StreamOverlay_2.0/stream-overlay.Setup.2.0.0.exe)

Run the installer, then launch **Stream Overlay** from the Start menu or desktop shortcut. Windows may show a security prompt because the installer is not code-signed; verify that you downloaded it from the release link above before choosing to run it.

## Quick Start

1. Open the overlay.
2. Click the menu button in the top-left corner to open **Settings**.
3. Under **Connection**, choose `Twitch (IRC WebSocket)`.
4. Enter the Twitch channel name without the `#`, for example `Sealient`.
5. Click **Apply & Save**.
6. Drag the header to position the overlay over your stream or recording software.
7. Press `Alt+L` to lock it in place and make it click-through.

The connection status appears below the header. The overlay reconnects automatically when enabled in Settings.

## Settings

### Connection

- **Platform / Feed Type**: Use Twitch for a Twitch channel, or Universal for an embed URL or WebSocket source.
- **Channel Name / URL**: Enter a Twitch channel, webpage URL, `ws://` URL, or `wss://` URL depending on the selected feed type.
- **Auto-reconnect**: Reconnect automatically after a connection drops.

### Appearance

- **Color Theme**: Choose Violet, Ocean Blue, Mint, or Monochrome.
- **Opacity**: Changes the transparency of chat bubble backgrounds. Message text remains readable and fully opaque.
- **Font Size**: Adjust the chat text size.
- **Max Visible Messages**: Set how many messages remain visible at once.
- **Custom CSS Injection**: Add CSS rules for further visual customization.

### Sound

Notification sounds can be changed while the overlay is running:

- Use **Notification Sound** to choose a sound already in the sounds folder.
- Click **Add** to import an `.mp3`, `.wav`, or `.ogg` file.
- Click **Refresh** after adding or removing files manually.
- Click **Open Sounds Folder** to open the persistent sound folder in Explorer.
- Select **Built-in chime** to use the default sound.
- Use **Volume** or **Mute** to control playback immediately.

Sound changes do not require restarting the app or clicking **Apply & Save**.

### Preview

- **Send Test Message** checks the message styling and notification sound.
- **Clear Chat** removes the messages currently shown.

## Locking and Shortcuts

- `Alt+L`: Lock or unlock the overlay. When locked, the entire window becomes click-through.
- `Alt+R`: Move the overlay back to a safe position if it is off-screen.
- Right-click: Open the quick action menu for locking, resetting the position, opening the sounds folder, or quitting.

Click the lock control in the top-right corner to lock the overlay manually. Unlock it with `Alt+L` or the quick action menu.

## Troubleshooting

**No messages appear**

Check the channel name or source URL, confirm the status text below the header, and make sure the selected feed is available. Turn on auto-reconnect if the source is intermittent.

**A sound does not play**

Open Settings, click **Refresh**, and select the sound again. Supported formats are `.mp3`, `.wav`, and `.ogg`. Use **Send Test Message** to test the current selection.

**The overlay is missing or off-screen**

Press `Alt+R` to reset its position, then drag the header to the desired location.
