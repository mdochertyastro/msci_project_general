# Matthew Docherty - Msci Project Status Folder

## Repo to keep track of COMPLETE status of project.

**Includes:**

- prep for literature survey (**Due 6th Novemeber 2020**)
- prep for presentation (**Due w/b 8th March 2021**)
- prep for report (**Due 26th March 2021 - Chris wants final copy 12th March 2021**)
  - will create Overleaf project with Chris as a collaborator
- keeping track of dates and course-guides/marking-schemes
- minutes of meeting (_project, igr-data, phas-ml_)
- keeping track of goals/meeting targets
- keeping track of issues to raise with Hunter

**Purpose:**

- to keep all files upto date and accessible on any remote machine
- to keep me accountable for updating (as close to) daily
- to be able to be used as evidence for marking my 'project work' grade out of 22

**Project webspace organisation:**

My initial plan: (8/10/20)

```text
PROJECT DIRECTORY
        |
        '------> Project status dir (This repo - version controlled w/ Git)
        |
        '------> Conda envs dir (Not version controlled as very data intensive)
        |                     |
        |                     '---> package files (txt docs to pip install from requirements incase incompatibilities occur in my envs)
        |                     |
        |                     '---> conda env (have at least 4 diff ones - tf2,torch,vit,basic. The first 2 cloned from wiay root)
        |                     |
        |                     '---> pkgs (a diversion from `$HOME/.conda/pkgs` as wiay data-limit is strict in wiay.)
        |
        '------> Vitamin_b (Most up to date version cloned from Hunter's Git)
        |
        '------> Programming dir (Version controlled from another repo - all my jupyter notebooks for running ML and vit scripts from vscode jupyter server)

```
Next step is to learn git submodules and have the my project webspace as one big repo (git ignoring conda envs for data rate still) and maintaining vit from within my project webspace - would this be too much data for 100gb git limit. Would forking be a better than cloning here?

My second version with submodules has been implimented as of 12/10/20 - still need to decide on conda env webspace and other if I can code directly from branch of forked vit or not!