
```markdown
# Git Helper

This repository is a collection of essential Git commands and a visual sequence diagram for understanding how Git workflows operate. If you ever find yourself stuck in the weeds with Git, this should help you get back on track.

---

## 📌 What's Inside
- **`git_commands.md`** – A table of Git commands, why they matter, and how to test them.
- **`git_seq.puml`** – A PlantUML sequence diagram to visualize Git operations.

---

## 🚀 Getting Started

### Clone the Repo
To get started, pull this repository down to your local machine:

```sh
git clone https://github.com/taylorparsons/git_helper.git
cd git_helper
```

---

## 📖 Using the Git Command Reference

The **`git_commands.md`** file is a quick reference guide with:
- The most common Git commands.
- Explanations for when and why you’d use them.
- Simple tests to confirm they worked.

### 🔍 Viewing the Guide
To read the command guide from the terminal:

```sh
cat git_commands.md
```

Or open it in VS Code:

```sh
code git_commands.md
```

---

## 📊 Visualizing Git Workflows

If you're a visual learner, the **`git_seq.puml`** file provides a sequence diagram to help understand Git operations.

### 🔹 Viewing the Diagram
To render the diagram, you'll need [PlantUML](https://plantuml.com/):

1. Install PlantUML:
   ```sh
   sudo apt install plantuml  # Linux
   brew install plantuml       # macOS
   choco install plantuml      # Windows
   ```
2. Generate the diagram:
   ```sh
   plantuml git_seq.puml
   ```
3. Open the generated image (`git_seq.png` or `.svg`).

---

## 🔄 Keeping It Up to Date

To pull the latest changes:

```sh
git pull origin main
```

To contribute changes:

1. Make your edits.
2. Stage and commit:
   ```sh
   git add .
   git commit -m "Updated Git command reference"
   ```
3. Push to GitHub:
   ```sh
   git push origin main
   ```

---

## 🤝 Contributing
If you find missing commands or improvements, feel free to submit a **pull request**.

---

## 📌 Need Help?
If Git is giving you trouble, here are some quick fixes:

- **Undo last commit (before pushing):**
  ```sh
  git reset --soft HEAD~1
  ```
- **Fix an accidental commit push:**
  ```sh
  git revert HEAD
  git push origin main
  ```
- **See what’s changed:**
  ```sh
  git status
  ```

For more troubleshooting, refer to **`git_commands.md`** or reach out.

---

### 🏁 That’s It!
Now go forth and version your code like a pro. 🚀
```
