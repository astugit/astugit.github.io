# Global Capslock Key

A synchronized global capslock key, hosted at [astutillo.me/capslock.html](https://astutillo.me/capslock.html).

## What is this?

By using this client YOU CAN SYNCHRONIZE YOUR CAPS LOCK STATE with everyone else USING THIS CLIENT.

WHENEVER I PRESS CAPSLOCK it is pressed for you and VICE-VERSA.

NO MORE DISAGREEING ABOUT WHEN TO USE CAPS LOCK!

Now we can all share a SINGLE KEY!

## How to run the client

### Prerequisites

- Python 3.12+
- On Linux: Install `xdotool` using your package manager

### Installation

1. Clone this repository or download the files
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the client:
   ```bash
   python client.py
   ```

### Using uv (alternative)

If you use [uv](https://github.com/astral-sh/uv):

```bash
uv run client.py
```

## Supported Platforms

- macOS
- Windows
- Linux (requires `xdotool`)

## Credits

Based on [global-capslock](https://github.com/nolenroyalty/global-capslock) by [eieio](https://eieio.games).

## License

MIT License - see [LICENSE](LICENSE) for details.
