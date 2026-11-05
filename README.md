# Ascent Mapper

Ascent Mapper is a desktop app for building and reading program logic models: the
network of inputs, activities, outputs and outcomes, the evidence behind each link,
the people around the program, and what changes when its inputs or policies do.

This repository holds the Mac installers. **Download them from
[Releases](https://github.com/Ascent-Evaluation/ascent-mapper/releases).** On Windows,
get the app from the [Microsoft Store](https://apps.microsoft.com/detail/9npq9tj2lvnh).

## Which file to download

| Your computer | Download |
|---|---|
| Mac with Apple silicon (M1 or later) | `Ascent-Mapper-<version>-arm64.dmg` |
| Mac with an Intel processor | `Ascent-Mapper-<version>-x64.dmg` |
| Windows PC | [Microsoft Store](https://apps.microsoft.com/detail/9npq9tj2lvnh) |

A release's `.zip`, `.blockmap` and `latest-mac.yml` files are for the app's automatic
updates. You don't need to download them.

Not sure which Mac you have? Choose **Apple menu → About This Mac**. A line reading
**Chip** means Apple silicon; **Processor** means Intel.

Ascent Mapper needs **macOS 12 Monterey or later**, or **64-bit Windows 10 or later**.

## Installing

**On a Mac**

1. Open the `.dmg` and drag **Ascent Mapper** into **Applications**.
2. Open Ascent Mapper from Applications. The first time, macOS asks you to confirm
   opening an app from the internet; click **Open**.

From version 1.1.0 the app is signed and notarized, so macOS opens it without a
security warning.

**On Windows**

Install Ascent Mapper from the
[Microsoft Store](https://apps.microsoft.com/detail/9npq9tj2lvnh). School- or
work-managed computers may block the Store; if so, ask your IT team.

## Updates

From version 1.1.0 the Mac app updates itself. The Microsoft Store updates the Windows
app.

If you downloaded version 1.0.0 or earlier from this page, download a newer version
once by hand: from Releases on a Mac, or the Microsoft Store on Windows.

## Your files

Ascent Mapper saves each model as an `.ascent` file, in **Documents/ProgramModels**
unless you choose somewhere else. Double-click an `.ascent` file to open it. Models
saved as `.json` by earlier versions open with **Open…**.
