# Julia

## Summary

*Develop Julia applications.*

| Metadata | Value |  
|----------|-------|
| *Contributors* | [David Anthoff](https://github.com/davidanthoff) & [Thomas Hagebols](https://github.com/ThomasHagebols) |
| *Definition type* | Image |
| *Works in Codespaces* | Yes |
| *Container host OS support* | Linux |
| *Languages, platforms* | Julia |

## Using this definition with an existing folder

### Optional Configuration:

While the definition itself works unmodified, you can select the version of Julia the container uses by updating the `VARIANT` arg in the included `.devcontainer/devcontainer.json` file.

```json
"args": { "VARIANT": "1.5" }
```

### Adding the definition to your project

Just follow these steps:

1. If this is your first time using a development container, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started) to set up your machine.

2. To use VS Code's copy of this definition:
   1. Start VS Code and open your project folder.
   2. Press <kbd>F1</kbd> select and **Remote-Containers: Add Development Container Configuration Files...** from the command palette.
   3. Select the Dart definition.

3. To use latest-and-greatest copy of this definition from the repository:
   1. Clone this repository.
   2. Copy the contents of this folder in the cloned repository to the root of your project folder.
   3. Start VS Code and open your project folder.

4. After following step 2 or 3, the contents of the `.devcontainer` folder in your project can be adapted to meet your needs.

5. Finally, press <kbd>F1</kbd> and run **Remote-Containers: Reopen Folder in Container** to start using the definition.

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the MIT License. See [LICENSE](https://github.com/Microsoft/vscode-dev-containers/blob/master/LICENSE).