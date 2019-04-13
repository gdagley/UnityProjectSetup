Unity Project Structure
=======================

This is the structure I use for any new Unity project I start.

```
_Game
    Animation
    Art
        Materials
        Models
        Sprites
    Audio
        Music
        Sounds
    Editor
    Fonts
    Prefabs
    Scenes
        TestScenes
    Scripts
        Game
        Managers
        UI
        Utilities
    Settings
```

## Usage

The are multiple ways you can use this project:

* Clone this project and copy the folder into your new Unity project, 
* Use the commands in the `create_project_structure.sh` file
* Copy the `create_project_structure.sh` into your `Assets` folder and run it with 

    ``` text
    sh create_project_structure.sh
    ```

###  Note

The `.gitkeep` files are placeholders to make sure the directory structure remains when using `git` (see https://fileinfo.com/extension/gitkeep for more info).  You can delete those files when you have other files in the directories that will maintain the directory structure.