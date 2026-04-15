# Data Organization in Linux

<img src="../svg/linux-svgrepo-com.svg" width="100" height="100">

## Introduction

In Linux, information is managed through a file system based on files and folders.

![Linux, Nautilus](linux-find-files-nautilus.webp)

## Basic Concepts

- `File`: A unit that stores content, such as text, images, audio, or video.
- `Folder`: A container that holds files and other folders.
- `Path`: The location string showing where a file or folder is stored.
- `Home folder` (`home`): The user's personal folder, often represented as `~`.

## Main Directories in Linux

- `Home` (`~`): User's personal data.
- `Documents`: Projects, reports, and other work files.
- `Downloads`: Files downloaded from the internet.
- `Pictures`, `Music`, `Videos`: Media storage folders.
- `Desktop`: Temporary files you need quick access to.

## Workflow for Handling Data

1. Open **Files** (file manager, such as Nautilus, Dolphin, or Thunar).
2. Create a new folder for each project.
3. Move files into the correct folders using drag-and-drop.
4. Rename files with descriptive names, for example `project-math-2026.pdf`.
5. Use search in the file manager to find files quickly.
6. Delete unnecessary files and empty Trash when you are sure.

## Best Practices

- Use one main folder for each project or course.
- Avoid storing permanent files on `Desktop`.
- Use consistent and clear file and folder names.
- Back up data regularly to an external drive or cloud storage.

### Overview: Working with Data in Linux

- **Files:** Main tool for browsing, moving, and organizing files.
- **Home folder (`~`):** Contains your personal folders.
- **Search:** Quickly finds files by full or partial name.
- **Drag-and-drop:** Easy way to move or copy files between folders.
- **Trash:** Files go here first before permanent deletion.

### Important Terms

- **Permissions:** Control who can read, edit, or execute files.
- **Backup:** Regular copies that protect data from loss.

## Summary

Good data organization in Linux relies on three key things: proper folder structure, clear naming, and regular backups.

## Submitting Assignments in Inna

#### All assignments must be submitted in Inna.

Example: All files for Assignment 1 are placed in one folder and compressed into a **.zip file**.

### How to Compress Data into One `.zip` File

#### Option 1: Using a File Manager (GUI)

1. Open **Files** and locate the folder/files you want to submit.
2. Select the content to include in the `.zip` file.
3. Right-click the selected content and choose **Compress...** (name may vary by Linux distribution).
4. Select the `zip` format.
5. Choose a file name, for example `Assignment-1.zip`, and save.

#### Option 2: Using Terminal

1. Open **Terminal**.
2. Go to the correct folder, for example:

```bash
cd ~/Documents
```

3. Compress the folder into `.zip`:

```bash
zip -r Assignment-1.zip Assignment-1/
```

4. After running the command, `Assignment-1.zip` will be in the same folder.

### Good to Remember

- Put the full assignment into **one folder** before compressing.
- Rename the `.zip` file clearly before submission, for example `Name-Assignment1.zip`.
- To extract a `.zip` file in Linux, double-click it or use the `unzip` command in Terminal.
