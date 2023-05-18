# autoCopy

A script for keeping multiple folders up to date with a master folder 

## Usage
Just run the script.
```bash
  python autoCopy.py
```

## Config
After running the script it will generate a file called ` autoCopyConfig.json ` where the settings are stored.

```json
{
    "folderToTrack": "path/to/folder",
    "ignoreList": [".git"],
    "copyTo": ["path/to/copy/1", "path/to/elsewhere"]
}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `"folderToTrack"` | `string` | **Required**. Path to your master folder |
| `"ignoreList"` | `list[string]` | Files to ignore |
| `"copyTo"` | `list[string]` | **Required**. List of folders to copy the contents of master to |

## Contributing

Contributions are always welcome!
Just fork the repo and create a pull request and if it adds functionality/deemed usefull it will probably get accepted.
