# Introduction

This is a demo project for Sim Agents

# Installation

1. Follow instructions to Install LFS from: https://help.github.com/articles/installing-git-large-file-storage/
2. Clone repository using following command: `git clone https://github.com/believable-agents/sim-agents --recursive`
3. Checkout all modules with:

```
git submodule init
git submodule update
```

4. Download Nodecanvas 2.6.2 from Asset Store
5. Download DO Tween from Asset Store
6. Delet Assets/Scripts/Reordable-List/DEMO to eliminate compilation error

# Reusing modules

If you want to use any of the modules from this project you can add them as a submodule from GIT:

```
git submodule add https://github.com/believable-agents/sim-agents-unity Assetscripts/reordable-list/Scripts/sim-agents-unity
...                                                                                                                              or-unity Assets/Scripts/reordable-list
```

This project uses following submodules:

```	
path = Assets/Scripts/interactive-objects
	
url = https://github.com/believable-agents/interactive-objects
path = Assets/Scripts/agents-core
	
url = https://github.com/believable-agents/agents-core
path = Assets/Scripts/agents-unity
	
url = https://github.com/believable-agents/agents-unity
path = Assets/Scripts/sim-agents
	
url = https://github.com/believable-agents/sim-agents	
path = Assets/Scripts/sim-agents-unity
	
url = https://github.com/believable-agents/sim-agents-unity
path = Assets/Scripts/reordable-list
	
url = https://bitbucket.org/rotorz/reorderable-list-editor-field-for-unity
```