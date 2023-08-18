# OBS Stopwatch Browser Source

A flexible stopwatch designed for integration into OBS (Open Broadcaster Software) as a browser source. This stopwatch features customizable hotkeys that can be effortlessly changed either by directly editing the source code or dynamically on the page itself.

## Features

- **Customizable Hotkeys:** You can set and change your hotkeys for starting, stopping, and resetting the stopwatch.
- **Dynamic Hotkey Configuration:** Users can dynamically set hotkeys through a hidden UI on the stopwatch page.
- **Integration with OBS:** The stopwatch is designed for easy addition as a browser source in OBS.
- **Self-Hosting via GitHub Pages:** No server setup is required; the stopwatch can be accessed directly via its GitHub Pages URL.

## Live Preview

Access the stopwatch using the GitHub Pages URL: [OBS Stopwatch Browser Source](https://Wheaties466.github.io/obs-Stopwatch-browser-source)

## Customizing Hotkeys

### Through the Source Code

1. Open the `index.html` file either locally or directly on GitHub.
2. Locate the hotkey assignments section:
\```javascript
let START_HOTKEY = 'Digit1';  // Ctrl + Shift + 1
let STOP_HOTKEY = 'Digit2';   // Ctrl + Shift + 2
let RESET_HOTKEY = 'Digit3';  // Ctrl + Shift + 3
\```
3. Modify these values as per your preference. 
    - For instance, to change the start action to `Ctrl + Shift + A`, replace `'Digit1'` with `'KeyA'`.

### Dynamically on the Page

1. Navigate to the stopwatch page.
2. Press the "Change Hotkeys" button to reveal the hotkey input fields.
3. Enter the desired hotkey codes (e.g., `Digit1` for the `1` key) for the start, stop, and reset actions.
4. Press "Update Hotkeys" to save your changes.

For an exhaustive list of key values, refer to the [official key values documentation](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/key/Key_Values).

## Integration with OBS

1. In OBS, add a new 'Browser' source to your desired scene.
2. Insert the GitHub Pages URL ([https://Wheaties466.github.io/obs-Stopwatch-browser-source](https://Wheaties466.github.io/obs-Stopwatch-browser-source)) as the browser source URL.
3. Adjust width, height, and any other settings to align with your stream's design.

## Feedback and Contributions

Noticed a bug or have ideas for further enhancements? Feel free to open an issue or submit a pull request on GitHub. Your feedback and contributions are always valued!

