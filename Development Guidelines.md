<div align="center">
    <h1>Loop Language Development Guidelines</h1>
    <a href="https://looplang.org/">Website</a> | 
    <a href="https://looplang.org/docs">Documentation</a> | 
    <a href="https://discord.gg/CAGR36aD">Discord</a> | 
    <a href="https://looplang.atlassian.net/jira/dashboards/10003">Jira Board</a><br>
    <p>Below you will find all the rules, conventions and guidelines on how we develop software for Loop. These are needed for greater work efficiency and to create the best software possible.</p>
</div>


## Issues

- Use [Jira](https://looplang.atlassian.net/jira/software/c/projects/LOOP/issues) to create: tasks, bug and stories.
  - When you create issue on Jira, try to add it to a correlating Epic.
  - **Epic**: A body of work that can be broken down into smaller tasks (Story). Example: `version 0.1.0`
  - **Story**: Known as "user story" are a list or requirements that make up an Epic. Example: `implement string type`.
  - **Task**: Small jobs, mostly done by an individual. Multiple tasks make up a story.
  - **Bug**: Unwanted/unexpected behaviour of software that needs to be fixed.
-  Give a clear discription of the issue, this will save hassle later on.

## Pull Requests (PR)

- Give clear and semantic names to your branches.
  1. It needs to start with the id of the issue in [Jira](https://looplang.atlassian.net/jira/software/c/projects/LOOP/issues). Examples: `LOOP-44` or `LOOP-3`.
  2. After the id, you need to give it as short as possible name that is descriptive.
  3. Examples: `LOOP-3-enums` or `LOOP-77-implement-inkwell`. 
- To merge the PR, you need approval from at least the project lead, **and** @kanersps or @WouterPennnings.
- Tests are required, otherwise the PR will be denied. We do not want untested/unproven code in our software.

## Committing

- Commit messages need to have [Conventional Commits]( https://www.conventionalcommits.org/en/v1.0.0/).
- Never commit to `main`, always to a seperate branch.

## Extra

- All the repositories are MIT licensed.
- All the software need to have [semantic versioning](https://semver.org/#summary).
- Git repository names need to be simple and only lower case/
- **Does not apply if you are a Open-Source contributer:** The sprints are three weeks of length.



##

<div align="center">
<p>Go to the website for more information.</p>
</div>


<!-- ##
OLD VERSION
1. The length of a sprint is three weeks long. (First sprint started at 28-9-2021)
2. Use GitHub projects & issues for planning, backlog, etc.
3. Git repository names: Lowercase + simple naming.
4. $We are working with feature branches (example: "feat/7-import-statement", the number refers to the issue).
5. $We work with pull requests, needs approval from @kanersps or @WouterPennings, and from the project lead.
6. Git commit conventions. ( explanation: Conventional Commits )
7. Everything is MIT licensed.
8. In a pull request ALWAYS refer to a issue, to avoid future confusion and misunderstanding.
9. Never push to main. -->
