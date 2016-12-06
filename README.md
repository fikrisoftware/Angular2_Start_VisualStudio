# Angular2_Start_VisualStudio
# Tutorial from VISUAL STUDIO 2015 QUICKSTART -> https://angular.io/docs/ts/latest/cookbook/visual-studio-2015.html
1. Prerequisite: Install Node.js
Verify that you are running node version 4.6.x or greater, and npm 3.x.x or greater by running node -v and npm -v in a terminal/console window. Older versions produce errors.
Get installer Node.js from -> https://nodejs.org/en/download/

2. Prerequisite: Install Visual Studio 2015 Update 3
Check release note https://www.visualstudio.com/en-us/news/releasenotes/vs2015-update3-vs
Get updater from https://go.microsoft.com/fwlink/?LinkId=691129

3. Prerequisite: Configure External Web tools
Configure Visual Studio to use the global external web tools instead of the tools that ship with Visual Studio:
Open the Options dialog with Tools | Options
In the tree on the left, select Projects and Solutions | External Web Tools.
On the right, move the $(PATH) entry above the $(DevEnvDir) entries. This tells Visual Studio to use the external tools (such as npm) found in the global path before using its own version of the external tools.
Click OK to close the dialog.
Restart Visual Studio for this change to take effect.
Visual Studio will now look first for external tools in the current workspace and if not found then look in the global path and if it is not found there, Visual Studio will use its own versions of the tools.

4. Prerequisite: Install TypeScript 2 for Visual Studio 2015
Get installer from http://download.microsoft.com/download/6/D/8/6D8381B0-03C1-4BD2-AE65-30FF0A4C62DA/TS2.0.3-TS-release20-nightly-20160921.1/TypeScript_Dev14Full.exe
While Visual Studio Update 3 ships with TypeScript support out of the box, it currently doesn’t ship with TypeScript 2, which you need to develop Angular 2 applications.
To install TypeScript 2:
Download and install TypeScript 2.0 for Visual Studio 2015
OR install it with npm: npm install -g typescript@2.0.
You can find out more about TypeScript 2 support in Visual studio here -> https://blogs.msdn.microsoft.com/typescript/2016/09/22/announcing-typescript-2-0/
At this point, Visual Studio is ready. It’s a good idea to close Visual Studio and restart it to make sure everything is clean.

5. Get Source Code from https://github.com/fikrisoftware/Angular2_Start_VisualStudio
