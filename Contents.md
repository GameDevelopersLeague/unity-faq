**Where can I ask questions?**
First make sure to read #rules and #read-before-posting (optionally also #get-a-role)
For common Unity questions go to #unity-dev

**How do I install Unity?**
You need to first download Unity Hub which is used for managing different Unity versions.
You can download Unity Hub here: <https://unity.com/download>
Once you have Unity Hub installed, run it and follow the instructions.

**What version of Unity should I install?**
For starters, it is recommended that you use the Unity Hub to manage Unity installations. This tool will allow you to manage your projects and multiple intalls of Unity.
There are two main types of Unity versions available in the Hub: Tech Stream and Long-Term Support (LTS). The tech stream versions will frequently get updated with new features, but is not as stable as LTS releases. LTS releases generally do not get new features added, but are updated occasionally to fix bugs and increase stability.
If you're working in a group, everyone will need to have the same version of Unity installed.

**Do I need to know how to program to use Unity?**
Unity provides many of the tools to create games, but you will still likely need some programming experience. If you're new to programming, Unity is still very beginner friendly!
All Unity scripts use C# as their language of choice: you can learn the basics of the language here: <https://docs.microsoft.com/en-us/dotnet/csharp/>
If you aren't a fan of programming, Unity also provides a visual scripting language: <https://unity.com/products/unity-visual-scripting>

**Where do I start learning Unity?**
There are many quality tutorials on Unity to be found around the web, but a good starting place is the official Unity learning portal <https://learn.unity.com/>
If you get stuck, you can always ask for help in #unity-dev as well :)
For more links, you can go to the pinned messages of #unity-dev: https://discord.com/channels/85338836384628736/85593628650504192/812720381295067177

**What features does Unity offer?**
Unity is a Component-driven game engine for C# with a significant amount of built-in tools and functionality to get you started making your own games.
Many things such as animations, physics, sounds, and UI are included in the Unity engine. These tools can be built upon and expanded in unique ways to best fit your game.
In addition to the built-in features, the Unity Asset Store provides a way to download and purchase additional assets for use in your games: <https://assetstore.unity.com/>

**Where can I see everything Unity provides?**
Unity has excellent online manuals and scripting APIs.
Scripting APIs are available here: <https://docs.unity3d.com/ScriptReference/> and describe how to access and use Unity classes in your C# code.
Unity Manuals are available here: <https://docs.unity3d.com/Manual/> and describe how things work (without discussing the programming side of things).

**I want to make an {insert genre here} game. How do I do that?**
Unity Learn has guides for many different genres and mechanics: that's a great place to start!
The key to learning game development it to *start small*. We often try to jump headfirst into a project that is too ambitious and get burnt out.
A good first step is to make a clone of a simple game that is similar to what you want to make. Common suggestions include Pong, Breakout, and other Atari favorites!

**How do I fix {insert error here}?**
Chances are, if you're running into a problem/error then someone else has too. The Unity Answers board (<https://answers.unity.com>) is a great place to search for specific errors.
If you can't find your answer online, post a question in #unity-dev with a detailed description of what you're trying to do, what's currently happening, and the error message itself (if applicable).

**I'm looking for a package in the Package Manager and it's not there. Why is that?**
Many packages that would normally appear in the Package Manager are marked as "Preview Packages", which are hidden by default.
You can enable Preview Packages by following these steps: <https://docs.unity3d.com/Manual/class-PackageManager.html> (under the heading "Advanced Settings > Enable Preview Packages")

**Can I view the Unity source code?**
Unity is closed-source, meaning that while we can *use* their classes and code, we can't *see* how those things are implemented.
However, Unity has made their C# bindings of the C++ engine code public, and it is available here: <https://github.com/Unity-Technologies/UnityCsReference>
This is sometimes useful if you can't figure out how something works, and it is poorly documented online.
