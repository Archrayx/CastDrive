# Cast Drive

**Read and write files on an ext4 USB drive from Android, without rooting your phone.**

Cast Drive started with a Raspberry Pi, a 2 TB game library, and a simple problem: the files were already on the drive, but my phone couldn't use them. I wanted to plug the drive into my phone and pick up where I left off. That's what I built Cast Drive for.

[Official website](https://castdrivetech.com) · [Explore the features](https://castdrivetech.com/features) · [Report a problem](https://github.com/Archrayx/CastDrive/issues/new/choose)

## Try it with your own drive

1. Connect a supported USB drive to your Android phone, open Cast Drive, and grant USB access when prompted.
2. Open the ext4 partition. Browse its folders or search for a filename or extension such as `.iso`.
3. To use a file in a compatible app, open that app's Android file picker and select the folder exposed by Cast Drive. Your library can stay on the external drive.

## What else can I do?

- **Manage files:** Copy or move files between supported locations. For eligible transfers, you can verify the destination before deleting the original on a Move.
- **Find your way back:** Save frequently used folders in Quick Access and use Drive History to revisit earlier scans.
- **Work with the drive itself:** Back up a drive image or grow a supported GPT/ext4 partition when it has adjacent unallocated space. Resize is grow-only and requires a compatible ARM64 device on Android 11 or later. Back up before resizing.

Some features require Pro. See the [feature guide](https://castdrivetech.com/features) for details.

## Get Cast Drive

Visit [castdrivetech.com](https://castdrivetech.com) for current availability. There is no APK attached to this repository yet. GitHub's **Download ZIP** downloads these project notes; it does not install the Android app.

## Testing something?

I'd especially like to hear what happens with your own phone and drive. If a folder doesn't appear in another app, tell me whether you can open that same folder inside Cast Drive. That one detail helps narrow down the problem. [Send a bug report or suggest an improvement](https://github.com/Archrayx/CastDrive/issues/new/choose).
