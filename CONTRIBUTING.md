
# Contributing to the Vertex GDNA Workshop

Welcome! This repository is a collaborative learning project based on Brackeys' Godot tutorials and assets. We're using it to practice game development and open-source collaboration.

## 1. Choose a Task

- Browse the repository's Issues tab.
- Read the issue description and acceptance criteria.
- Comment that you want to work on the issue.
- Wait for an organizer to confirm or assign it.
- Ask questions in the issue if anything is unclear.

Please work on one issue at a time unless an organizer approves otherwise.

## 2. Fork and Clone

Fork the repository on GitHub, then clone your fork:

```bash
git clone https://github.com/YOUR-USERNAME/vertex-gdna-godot-workshop.git
cd vertex-gdna-godot-workshop
```

## 3. Create a Branch

Create a descriptive branch for your task:

```bash
git switch -c feature/your-feature-name
```

Examples:

- `feature/double-jump`
- `feature/bouncy-mushroom`
- `feature/stompable-slime`
- `fix/coin-collision`

Do not work directly on `main`.

## 4. Implement Your Feature

- Understand the existing scene tree and scripts before changing them.
- Follow the acceptance criteria in your issue.
- Keep changes focused on the selected task.
- Reuse existing systems when practical.
- Avoid unrelated refactoring.
- Do not commit the generated `.godot/` cache directory.

## 5. Test Your Changes

Before submitting:

- Open the project in the workshop's specified Godot 4 version.
- Run the game and verify your feature.
- Check that existing movement, jumping, collectibles, and other relevant mechanics still work.
- Check the debugger for relevant errors.
- Capture a screenshot or short recording if it demonstrates the feature.

## 6. Commit and Push

```bash
git add .
git commit -m "feat: describe your change"
git push -u origin feature/your-feature-name
```

Use a clear commit message that describes what changed.

## 7. Open a Pull Request

Open a pull request from your fork's feature branch to this repository's `main` branch.

Include:

- The issue number, using `Closes #ISSUE_NUMBER` when appropriate.
- A summary of your changes.
- Testing steps and results.
- Screenshots or recordings when useful.
- Any known limitations.

## 8. Code Review

Organizers will review submissions against the issue's acceptance criteria.

They may request changes before approving a pull request. Please respond to review comments and push any fixes to the same feature branch.

A pull request is merged only after the organizer confirms that the changes are appropriate and tested.

## 9. Respect Assets and Attribution

This project is based on Brackeys' tutorials and uses assets from the original asset pack.

Do not remove attribution or redistribute third-party assets separately. Follow the applicable asset license and any instructions provided by the organizers.

## 10. Ask for Help

If you get stuck, comment on your issue or ask an organizer during the workshop.

The goal is to learn, experiment, collaborate, and build maintainable game features together.
