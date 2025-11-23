![GitHub repo size](https://img.shields.io/github/repo-size/mg0x7BE/rename-all-files)
![GitHub License](https://img.shields.io/github/license/mg0x7BE/rename-all-files)
![GitHub Created At](https://img.shields.io/github/created-at/mg0x7BE/rename-all-files)
![GitHub forks](https://img.shields.io/github/forks/mg0x7BE/rename-all-files)
![GitHub Repo stars](https://img.shields.io/github/stars/mg0x7BE/rename-all-files)

# RenameAllFiles

Batch rename files by replacing string in filenames.

## Usage

```bash
RenameAllFiles.exe searchString replaceString [CONFIRM]
```

Without `CONFIRM`, shows preview only.

## Example

```bash
RenameAllFiles.exe old new
```

Preview:
```
old_file.txt -> new_file.txt
another_old.txt -> another_new.txt
```

Execute:
```bash
RenameAllFiles.exe old new CONFIRM
```

## Notes

- Case-insensitive search
- Current directory only (no subdirectories)

## License

[Unlicense](LICENSE)
