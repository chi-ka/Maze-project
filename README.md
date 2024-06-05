ze Project
(3D Raycaster Game Project)


Team:

Name: Chika Ugonna Okafor
Role: Lead Developer, Gameplay Designer, Graphics and Texture Artist, Sound Designaer  
Reason:  Chika has experience in game development and an understanding of raycasting techniques.She  is also  skilled in designing engaging and intuitive gameplay mechanics, ensuring the game is fun and accessible for players. She has Knowledge of digital art, texture mapping, and creating immersive audio experiences and will be responsible for developing the game's sound effects and music.

Technologies:


Libraries, Languages, and Frameworks:
Python: Primary programming language for implementing raycasting logic.
Pygame: Library for handling graphics, input, and game loop.
OpenGL: For advanced rendering and graphical effects.
Blender: For creating 3D models and textures.
Audacity: For editing and creating sound effects and music.
Platforms:
 PC (Windows, Linux)
Hardware:
 Development PCs
Books and Resources:
SDL2  Get started Graphics programming
Lazy Foo Productions Beginning Game Programming
RayCasting Tutorial By permadi


Technology Choices and Tradeoffs:
Python vs. C++
 Python was chosen due to its ease of use, which allows for quicker iteration and development, making it more suitable for our team's skill set and project timeline.
Pygame vs. Unity
Pygame was chosen due to its simplicity and alignment with our project's scope and requirements. It allows us to stay within the Python ecosystem, leveraging our team's existing knowledge and resources. Although Unity was Considered for its powerful game development capabilities, including a robust editor and support for 3D graphics. However, it requires learning C# and might be overkill for a project focused on raycasting.

Challenge:

Problem the Portfolio Project is Intended to Solve:

The Portfolio Project aims to demonstrate the practical application of raycasting in creating an immersive 3D gaming experience. It showcases the team's ability to develop a functional 3D game using raycasting technology, highlighting skills in game development, programming, graphic design, and sound design.

What the Portfolio Project Will Not Solve:
The project is not intended to solve advanced 3D rendering challenges found in AAA games, nor will it address highperformance optimization for largescale multiplayer environments.
Who the Portfolio Project Will Help and/or Who the Users Will Be:
Aspiring Game Developers
Students and Educators

Relevance or Dependency on a Specific Locale:
The project is relevant to anyone interested in game development, regardless of their geographic location  provided they have the necessary hardware and software to run the game.



Risks
Technical Risks:
Performance Issues:
Potential Impact: Slow/Unresponsive gameplay, especially on lower-end hardware.
Safeguards/Alternatives: Optimize code by using efficient algorithms and data structures. 
Complexity of Raycasting Implementation:
Potential Impact: Delays in development due to lack of  proper understanding.
Safeguards/Alternatives: Follow the raycasting tutorial closely and break down the implementation into manageable steps. 
Graphics Rendering Issues:
Potential Impact: Rendering errors that detract from the gameplay experience.
Safeguards/Alternatives: Utilize OpenGL for advanced rendering.
Non-Technical Risks:
Scope Creep:
Potential Impact: The project may become too ambitious, leading to unfinished features or an incomplete game.
Strategies: Define a clear project scope and prioritize core features. 
Resource Availability:
Potential Impact: Limited access to necessary hardware or software can delay development.
Strategies: Ensure the team has the required resources at the start of the project. 

Infrastructure
Branching and Merging Process:
The team will use GitHub Flow for managing our codebase.
Deployment Strategy:
Initially, the game will be tested locally on development PCs to ensure core functionality and stability. Upon reaching significant milestones, we will create tagged releases in the GitHub repository.Distribution: The game will be distributed via GitHub.
Populating the App with Data:
Game Assets: All game assets, including textures, models, and sounds, will be created and integrated using Blender and Audacity. These assets will be versioned and stored in the repository.
Level Data: Levels will be designed using a combination of external tools (like Blender for map design).
Configuration Files: JSON files will be used to store configuration data such as game settings, level parameters, and other customizable options.
Testing Tools, Automation, and Processes:
Automated Testing: Unit tests will be written for critical components of the game using Python's unittest framework. 
Continuous Integration (CI): I will set up a CI pipeline using GitHub Actions to automatically run tests and build the project on each push to the repository. 
Manual Testing:I will perform extensive manual testing to identify and report bugs.

Existing Solutions

Similar Products or Solutions:
Wolfenstein 3D
Similarities: Wolfenstein 3D is one of the earliest examples of a game that uses raycasting to render a 3D environment. Like our project, it employs 2D textures on 3D surfaces and uses a first-person perspective.
Differences: Wolfenstein 3D has a fixed set of levels and a pre-defined storyline. Our project will focus more on the technical demonstration of raycasting and may include additional gameplay mechanics and dynamic level generation.
Reimplementation of Proven Solutions:
We intend to reimplement the basic principles of raycasting used in early 3D games like Wolfenstein 3D and Doom.
 
