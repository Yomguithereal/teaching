# How to make sure your computer is terminal-ready?

## You are on Linux (Ubuntu, Debian, CentOS, etc.)

You are already good to go!

## You are on MacOS

1. Open a terminal by searching for "terminal" in the launchpad (or follow this little [guide](https://support.apple.com/guide/terminal/open-or-quit-terminal-apd5265185d-f365-44cb-8b09-71a064a42125/mac)).
2. Make sure MacOS Developer Tools are installed by executing the following command (you can copy-paste and hit enter):

```bash
xcode-select --install
```

This will probably open a prompt asking for confirmation. Be sure to have a proper Internet connection as this installation will require to download some variable amount of data.

When this terminates, you can close the terminal, your computer is ready.

## You are on Windows

Unfortunately, Windows chose to do things differently than every single other operating system on earth, so we need to install the [Window Subsystem for Linux](https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux) (abbreviated `WSL`), to be able to access a proper [UNIX shell](https://en.wikipedia.org/wiki/Unix_shell).

To install `WSL` on your Windows machine, follow those steps:

1. Open `Powershell` by searching for it in your desktop toolbar.
2. Execute the following command (you can copy-paste and hit enter):

```bash
wsl --install
```

Be sure to have a proper Internet connection.

When the installation completes (it might ask you for authorization and prompt some questions), reboot your computer.

Then, you should be able to find a penguin icon when searching for `WSL` in your desktop toolbar search.

If said penguin is present, your computer is ready.

## You are on Windows but cannot install WSL

Come and see me. We will find a solution.