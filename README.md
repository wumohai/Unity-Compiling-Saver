## Unity Compiling Saver

A tool to save Unity project compiling time.

Simply move all the stable scripts into [Standard Assets][http://docs.unity3d.com/Manual/ScriptCompileOrderFolders.html] folder to avoid recompile them every time. Can save massive time if you use a lot of third party libs.

If your library code depends on the code file position in your project(That barely happens), don't optimize them.

#### How to use

1. Copy the CompilingSaver folder into your project. 
2. Select the folders you want to optimize.
3. Click menu item Assets-Optimize Compiling Time.



---------------------

Inspired by the idea of [Mad Compile Time Optimizer][https://www.assetstore.unity3d.com/en/#!/content/34012]. (Never saw the code in that plugin, a little expensive for me:)

