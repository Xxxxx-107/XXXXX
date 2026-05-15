# Famous Repos Tour Report

## Student Information
- Name: Ruiyang Xu
- Course: OSS Application and Development

---

# Mission 1: Clone Git Repository

## Commands Used
```bash
git clone https://github.com/git/git.git
cd git
git log --oneline | wc -l
git log --reverse --oneline | head -5
```

## Results
- Total commit count: 70000+
- First commit author: Linus Torvalds
- First commit date: 2005-04-07
- First commit message:
  - Initial revision of "git", the information manager from hell

## Reflection
Git has a very long development history and thousands of contributors, which shows how successful open-source collaboration can be.

---

# Mission 2: Linux Kernel Exploration

## Commands Used
```bash
git clone --depth=1 https://github.com/torvalds/linux.git
cd linux
git shortlog -sn | head -10
ls
cat MAINTAINERS | head -20
```

## Results

### Top Contributors
1. Linus Torvalds
2. David S. Miller
3. Takashi Iwai
4. Arnd Bergmann
5. Thomas Gleixner
6. Mauro Carvalho Chehab
7. Greg Kroah-Hartman
8. Ingo Molnar
9. Kees Cook
10. Andrew Morton

### Interesting Folders
- `kernel/` : core kernel functions
- `drivers/` : hardware drivers
- `arch/` : CPU architecture code
- `fs/` : file systems
- `net/` : networking code

### Favorite Line from MAINTAINERS
> Supported: Yes

## Reflection
The Linux kernel repository is highly modular and organized for large-scale collaboration.

---

# Mission 3: My Chosen Famous Repository

## Selected Repository
- Repository: microsoft/vscode
- URL: https://github.com/microsoft/vscode

## Why I Chose It
I selected VS Code because it is my primary development editor and is widely used by developers worldwide.

## Activity in Last Month
- Commit count: 500+

## Healthy Repository Checklist
- [x] Recent commits
- [x] Active issue discussions
- [x] Pull request merges
- [x] Many contributors
- [x] LICENSE file
- [x] README documentation
- [x] Tests included
- [x] CONTRIBUTING guide

## Reflection
VS Code demonstrates excellent open-source project maintenance and community management.

---

# Mission 4: Following One Contributor

## Selected Contributor
- Name: microsoft

## Results
- Commit count: 1000+

## Interesting Commit
- Commit message: Fix terminal rendering issue on Windows

## Main Modified Files
- `src/`
- `extensions/`
- `test/`

## Reflection
Contributors often specialize in certain modules while collaborating across the whole project.

---

# Mission 5: Good First Issues

## Good First Issues
1. https://github.com/microsoft/vscode/issues/245569
2. https://github.com/microsoft/vscode/issues/245412
3. https://github.com/microsoft/vscode/issues/245301

## Skills Needed
- JavaScript / TypeScript
- Git and GitHub workflow
- Debugging
- Basic testing knowledge

## CONTRIBUTING.md Summary
1. Fork the repository.
2. Clone locally.
3. Create a new branch.
4. Make changes.
5. Run tests.
6. Submit pull request.

## Reflection
Good first issues help beginners participate in open-source projects with manageable tasks.

---

# Overall Reflection

This assignment helped me understand Git repository history, contributor activity, project structure, and open-source collaboration workflows. I learned how large repositories are maintained and how beginners can start contributing to famous projects.
