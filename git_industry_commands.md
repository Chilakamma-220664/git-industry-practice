# Industry Level Git Commands Practice

## 1. Git Configuration Commands

### Command: git config --global user.name

**Syntax:**
git config --global user.name "Your Name"

**Purpose:**
Sets the global username for Git commits.

**Example:**
git config --global user.name "Chilakamma"

## 2. Repository Setup Commands

### Command: git init

**Syntax:**
git init

**Purpose:**
Initializes a new Git repository in the current directory.

**Example:**
git init

**Purpose:**
Initializes a new Git repository.

**Example:**
git init

### Command: git clone

**Syntax:**
git clone <repository_url>

**Purpose:**
Copies an existing remote repository from GitHub (or any remote server) to your local system.

**Example:**
git clone https://github.com/your-username/git-industry-practice.git

**Screenshot Proof:**
**Screenshot Proof:**

![git status output](git_status.png)

### Command: git clone --branch

**Syntax:**
git clone --branch <branch-name> <repository_url>

**Purpose:**
Clones a specific branch from a remote repository instead of the default branch.

**Example:**
git clone --branch master https://github.com/your-username/git-industry-practice.git

**Screenshot Proof:**
**Screenshot Proof:**

![git status output](git_status.png)

### Command: git clone --depth

**Syntax:**
git clone --depth <number> <repository_url>

**Purpose:**
Clones the repository with limited commit history (shallow clone). Improves speed by downloading fewer commits.

**Example:**
git clone --depth 1 https://github.com/your-username/git-industry-practice.git

**Screenshot Proof:**
**Screenshot Proof:**

![git status output](git_status.png)

### Command: git log --oneline

**Syntax:**
git log --oneline

**Purpose:**
Displays commit history in a short, single-line format.

**Example:**
git log --oneline

**Screenshot Proof:**
(Add screenshot showing git log --oneline output)

### Command: git log --graph

**Syntax:**
git log --graph

**Purpose:**
Shows commit history in a graphical tree structure.

**Example:**
git log --graph

**Screenshot Proof:**
(Add screenshot showing git log --graph output)