# ROMs Folder

Place your GBA ROM files (`.gba` or `.zip`) in this folder.

## How to Add ROMs

1. Place your ROM files in this folder
2. Update the `ROM_LIST` array in `index.html` with your ROM filenames
3. The ROMs will appear as buttons on the left side of the page

## Example Configuration

In `index.html`, update the ROM_LIST:

```javascript
const ROM_LIST = [
    { name: 'Game 1', file: 'game1.gba' },
    { name: 'Game 2', file: 'game2.gba' },
    // Add more ROMs here
];
```

## Legal Notice

Only place ROM files that you legally own or have permission to use.
