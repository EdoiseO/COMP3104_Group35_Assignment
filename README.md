# COMP3104_Group35_Assignment

Group 35 — Developer Operations

This project brings together our individual work on Git, GitHub collaboration and continuous integration. We will use separate member branches, local commits and pull requests to combine our contributions in one shared repository.

## Group members

| Member | GitHub |
| --- | --- |
| Phillip Onofua | [EdoiseO](https://github.com/EdoiseO) |
| Kalid Ali | [kalidal](https://github.com/kalidal) |
| Mohamed Amine Ouatar | [Tomamine1](https://github.com/Tomamine1) |
| Joshua Zaakir | [JoshuaZaakir](https://github.com/JoshuaZaakir) |

## Setup

Clone the repository and enter the project directory:

```sh
git clone https://github.com/EdoiseO/COMP3104_Group35_Assignment.git
cd COMP3104_Group35_Assignment
```

The assignment files are plain text. No application dependencies are required.

## Member files

Each member creates these three files in the repository root, replacing `STUDENTID` with their student number:

| File | Content |
| --- | --- |
| `STUDENTID_gb.txt` | Information about George Brown College |
| `STUDENTID_devops.txt` | Information about the DevOps course |
| `STUDENTID_sdlc.txt` | The importance of DevOps in the software development lifecycle |

## Branching strategy

- `main` holds the group's merged work.
- Each member works on a branch named `STUDENTID-Name` and makes at least ten meaningful commits with descriptive messages.
- File changes and commits are made locally, then pushed to the member's branch.
- Members pull updates regularly and open pull requests into `main`. Any conflicts must be resolved before merging.
- Each member contributes to this README as the project develops.

## CI/CD

The CI workflow has not been configured yet. GitHub Actions will be set up under `.github/workflows/`, and its results will be available in the repository's Actions tab.
