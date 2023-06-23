# Browser Fullscreen Lock

Browser Fullscreen Lock is a script that allows you to lock fullscreen mode to your web browser, ensuring a seamless and uninterrupted video watching experience.

## Description

Have you ever wanted to use splitscreen mode, and full screen at the same time? Browser Fullscreen Lock solves this problem by providing a convenient way to lock fullscreen mode to your web browser, preventing the default fullscreen mode from occuring.

With a simple keyboard shortcut, the script activates your browser window and triggers fullscreen mode within the browser itself, instead of using the full viewport of the screen. This allows you to stay focused on your video content without the fear of unintentionally taking over the entire screen.

Browser Fullscreen Lock is compatible with any web browser and leverages the power of the `xdotool` command-line tool to automate the process.

## Features

- Locks fullscreen mode to your web browser
- Prevents accidental switching to fullscreen across the entire desktop
- Compatible with any web browser
- Easy to use with a simple keyboard shortcut

## Usage

1. Ensure that the `xdotool` command-line tool is installed on your system. If not, install it using the package manager for your Linux distribution.

2. Clone or download the `browser-fullscreen-lock.sh` script from this repository.

3. Open the script in a text editor and replace `"browser_name"` with the actual name of your web browser. For example, if you use Firefox, replace it with `"firefox"`. Save the changes.

4. Make the script executable by running the following command in the terminal:
chmod +x browser-fullscreen-lock.sh

5. Create a custom keyboard shortcut to easily trigger the script:
- Go to the system settings of your Linux distribution.
- Look for the "Keyboard Shortcuts" or "Keyboard" settings.
- Add a new custom shortcut.
- Provide a name for the shortcut (e.g., "Browser Fullscreen Lock").
- In the "Command" field, enter the full path to the script (e.g., `/path/to/browser-fullscreen-lock.sh`).
- Assign a keyboard shortcut of your choice, such as `Ctrl+Alt+F` or any other combination not already in use.

6. Open your web browser and play a video.

7. Use the custom keyboard shortcut you created to lock fullscreen mode to your browser.

8. Enjoy your videos in fullscreen mode within your browser, without any accidental disruptions.

## Compatibility

This script is compatible with Linux-based systems and should work with any web browser.

## Dependencies

- `xdotool`: The script relies on the `xdotool` command-line tool for automating window and keyboard operations. Ensure that `xdotool` is installed on your system before using this script.

## Contributing

Contributions to Browser Fullscreen Lock are welcome! If you have any ideas, improvements, or bug fixes, feel free to submit a pull request.

## License

This script is released under the [MIT License](LICENSE).




