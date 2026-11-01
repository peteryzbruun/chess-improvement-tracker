# 04 Code Lab

Purpose: software, apps, dashboards, scripts, prototypes, and code projects.

## Project Directory

Use this list to find a Code Lab workspace and record whether it is still active. Entries marked **Review** need owner confirmation; folder names and README files alone do not establish that work is active.

| Project or workspace | State |
|---|---|
| [AI Skills Studio](AI%20Skills%20Studio/) | Active |
| [ai-workflow-atlas](ai-workflow-atlas/) | Review |
| [archify](archify/) | Review |
| [atlas](atlas/) | Review |
| [bok-automation](bok-automation/) | Review |
| [chess.com-api-project](chess.com-api-project/) | Review |
| [chess-improvement-tracker](chess-improvement-tracker/) | Draft |
| [claude-cli-customization](claude-cli-customization/) | Review |
| [codex-learning-lab](codex-learning-lab/) | Review |
| [codexbar](codexbar/) | Review |
| [diagram-design](diagram-design/) | Review |
| [Experiments](Experiments/) | Review |
| [File Automation Lab](file-automation-lab/) | Review |
| [github_files](github_files/) | Review |
| [homebase-start-page](homebase-start-page/) | Review |
| [html-effectiveness-main](html-effectiveness-main/) | Review |
| [langchain-starter](langchain-starter/) | Review |
| [loop-engineering-first](loop-engineering-first/) | Review |
| [MacBookPro-2012-doc](MacBookPro-2012-doc/) | Review |
| [Optimizing My OpenAI Setup](Optimizing%20My%20OpenAI%20Setup/) | Review |
| [Personal Identity & Documentation](Personal%20Identity%20%26%20Documentation/) | Review |
| [pyzb-landingpage-old](pyzb-landingpage-old/) | Review |
| [sherlock](sherlock/) | Review |
| [short-some-video-fail](short-some-video-fail/) | Review |
| [yt-dlp-personal-workflow](yt-dlp-personal-workflow/) | Review |
| [Repository Finder Icons helper](.codelab-icon-policy/) | Review |

After reviewing an entry's README, local instructions, and repository status, replace **Review** with a concise state such as **Active**, **Paused**, **Reference**, or **Retired**. Keep the detailed project guidance and Git history inside that project's own folder.

## What Belongs Here

- code projects,
- app folders,
- dashboards,
- scripts and technical prototypes,
- one repo or app per folder where possible.

## What Does Not Belong Here

- non-code personal projects,
- general reference drawers,
- active music production assets,
- code copied from old roots without baseline review.

## Routing Examples

- Standalone repositories, apps, libraries, scripts, and technical prototypes belong in this room.
- Keep code inside [**02 Active Projects**](../02%20Active%20Projects/) when it is integral to a larger project and the project folder is its clearer canonical home.
- Keep active study and exercises in [**07 Learning Lab**](../07%20Learning%20Lab/README.md) when learning is the main purpose.
- Keep consulted guides and durable research in [**05 Knowledge & Curiosity — Reference**](../05%20Knowledge%20%26%20Curiosity/Reference/README.md).

## Risk Notes

Before running installs/builds or initializing Git:

- confirm project status,
- check for old path references,
- decide whether a separate repo is needed,
- commit a baseline if Git is approved.

Do not run `npm install` or `npm build` without a checkpoint.

## Automation

Start with the [Automation Guide](Automation%20Guide.md) for choosing an approach and building it safely. Hands-on file examples live in the [File Automation Lab](file-automation-lab/README.md).

## Finder Metadata Helper

The Code Lab has a local helper that updates Finder icons and a README tag for GitHub-origin repositories. Its scope, effects, and pause/resume steps are in the [Code Lab Repository Finder Icons guide](.codelab-icon-policy/README.md).

## Cloning a Repository

Replace the URL with the repository you want to clone:

```bash
REPO_URL="https://github.com/owner/repository.git"

cd ~/Homebase/04\ Code\ Lab &&
git clone "$REPO_URL" &&
cd "$(basename "$REPO_URL" .git)" &&
code .
```

This will:

1. Go to `~/Homebase/04 Code Lab`
2. Clone the repository
3. Enter the newly created repository folder
4. Open it in VS Code

Example

```bash
REPO_URL="https://github.com/sherlock-project/sherlock.git"

cd ~/Homebase/04\ Code\ Lab &&
git clone "$REPO_URL" &&
cd "$(basename "$REPO_URL" .git)" &&
code .
```

Clone Without Opening VS Code

```bash
REPO_URL="https://github.com/owner/repository.git"

cd ~/Homebase/04\ Code\ Lab &&
git clone "$REPO_URL" &&
cd "$(basename "$REPO_URL" .git)"
```

Verify the Clone

```bash
git status
git remote -v
git branch --show-current
```

Standard Location Rule

```
General repositories:
~/Homebase/04 Code Lab/<repository-name>

Code belonging to a larger active project:
~/Homebase/02 Active Projects/<project-name>/<repository-name>

Temporary experiments:
~/Homebase/04 Code Lab/Experiments/<repository-name>
```
