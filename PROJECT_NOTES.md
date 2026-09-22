# StudyTrack Project Notes

## Project Organization

- PROPOSAL.md contains the approved project scope.
- README.md contains the project overview and current status.
- docs/ contains documentation and design images.
- app/ contains the application source code.
- requirements.txt contains Python dependencies.
- Credentials and API keys must never be committed to GitHub.

## Code Style

- Use Python naming conventions.
- Use snake_case for variables and functions.
- Use descriptive variable and function names.
- Keep functions small and focused on one responsibility.
- Add comments when they improve understanding.
- Validate user input before storing data.
- Handle expected errors with clear messages.

## Assistant Rules

The coding assistant should never:

- Change the approved project scope without permission.
- Delete working features without permission.
- Add unnecessary dependencies.
- Put passwords, API keys, tokens, or credentials in source code.
- Change database fields without updating the project documentation.
- Replace large working sections of the application without explaining the change.

## Development Convention

Each major feature should correspond to a GitHub issue. Changes should be tested before an issue is considered complete.
