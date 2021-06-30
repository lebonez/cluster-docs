# Getting Started OnDemand

The SIUE OnDemand service is an online access point that provides users with web access to their SIUE `/home` and `/project` directories and to the CC HPC cluster.

> OnDemand offers:
> - Easy file management
> - Command line shell access
> - Slurm job management
> - Interactive Apps (i.e. Matlab, Jupyter...)

OnDemand is available to all SIUE users. To access OnDemand, you must belong to an active project in the campus cluster.

[Log in to SIUE OnDemand](https://ondemand.hpc.siue.edu)

### Files
OnDemand provides a web-based File Explorer that can be used to upload, download, copy, delete, rename, and edit files.

Every user will have access to their `/home` and `/project` directories. If you have access to a project space in a project directory, you will also have access to this directory. The project directory's name will be of the form `/project/<project_name>`.

You can access the File Explorer from the main OnDemand dashboard. Select the file system you would like to access:

[File system]()

After selecting a directory (in this case, the user's home directory), OnDemand will present a graphical representation of the directory and all its contents:

[Files Dashboard]()

#### Navigation
From your selected directory, you can switch to another by backtracking through the path near the top of the window and selecting the previous directory you wish to browse:

Files Dashboard

In addition, you can use the "Go To..." option in the top menu to type the path you wish to navigate to:

Files Dashboard

On the left side of the screen is a tree view of the directory structure. You can navigate this tree the same way you might on a normal desktop GUI to select the folder you wish to use.

#### Uploading and downloading files
There are several ways to upload files. The first is to simply navigate to the desired destination directory in OnDemand, and then drag the file from your local computer to the OnDemand browser window. You can also click the "Upload" button to open a dialog that will allow you to navigate your local computer and select which files you want to upload:

Files Upload

To download files, select the file(s) in the OnDemand directory that you wish to download, and then use the "Download" button. If you select multiple files ("control+click" or "shift+click") or a folder, OnDemand will zip the files and download a single zip archive to your computer.

File operations
Most file operations can be accomplished by selecting a file in the File Explorer and choosing the desired operation from the main menu:

#### Files Operations

You have the ability to perform the following file operations in OnDemand:

- View
- Edit
- Rename/Move
- Download
- Copy
- Paste
- (Un)Select All
- Delete

### Jobs
OnDemand provides two related job managment tools. The Active Jobs tool allows you to monitor queued and running jobs and the Job Composer tool allows you to create and submit jobs via your web browser.

Files Dashboard

#### Active Jobs
The "Active Jobs" tool will show you all jobs currently in the queue (running or queued), regardless of how the jobs were submitted:

Files Dashboard

You can use the dropdown options at the top of the page to toggle between your jobs, all jobs, and the different clusters. The screenshot above shows all jobs on both clusters. You can also use the "Filter" tool to filter jobs based on systems campus, status (running, queued, or hold), user, project account, etc.

If you click the arrow to the left of each job entry, you can get more information about the job, including information about the node(s) on which the job is running.

#### Job Composer
Selecting Job Composer in the Jobs menu will open the Jobs page, where you can create new jobs and submit them to the cluster, and inspect the results of jobs submitted via this tool.

To create a new job, from the Jobs page, click the "+New Job" button:

Files Dashboard

There are four ways to create a job:

- "From Default Template" creates a Simple Sequential Job (the default job template)
- "From Template" creates a new job by copying from an existing job template directory
- "From Specified Path" creates a new job based on the source path to a directory on campus
- "From Selected Job" creates a new job from a previously run job directory

For example, to create a new job from a job template, select "New Job->From Template". Next, select the job template to copy (in this case, "Job Array Job"), then click the blue "Create New Job" button on the lefthand side of the page:

Files Dashboard

The template directory will be copied and a new job row will be added to the top of the jobs table on your Jobs page:Files Dashboard

From the table, select the job you just created, then modify and/or add any files to this job by clicking "Edit Files"Files Dashboard

You will be taken to the File Explorer, where you can upload any files required for your job. See the "Files" section above for instructions on uploading files.

If you need to make changes to a job's settings, select the job and click "Job Options":Files Dashboard

Here, you can change the job name, cluster, job script, project account, or job array specification:Files Dashboard

After you've created your job, added files, and changed any settings as necessary, you can submit the job using the green "Submit" button from the Jobs page. You can also similarly use the yellow "Stop" button to stop a running job, or the red "Delete" button to delete a job from your list:

Files Dashboard

You can also monitor the job status on the Jobs page:

Files Dashboard

Currently, you must reload the page to see job status changes.

### Shell access
OnDemand provides the ability SSH into the campus cluster from inside your web browser:

Files Dashboard

#### campus cluster
To access the campus cluster:

- Select "Clusters->campus Cluster Shell Access" from the dropdown
Duo two-factor authentication is required to access campus cluster. You will see a Duo two-factor authentication prompt upon launching the shell:
Files Dashboard

Shell access will be connected to the campus cluster login node. For detailed information on the campus cluster, see the Getting Started with campus user guide.

SIUE file systems (/home, /project, /scratch, and /scratch2) can be accessed using the OnDemand File Explorer - see the "Files" section above.

SIUE file systems (/home, /project, /scratch, and /scratch2) can be accessed using the OnDemand File Explorer - see the "Files" section above.

Interactive apps
The Interactive Apps section of OnDemand is currently still being developed and as such is not yet available for use. In the future, we hope to have some of the following interactive apps available:

MATLAB
Jupyter
RStudio
Abaqus
COMSOL
RELION

Additional information
OnDemand documentation
