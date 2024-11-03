# Episode Renamer

A simple script to rename episodes in a folder and delete any unnecessary text or image files.

## Usage

```python

# gathers user requirements for series and episode num and returns the formatted name
user_input()

# creates two lists: a video list for videos which need to be renamed, and a deletion list for txt or img files
make_file_list()

# renames the video files
rename_files(file_list, name_format, episode_format)

# deletes the img and txt files on the list
delete_files(deletion_list)
```

## Contributing

Pull requests are welcome.