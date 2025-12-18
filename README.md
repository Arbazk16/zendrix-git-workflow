# zendrix-git-workflow



\# Zendrix Software – Git Release Workflow



This repository demonstrates a Git workflow to manage monthly product releases scheduled on the 25th of every month.



\## Branching Strategy

\- main: Production-ready code

\- develop: Integration branch for the upcoming monthly release

\- feature/\*: Feature development branches

\- release/\*: Release preparation and stabilization before the 25th



\## Release Process

1\. Developers create feature branches from develop.

2\. Completed features are merged into develop.

3\. Before the 25th, a release branch is created from develop.

4\. Testing and bug fixes are done in the release branch.

5\. On the 25th, the release branch is merged into main and tagged.

6\. Release changes are merged back into develop.

