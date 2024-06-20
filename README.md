# Just For WeRead

## Shortcuts
| Mac                         | Windows/Linux                  | Function                      |
| --------------------------- | ------------------------------ | ----------------------------- |
| <kbd>⌘</kbd> + <kbd>[</kbd> | <kbd>Ctrl</kbd> + <kbd>←</kbd> | Return to the previous page   |
| <kbd>⌘</kbd> + <kbd>]</kbd> | <kbd>Ctrl</kbd> + <kbd>→</kbd> | Go to the next page           |
| <kbd>⌘</kbd> + <kbd>↑</kbd> | <kbd>Ctrl</kbd> + <kbd>↑</kbd> | Auto scroll to top of page    |
| <kbd>⌘</kbd> + <kbd>↓</kbd> | <kbd>Ctrl</kbd> + <kbd>↓</kbd> | Auto scroll to bottom of page |
| <kbd>⌘</kbd> + <kbd>r</kbd> | <kbd>Ctrl</kbd> + <kbd>r</kbd> | Refresh Page                  |
| <kbd>⌘</kbd> + <kbd>w</kbd> | <kbd>Ctrl</kbd> + <kbd>w</kbd> | Hide window, not quite        |
| <kbd>⌘</kbd> + <kbd>-</kbd> | <kbd>Ctrl</kbd> + <kbd>-</kbd> | Zoom out the page             |
| <kbd>⌘</kbd> + <kbd>+</kbd> | <kbd>Ctrl</kbd> + <kbd>+</kbd> | Zoom in the page              |
| <kbd>⌘</kbd> + <kbd>=</kbd> | <kbd>Ctrl</kbd> + <kbd>=</kbd> | Zoom in the Page              |
| <kbd>⌘</kbd> + <kbd>0</kbd> | <kbd>Ctrl</kbd> + <kbd>0</kbd> | Reset the page zoom           |

<detail>
In addition, double-click the title bar to switch to full-screen mode. For Mac users, you can also use the gesture to go to the previous or next page and drag the title bar to move the window.
</detail>

## Before starting

1. **For beginners**: Play with Popular Packages to find out Pake's capabilities, or try to pack your application with [GitHub Actions](<https://github.com/tw93/Pake/wiki/Online-Compilation-(used-by-ordinary-users)>). Don't hesitate to reach for assistance at [Discussion](https://github.com/tw93/Pake/discussions)!
2. **For developers**: “Command-Line Packaging” supports macOS fully. For Windows/Linux users, it requires some tinkering. [Configure your environment](https://tauri.app/v1/guides/getting-started/prerequisites) before getting started.
3. **For hackers**: For people who are good at both front-end development and Rust, how about customizing your apps' function more with the following [Customized Development](#development)?

## Development

Prepare your environment before starting. Make sure you have Rust `>=1.63` and Node `>=16` (e.g., `16.18.1`) installed on your computer. For installation guidance, see [Tauri documentation](https://tauri.app/v1/guides/getting-started/prerequisites).

If you are unfamiliar with these, it is better to try out the above tool to pack with one click.

```sh
# Install Dependencies
npm i

# Local development [Right-click to open debug mode.]
npm run dev

# Pack application
npm run build
```