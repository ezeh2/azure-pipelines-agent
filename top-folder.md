# Repository Top Folders

The table below summarizes each top-level folder in this repository, the types of files it stores, and notable dependencies on other folders.

| Folder | Summary | Primary File Types | Depends On |
|-------|---------|-------------------|------------|
| `.azure-pipelines` | Azure Pipelines build and release definitions along with helper scripts. | `*.yml`, `*.ps1`, `*.js`, `*.sh` | `src` (build artifacts)
| `.gdn` | Baseline configuration for the GDN (Governance, Detection, and Notification) tool. | `.gdnbaselines` | none |
| `.github` | GitHub configuration including issue templates, workflows, and pull request template. | `*.yml`, `*.md` | none |
| `.vscode` | Editor settings for Visual Studio Code. | `settings.json` | none |
| `docs` | Documentation for contributors and troubleshooting. Includes design notes and various guides. | `*.md`, image assets | `images` (embedded images) |
| `images` | Placeholder folder referencing container images used by the project. | `README.md` | none |
| `release` | Scripts used during the agent release process such as creating branches and rolling releases. | `*.js`, `*.ps1`, `package*.json` | `src` (version files) |
| `src` | Core source code for the Azure Pipelines Agent including multiple C# projects. | `*.cs`, `*.csproj`, helper scripts | none |
| `tools` | Utility scripts to query pipelines or agents. | `*.ps1`, `*.md` | none |

