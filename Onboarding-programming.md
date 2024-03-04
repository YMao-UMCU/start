## References

- Programming norms and docs at RWE [Sharepoint](https://umcutrecht.sharepoint.com/:f:/s/W_JC_RWE-groupSturkenboom/EgjWw_lelAtOhf0hmrcJ510BxJhin_gCo1qBUuhiH-0qIA?e=4C3hq3)
  - To contribute

- To develop a new repo: [Repo template](https://github.com/UMC-Utrecht-RWE/repo_template)

- Package of common functions [T2-DataManagementModel](https://github.com/UMC-Utrecht-RWE/T2-DataManagementModel)
    - To maintain
    - [Flowchart](https://github.com/UMC-Utrecht-RWE/T2-DataManagementModel/blob/b0c178c660a7e04e6f2bf4683808ea6dec6fac66/man/T2_DMM.png)


## Tasks completed

### Create a new project repo

1. Create a repo Paxlovid-1047 named after the project and pull onto local machine.

2. Download [Repo template](https://github.com/UMC-Utrecht-RWE/repo_template) and copy the content directory structure into Paxlovid-1047.

3. Add module [T2-DMM](https://github.com/UMC-Utrecht-RWE/T2-DataManagementModel) into Paxlovid-1047 as a subsidiary package, the common functions are going to be utilized in Paxlovid-1047.
    - To modify this step with package release number

4. Add a set of sample data from sharepoint [Synthetic database](https://umcutrecht.sharepoint.com/sites/W_JC_RWE-groupSturkenboom/Gedeelde%20documenten/Forms/AllItems.aspx?ga=1&id=%2Fsites%2FW%5FJC%5FRWE%2DgroupSturkenboom%2FGedeelde%20documenten%2FGeneral%2F04%2E%20Documentation%2FSynthetic%20databases&viewid=648f81c8%2D4042%2D415e%2Daa4c%2Da2541bd74a3f) into folder Paxlovid-1047/data/D2_cdm


### Clean up T2 script

Based on content of scripts under repo [Janssen-PASS-study](https://github.com/UMC-Utrecht-RWE/Janssen-PASS-study/tree/Final-Analysis/Data%20characterisation/Janssen_Script), adapt into Paxlovid-1047 with supporting functions from T2-DMM.

1. Fix directory variables 

2. Fix T2-DMM supporting functions (pull request)

3. Add to meta data files

3. Create supporting functions such as load_function, set_toupper...

4. Build functions to support concept id creation. Reference [link](https://github.com/ARS-toscana/CreateConceptSetDatasets)

