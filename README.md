<p align="center">
  <img src="CatastifBackupIcon.png" alt="CatastifBackup Icon" width="160">
</p>

<h1 align="center">CatastifBackup</h1>

CatastifBackup is a Windows backup application project designed for both individual computers and centrally managed environments.

The project aims to provide reliable, configurable backups through a graphical interface and unattended execution, with an emphasis on data integrity, portability, and ease of administration.

## Project Status

**Architecture and planning**

CatastifBackup is currently in the design phase. Development of the new application has not yet begun, and no functional release is available.

## Architecture

CatastifBackup is being designed around three operating roles:
a standalone application, a fleet controller, and a fleet agent.

The following diagrams document the planned architecture.
They describe design intentions, not functionality that has
already been implemented.

### C4 Level 1 — System Context

An overview of CatastifBackup, its users, and the external
systems it interacts with.

![C4 Level 1 — System Context](Docs/Architecture/CatastifBackup%20-%20C4%20Level%201.svg)

### C4 Level 2 — Container Diagram

A closer look at the application's operating roles,
local state storage, and communication mechanisms.

![C4 Level 2 — Container Diagram](Docs/Architecture/CatastifBackup%20-%20C4%20Level%202.svg)

Planned cloud integration is included as a future direction,
not a completed feature.

## Background

CatastifBackup originates from the experience gained while developing [BackupStation](https://github.com/radu9832/Backupstation-script), a PowerShell automation script created to back up files from production test stations.

The original project remains available as a separate repository. CatastifBackup is its conceptual successor, designed with a broader scope and a new architecture.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
