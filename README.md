🤍How to setup ModCoderPack to 1.12.2 using gradle compiler, in intellijIdea.

1-Step: Download the ModCoderPack

![LinkedIn](https://img.shields.io/badge/-mcp-090909?style=for-the-badge&logo=java&logoColor=007BB)


2-Step: Download the 1.12.2-srg


![LinkedIn](https://img.shields.io/badge/-srg-090909?style=for-the-badge&logo=java&logoColor=007BB)

3-Step: Download the 1.12. Minecraft version(.minecraft folder version).

4-Step: run "Decompile.bat", and wait progress

5-Step: Download the intellijIdea version no high to 2021.3.3

![LinkedIn](https://img.shields.io/badge/-intellij-090909?style=for-the-badge&logo=java&logoColor=007BB)

6-Step: Create new project on itellij java -> gradle, and create new project

7-Step: Create folders in you gradle folder intellij -> natives, libraries, "run".

8-Step: in intellij open "build.gradle", and typing near testImplementation type ->

 implementation fileTree('libraries')

 9-Step: open mcp folder, and open "jar" folder, copy assets folder.

10-Step: open folder run, and paste you folder assets

11-Step: Open mcp folder, and open jars folder, and open 1.12.2, open 1.12.2-natives -> copy all, and paste this resources to gradle folder (intellij) "natives" and paste you files

12-Step: open in you mcp folder, open folder src -> minecraft, and paste all, and open in gradle folder (intellij), and open folder src -> java -> main, and paste this you files.

13-Step: Create run-option in itellij, and name this option is "Start" -> -Djava.library.path=../natives in vm options.

14-Step: Run start, and you client is running.

Maybi i created post -> how to code moduleBase on 1.12.2 Mod Coder Pack later.

AllLinks:

MCP -> http://www.modcoderpack.com/

SRG -> http://files.minecraftforge.net/maven/de/oceanlabs/mcp/mcp/1.12.2/mcp-1.12.2-srg.zip

INTELLIJ IDEA COMMUNITY -> https://www.jetbrains.com/idea/download/other.html?ysclid=l3eudii07c

Bye, bye, bye.