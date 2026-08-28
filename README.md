# Empty Copy

Copy to **RAM**<br>
**Paste** to <u>*disk*</u>

#### Warning
<code>RAM works as long as the computer is turned on — beware of data loss.</code>

### What is
It is a simple bash script for Linux that copies file(s) or folder(s) to RAM, which can then be pasted at any time to any device connected to the computer. Be careful, though, because RAM only retains data as long as the computer is turned on. **Not recommended for important data**

### Explain
Many times, unnecessary system transfers take place, or files are copied that could simply be put into RAM. Or even, when we have only one free USB port and a 5 GB file that we want to move to another *external drive*, what do we do? We copy the file to the *internal drive*, then disconnect *external drive 1*, plug in *external drive 2*, and transfer it. That's a simple way to avoid completely unnecessary disk writes and prevent its health from degrading. Of course isn't so important for your disk health but is a hobby script.

### Setup
*Plug-and-Play* - no install<br>
<code>empycopy.sh copy  <path1,path2,...>       # copy to RAM          
empycopy.sh paste <file path>                        # paste to RAM       
empycopy.sh status                      # show clipboard          
empycopy.sh clear                      # clean clipboard          
empycopy.sh lang  el|en                # language change</code>
<br>**As parameters:**<br>
<code>--en / --el    use this language for this run only</code>

### Download
[Github Release](https://github.com/FANDCS/Empty_Copy/releases)

### Credits
- As small and quick script is written by [Claude Sonnet 5](https://claude.ai)
- Developer: [Android_Creator](https://github.com/AndroidCreator5)
