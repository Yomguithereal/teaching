# Installing xan

## 1. Make sure your computer is terminal-ready

You can do so by following [this](./INSTALL.md) guide (especially if you are using MacOS or Windows).

## 2. Install necessary dependencies

If you are on Ubuntu or WSL (Windows), run the following command in your terminal:

```bash
sudo apt install build-essential
```

It will ask you for your password.

If you are on MacOS, you have nothing to do. If you are on another Linux distribution, I'll assume you already know what to do.

## 3. Install the rust compiler & cargo

By pasting and executing the following command in your terminal:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Then close and restart your terminal

## 4. Install `xan`

By running:

```bash
cargo install xan
```

Then run:

```bash
xan
```

and you should see some summary of the command appear.

Congratulations, you are ready!