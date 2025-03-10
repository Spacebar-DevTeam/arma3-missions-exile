## Contributing to Arma 3 Mission Files for Exile Mod
## 🛠️ How to Contribute

** Fork the Repository: **
   - Create your own copy of the repository by clicking the `Fork` button.

** Clone Your Fork: ** sh
  - git clone https://github.com/YourUsername/arma3-mission-files.git

Create a Branch:
  git checkout -b feature/new-mission

Make Your Changes:

    Add new missions or update scripts under the appropriate directories.
    Follow the coding guidelines outlined in MissionEditingGuidelines.md.

Test Your Changes:

    Ensure your missions run correctly on a local server.
    Check for script errors or performance issues.

Commit and Push:
  git add .
  git commit -m "Add new capture point mission"
  git push origin feature/new-mission

Create a Pull Request:

    Go to the main repository and open a pull request.
    Provide a clear description of your changes.

Code Review & Merging

    All pull requests will be reviewed before merging.
    Fix any requested changes promptly.

Guidelines

    Avoid modifying core DMS/ZCP files.
    Maintain modularity and keep custom scripts in the designated folders.
    Include comments in scripts where necessary.
