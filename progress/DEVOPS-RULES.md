# DevOps Working Rules

## 1. Commit Standards

All commits must follow Conventional Commits:

- feat: new feature or Kubernetes manifest
- fix: bug fix or correction
- docs: documentation updates
- chore: repository structure or maintenance
- test: validation or simulations

Format:
<type>(<scope>): <description>

Example:
feat(k8s): add nodeSelector scheduling example

---

## 2. Work Flow

Daily workflow:

1. Execute lab or technical task
2. Save artifacts in /k8s or /ci-cd
3. Document progress in /progress/day-XX.md
4. Update tracker status
5. Commit changes separately (code vs docs)

---

## 3. Commit Discipline Rules

- One logical change per commit
- Never mix code and documentation in the same commit
- Every change must be traceable
- Commit messages must describe action, not intention
