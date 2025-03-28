# Wubby VOD Downloader (aka Wubby Snatch)

A simple script to snatch those autism VODs from the Wubby TV archive, for when you need to grab the best of the chaos.

## Install this ADHD-fueled masterpiece

Install this package from PyPI using `pip`:

```bash
pip install wubby-vod-downloader==1.1.0
```

## Usage

Navigate to the directory where you want to store your VODs. The script will create a new folder named `vod_downloads` where the files will be saved.

Run the command to download your desired VODs:

```bash
wubby-snatch month -c <number_of_vods>
```

## Arguments

Month: Specify the month in `MMM_YYYY` format (e.g., `mar_2025`) from which you want to download VODs.

-c <number_of_vods>: Specify how many VODs you want to download. For example, `-c 5` to download the 5 most recent VODs.

## Example

```bash
wubby-snatch mar_2025 -c 5
```

This will download the 5 most recent VODs from March 2025.

## Skipping Already Downloaded VODs

The script will check if VODs have already been downloaded and skip them

## Important

After installing via pip, if you get a warning about `wubby-snatch` not being in PATH, you can add `~/.local/bin` to your PATH manually.

This typically happens on Linux systems. You can add it by running:

```bash
export PATH="$HOME/.local/bin:$PATH"
```

Add this line to the end of your .`bashrc` or `.zshrc` file to make it permanent.

License
This project is licensed under the MIT License - see the LICENSE file for details if you care.
