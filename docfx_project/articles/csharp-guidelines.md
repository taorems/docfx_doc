# C# Guidelines
## General
- Use four spaces of indentation (no tabs!)
- Avoid `this`, unless necessary
- Use async/await for any operations that include I/O (e.g reading/writing to a disk, database/network calls, etc)

## Validation
- Use FluentValidation to guard client input (e.g on API's)
- Use built-in argument checks for all method parameters

## Commenting
- Use XML comments on all classes and public methods
- Don't use comments for obvious logic

## Code Snippet
- Add code snippet by using this command
[!code-csharp[] (../src/calculator.cs#L8-L13)]

## Images
- Image can be added using this command
[!<alt-text>](../images/image_syntax.jpg)