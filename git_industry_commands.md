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
![git status output](git_status.png)

![Git Log Oneline](git_log_oneline.png)

### Command: git log --graph

**Syntax:**
git log --graph

**Purpose:**
Shows commit history in a graphical tree structure.

**Screenshot Proof:**
![Git Log Graph](git_log_graph.png)

### Command: git branch

**Syntax:**
git branch

**Purpose:**
Lists all branches in the repository and highlights the current branch.

**Screenshot Proof:**
![Git Branch](branch.png)

### Command: git branch -a

**Syntax:**
git branch -a

**Purpose:**
Displays all local and remote branches.

**Example:**
git branch -a

**Screenshot Proof:**
![Git Branch -a](git_branch_a.png)

### Command: git checkout -b

**Syntax:**
git checkout -b <branch-name>

**Purpose:**
Creates and switches to a new branch.

**Example:**
git checkout -b feature-branch

**Screenshot Proof:**
![Git Checkout -b](git_checkout_b.png)

### Command: git switch

**Syntax:**
git switch <branch-name>

**Purpose:**
Switches to an existing branch.

**Example:**
git switch main

**Screenshot Proof:**
![Git Switch](git_switch.png)

### Command: git checkout

**Syntax:**
git checkout <branch-name>

**Purpose:**
Switches to another branch 
**Example:**
git checkout main

**Screenshot Proof:**
![Git Checkout](git_checkout.png)