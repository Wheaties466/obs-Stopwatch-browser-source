# OBS Stopwatch Browser Source

A simple, yet efficient stopwatch designed to be integrated into OBS (Open Broadcaster Software) as a browser source. Customizable hotkeys allow you to effortlessly control the timer during your broadcasts.

## Features

- **Customizable Hotkeys:** Set your preferred hotkeys for starting, stopping, and resetting the stopwatch.
- **Perfect Integration with OBS:** Crafted to be easily added as a browser source in OBS.
- **Hosted via GitHub Pages:** Zero server setup needed, just use the provided GitHub Pages URL.

## Live Preview

You can access the stopwatch directly via GitHub Pages: [OBS Stopwatch Browser Source](https://Wheaties466.github.io/obs-Stopwatch-browser-source)

## Customizing Hotkeys

Customizing the hotkeys is a straightforward process:

1. Open the `index.html` file either locally or directly on GitHub.
2. Find the section dedicated to hotkey assignments:
\```javascript
const START_HOTKEY = 'Digit1';  // Ctrl + 1
const STOP_HOTKEY = 'Digit2';   // Ctrl + 2
const RESET_HOTKEY = 'Digit3';  // Ctrl + 3
\```
3. Modify these values according to your preferred hotkeys. 
    - For instance, to change the start action to `Ctrl + A`, replace `'Digit1'` with `'KeyA'`.

For a comprehensive list of key values, consult the [official key values documentation](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/key/Key_Values).

## Integration with OBS

1. In OBS, add a new 'Browser' source to your desired scene.
2. Insert the GitHub Pages URL ([https://Wheaties466.github.io/obs-Stopwatch-browser-source](https://Wheaties466.github.io/obs-Stopwatch-browser-source)) as the browser source URL.
3. Tweak width, height, and any other properties to fit your stream's design.

## Feedback and Contributions

Spot an issue or have ideas for further enhancement? Feel free to open an issue or submit a pull request on GitHub. Your contributions are always appreciated!

