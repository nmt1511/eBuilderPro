# eBuilderPro - Claude Code Project

## Project Overview
eBuilderPro is an ASP.NET Core web application for building management and construction project management.

## Development Commands

### Run the project
```bash
dotnet run
```

### Build the project
```bash
dotnet build
```

### Test the project
```bash
dotnet test
```

## Project Structure
- `Program.cs` - Entry point and application configuration
- `Pages/` - Razor Pages for the UI
- `wwwroot/` - Static files (CSS, JS, images)
- `appsettings.json` - Configuration settings
- `ebuilderpro.csproj` - Project file

## Git Workflow
- Branch from `main`
- Create feature branches for new work
- Pull requests must pass CI checks
- Squash and merge on completion

## Code Style
- Follow C# coding conventions
- Use nullable reference types appropriately
- Keep Razor Pages focused and maintainable
- Write unit tests for business logic

## Claude Code Specific
- This project is managed with Claude Code
- See `plan/` directory for project roadmap and planning documents
- Use `/fast` mode for faster iteration when available
- Remember to commit changes with descriptive messages

## License
See the project license for usage terms.