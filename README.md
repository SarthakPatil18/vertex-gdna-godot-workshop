
# 🎮 Vertex GDNA — Game Development Workshop

Welcome to the official open-source game project for the Vertex GDNA SY–TY recruitment workshop!

In this workshop, you'll explore **Godot 4, GDScript, game mechanics, scene organization, and collaborative development using Git and GitHub**.

Our starter project is a 2D precision platformer. Your challenge is to extend the game with new mechanics, polish existing gameplay, and contribute improvements through pull requests.

## 🕹️ The Game

- **Engine:** Godot 4
- **Language:** GDScript
- **Genre:** 2D Precision Platformer
- **Working title:** Knight's Run / Princess Dragon Slayer

The base game includes player movement, jumping, hazards, collectibles, scoring, and enemy interactions.

## 🙌 Credits & Attribution

This workshop project is based on the 2D platformer tutorials by **Brackeys** and uses assets from the Brackeys asset pack available on itch.io.

- **Tutorial creator:** [Brackeys on YouTube](https://www.youtube.com/@Brackeys)
- **Asset source:** [Brackeys on itch.io](https://brackeysgames.itch.io/)

The original tutorial and assets belong to their respective creator(s). Vertex GDNA uses this project as a learning and recruitment workshop, where participants practice extending gameplay mechanics and contributing through GitHub.

Please refer to the original asset pack's license and terms for redistribution, modification, and attribution requirements.

## 🚀 Getting Started

### Prerequisites

- [Godot Engine 4](https://godotengine.org/download/)
- [Git](https://git-scm.com/downloads)
- A GitHub account

Use the Godot 4 version specified by the workshop organizers, if provided.

### Run the Project

1. Clone or download this repository.
2. Open Godot Engine.
3. Import the project by selecting its `project.godot` file.
4. Open the project and press **F6** to run the current scene, or **F5** to run the configured main scene.

If the project does not run, check the workshop instructions or ask an organizer for help.

## 🧩 Add-on Challenges

Choose an available issue from the repository's **Issues** tab.

Example challenges:

- **Double Jump:** Allow the player to jump a second time while airborne.
- **Bouncy Mushroom Pad:** Add a spring-like object that launches the player upward.
- **Stompable Slime:** Defeat an enemy by landing on it from above.

These are examples of the planned challenge menu. Check the actual issue descriptions for requirements and availability.

Every contribution should satisfy its issue's acceptance criteria and preserve existing gameplay.

## 🤝 How to Contribute

### 1. Choose an Issue

Browse the [open issues](../../issues), read the requirements, and comment that you want to work on a task.

Wait for an organizer to confirm or assign the issue before starting.

### 2. Fork the Repository

Click **Fork** at the top of this repository to create your own copy.

### 3. Clone Your Fork

Replace `YOUR-USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR-USERNAME/vertex-gdna-godot-workshop.git
cd vertex-gdna-godot-workshop
```

### 4. Create a Feature Branch

Use a descriptive branch name related to your issue.

```bash
git switch -c feature/double-jump
```

### 5. Implement and Test

- Make the changes required by the issue.
- Run the game in Godot and test the feature.
- Check that existing mechanics still work.
- Avoid committing generated cache files or unrelated changes.

### 6. Commit and Push

```bash
git add .
git commit -m "feat: add double jump"
git push -u origin feature/double-jump
```

Use a descriptive commit message and replace the example branch name and message with those relevant to your task.

### 7. Open a Pull Request

Open a pull request from your feature branch to the `main` branch of this repository.

Include:
- The issue number (for example, `Closes #1`).
- A summary of your implementation.
- The tests you performed.
- A screenshot or recording when useful.

An organizer will review your contribution and may request changes before merging.

## 📋 Contribution Guidelines

- Work on an assigned issue to avoid duplicate efforts.
- Do not push directly to `main`.
- Keep changes focused on the selected task.
- Preserve the existing project structure unless the task requires otherwise.
- Test your changes before submitting a pull request.
- Respect the licenses and attribution requirements of all assets.
- Ask questions in the issue when requirements are unclear.

## 🛠️ Project Structure

The exact structure depends on the starter project. Common elements include:

- `project.godot` — Godot project configuration.
- Scenes (`.tscn`) — Game scenes and reusable objects.
- Scripts (`.gd`) — GDScript gameplay logic.
- Assets — Sprites, audio, fonts, and other game resources.

Explore the actual project files to understand the existing implementation before making changes.

## 🌱 Keep Contributing

The workshop is the starting point, not the end.

You can continue improving the game by reporting bugs, proposing new mechanics, improving documentation, and submitting pull requests.

**Learn. Build. Create. Play.**

Maintained by **Vertex GDNA**.
