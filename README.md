# ScriptTool
This is my own custom script to help my daily development life.
Right now just support `Dcard Project`

## gita [arg] 
> git add
- ` `: add all file but Stetho-related files
- `-a`: add all dcard files
- `-s`: add dcard screen files
- `-r`: add dcard resrouces files
- `-m`: add dcard module files

## gitc [arg]
> git checkout staged files
- `-s`: checkout dcard screen files
- `-r`: checkout dcard resource files
- `-m`: checkout dcard module files
- `-i`: checkout `.idea/codeStyles/Project.xml` & `.idea/modules.xml`

## gc [agr]
> git commit
- `args`: your commit message

## mvres [source] [target]
> more the drawable files from `designer source folder` to `project folder`
- `source`: designer source folder which contain all the drawable-xxx folder
- `target`: project folder which contain the `src` folder in project. NOT project root folder.

## adbip
> get connected device ip (only work when there is one device connected)

## adbw
> setup wifi port connected to adb (only work when there is one device connected)

## uapk (WIP)
> upload apk to slack channel

# Reference
- [How to Create and Use Bash Scripts](https://www.taniarascia.com/how-to-create-and-use-bash-scripts/)
- [Writing Your First Script and Getting It to Work](http://linuxcommand.org/lc3_wss0010.php)
