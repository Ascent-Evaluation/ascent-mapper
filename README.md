# Ascent Mapper

Ascent Mapper is a desktop app for building and reading program logic models: the
network of inputs, activities, outputs and outcomes, the evidence behind each link,
the people around the program, and what changes when its inputs or policies do.

This repository holds the app's installers. **Download them from
[Releases](https://github.com/Ascent-Evaluation/ascent-mapper/releases).**

## Which file to download

| Your computer | Download |
|---|---|
| Mac with Apple silicon (M1 or later) | `Ascent-Mapper-<version>-arm64.dmg` |
| Mac with an Intel processor | `Ascent-Mapper-<version>-x64.dmg` |
| Windows PC | `Ascent-Mapper-Setup-<version>.exe` |

Not sure which Mac you have? Choose **Apple menu → About This Mac**. A line reading
**Chip** means Apple silicon; **Processor** means Intel.

Ascent Mapper needs **macOS 12 Monterey or later**, or **64-bit Windows 10 or later**.

## Installing

Ascent Mapper is not yet signed, so your computer will warn you before opening it the
first time. You only have to get past this once.

**On a Mac**

1. Open the `.dmg` and drag **Ascent Mapper** into **Applications**.
2. Open Ascent Mapper from Applications. macOS says it could not verify the app;
   click **Done**.
3. Open **System Settings → Privacy & Security**, scroll down to the message about
   Ascent Mapper, and click **Open Anyway**. Confirm with your password, then
   **Open**.

On macOS 14 or earlier you can instead Control-click the app in Applications, choose
**Open**, then **Open** again.

**On Windows**

1. If your browser says the file isn't commonly downloaded, choose to keep it.
2. Run the installer. If **Windows protected your PC** appears, click **More info**,
   then **Run anyway**.

Ascent Mapper installs for your account only, without needing administrator rights.
School- or work-managed computers may block unsigned apps entirely; if so, ask your
IT team.

## Your files

Ascent Mapper saves each model as an `.ascent` file, in **Documents/ProgramModels**
unless you choose somewhere else. Double-click an `.ascent` file to open it. Models
saved as `.json` by earlier versions open with **Open…**.
