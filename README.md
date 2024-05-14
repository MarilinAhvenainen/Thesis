# Generative AI-Based Experiment Environment for Investigating Beliefs

Experiment environment for Investigating Beliefs using GPT models for contradicting opinions. To use this environment you need OpenAI account and [OpenAI API key](https://platform.openai.com/api-keys).

# Installation

To use this experiment environment you have two options. To clone the project and run it inside the Unreal Engine or use the packaged file. 

### 1. Using the project inside the engine:

- Download: `git clone https://github.com/MarilinAhvenainen/Thesis.git`
- Go to Thesis folder and run the uproject. 

Requirements for running the project in Unreal Engine:
- Unreal Engine 5.3
- Visual Studio 2022
- File Helper Blueprint Library

### 2. Using the packaged project (for Windows):
- Download the packaged project: [Packaged project](https://drive.google.com/drive/folders/1yPSlCG4qb6TWB5xXq9F_xaeTzBzFOii5?usp=share_link)
- Unzip then go to Thesis/Windows/ and run the ThesisProject_v5.exe. Prerequisite installer is included, therefore you might see following error:
  <img width="351" alt="Screenshot 2024-05-12 at 13 31 21" src="https://github.com/MarilinAhvenainen/Thesis/assets/92847897/1c931cff-c35b-47a6-9bcb-bbc4401a5f2e">
Select Yes to install.

# Usage

Before starting the experiment:
- configure settings: [Example settings (in EST)](https://docs.google.com/document/d/15e4ZpjMY6kZxR7Qw_7Dngbx0bdHKVa8ezwwCdPYiqaQ/edit?usp=sharing)
- make sure you have OpenAI API key. If you do not have one, but want to test it, then please contact the code owner.
- make sure you are connected to the internet

Shortcuts:
- F11 = exit fullscreen
- F2 = open settings in conversation view
- F7 = retry last message in conversation view and results view
- Esc = back to main menu

Saved csv files:
- Saved responses /Content/UserResponses/FormAnswers/
- Saved conversations: /Content/UserResponses/Conversations/ 

Please note that for security reasons API key will not be permanently saved. Therefore any time the application or settings view is reopened the API key must be added in the settings. Rest of the settings will be saved.

# References
- [Plugin for OpenAI API](https://github.com/KellanM/OpenAI-Api-Unreal)
- [File Helper](https://www.unrealengine.com/marketplace/en-US/product/file-helper-bp-library)
- [Font Open Sans](https://fonts.google.com/specimen/Open+Sans)
- [Google Icons](https://fonts.google.com/icons)
- [Profile images](https://commons.wikimedia.org/wiki/File:Default_pfp.jpg)

