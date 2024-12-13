# Copilot Software Architect

## Overview

The `Copilot Software Architect` extension provides a chat participant for software professionals, specifically designed to assist with everyday tasks. Create your own architect with specific roles and assign projects which the architect can work on and complete for you. A simple example is to convert a BRD to HLD. Create an architect with specific roles, skills, etc., and assign projects.

## Features

- **DOCX to Markdown Conversion**: Convert Word documents to Markdown format.
- **High-Level Design (HLD) Creation**: Generate HLD documents based on provided context and templates.
- **Custom Architect Roles and Skills**: Complete the assigned work with your own architect configured with different roles and skills.

## Commands

- `setup`: Set up the workspace to work with the architect.
- `refreshConfig`: Refresh the workspace architect config.
- `listProjects`: List all configured active projects.
- `updateContext`: Update the chat context with selected files.
- `viewContext`: View the current chat context.
- `clearContext`: Clear the chat context.
- `help`: Display help for available commands.
- `docx2md`: Convert DOCX files to Markdown.

## Installation

### From the Marketplace

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
3. Search for `Copilot Software Architect`.
4. Click the `Install` button.

## Usage

1. Open the GitHub Copilot chat.
2. Type `@architect /setup` to set up your workspace to work with the participant.
3. Read the generated file `architectConfig.yaml` for more details.
4. Once you configure your `architectConfig.yaml`, use `@architect /listProjects` to list all configured active projects.
5. Click the follow-up link.
6. Wait until it produces the file.
7. If you need any customization on the output, modify the output template MD file.
8. Type `@architect /help` in the chat space to list available commands.
9. Pick any command that suits your work and complete it.
10. Follow the prompts to complete the task.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Change Log

All notable changes to this project will be documented in the [CHANGELOG](CHANGELOG.md) file.
