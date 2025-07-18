Modular Admin Command System for Roblox
A powerful, scalable, and easy-to-use admin command system built for any Roblox game. This system is designed with a modular architecture, allowing you to add, remove, or edit commands without ever touching the core handler script. It's perfect for game moderation, testing, and administration.

Why Use This System?
Many admin systems are either too simple, forcing you to write all your code in one massive script, or too complex and hard to configure. This system strikes the perfect balance by being both powerful and incredibly easy to maintain.
Clean & Organized: Each command is its own self-contained ModuleScript.

Scalable: Add hundreds of commands without cluttering your workspace.
Permission-Based: Easily control who can use which commands with a simple configuration file.
Efficient: The system is lightweight and optimized for performance.

File Structure
To install the system, organize your scripts in ServerScriptService exactly like this:

ServerScriptService
└── AdminSystem (Folder)
    ├── AdminCore (Script)
    ├── Config (ModuleScript)
    └── Commands (Folder)
        ├── kick (ModuleScript)
        ├── kill (ModuleScript)
        ├── tp (ModuleScript)
        └── ... DO YOU NEED OTHER MODULES? IF SO, ADD AS MANY AS YOU REQUIRE

NOTE:
Admin loaders are composed of admin modules, which are small containers used to create interactive features, from a local or server side perspective.
Server side scripting is the most secure, handling local scripts however, means using extra code that can interact with the single user experience, not for all the other players.
That means that if used correctly, it can boost staff usage, by using less server-side calculations and memory usage, and more on the player side, which would balance overall client-server communication.
