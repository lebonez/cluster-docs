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

>OnDemand has quick links to your:
> - SIUE home directory
> - SIUE project directory(ies)

Every user will have access to their `/home` and `/project` directories. If you have access to a project space in a project directory, you will also have access to this directory. The project directory's name will be of the form `/project/<project_name>`.

You can access the File Explorer from the main OnDemand dashboard. Select the file system you would like to access:

![Files Links](_media/ondemand/files_links.png ':size=900')

After selecting a directory (in this case, the user's home directory), OnDemand will present a graphical representation of the directory and all its contents:

![Files Content](_media/ondemand/files_content.png ':size=900')

#### Navigation
From your selected directory, you can switch to another by backtracking through the path near the top of the window and selecting the previous directory you wish to browse:

![Files Directory](_media/ondemand/files_directory.png ':size=900')

In addition, you can use the "Change Directory" option in the top menu to type the path you wish to navigate to:

![Files Change Directory](_media/ondemand/files_change_directory.png ':size=900')

On the left side of the screen is a tree view of the directory structure. You can navigate this tree the same way you might on a normal desktop GUI to select the folder you wish to use.

#### Uploading and downloading files
There are several ways to upload files. The first is to simply navigate to the desired destination directory in OnDemand, and then drag the file or directory from your local computer to the OnDemand browser window. You can also click the "Upload" button to open a dialog that will allow you to navigate your local computer and select which files you want to upload:

![Files upload_file](_media/ondemand/files_upload_file.png ':size=900')

 You can also click the "Upload" button to open a dialog that will allow you to navigate your local computer and select which directories you want to upload:

![Files upload_directory](_media/ondemand/files_upload_directory.png ':size=900')

To download files, select the file(s) in the OnDemand directory that you wish to download, and then use the "Download" button. If you select multiple files ("control+click" or "shift+click") or a folder, OnDemand will zip the files and download a single zip archive to your computer.

#### File operations

Most file operations can be accomplished by selecting a file in the File Explorer and choosing the desired operation from the main menu:

![Files Operations](_media/ondemand/files_operations.png ':size=900')

> You have the ability to perform the following file operations in OnDemand:
>
> - Open in Terminal (go directly to the directory containg the file in the web terminal shell)
> - New File (create a new blank file)
> - New Directory (create a new empty directory)
> - Upload (upload a file form your local computer)
> - Download (check box of file to download before clicking)
> - Copy/Move (used to rename and copy files)
> - Delete (deletes file permanently **be careful**)

### Jobs
OnDemand provides two related job management tools. The Active Jobs tool allows you to monitor queued and running jobs and the Job Composer tool allows you to create and submit jobs via your web browser.

![Jobs Links](_media/ondemand/jobs_links.png ':size=900')

#### Active Jobs
The "Active Jobs" tool will show you all jobs currently in the queue (running or queued), regardless of how the jobs were submitted:

![Jobs Active Dashboard](_media/ondemand/jobs_active_dashboard.png ':size=900')

You can use the dropdown options at the top of the page to toggle between your jobs, all jobs, and the different clusters. The screenshot above shows all jobs clusters. You can also use the "Filter" tool to filter jobs based on systems campus cluster, status (running, queued, or hold), user, project account, etc.

If you click the arrow to the left of each job entry, you can get more information about the job, including information about the node(s) on which the job is running.

#### Job Composer
Selecting Job Composer in the Jobs menu will open the Jobs page, where you can create new jobs and submit them to the cluster, and inspect the results of jobs submitted via this tool.

To create a new job, from the Jobs page, click the "+New Job" button:

![Jobs New Job](_media/ondemand/jobs_new_job.png ':size=900')

There are four ways to create a job:

- "From Default Template" creates a Simple Sequential Job (the default job template)
- "From Specified Path" creates a new job based on the source path to a directory on the campus cluster
- "From Selected Job" creates a new job from a previously run job directory

For example, to create a new job from a job default template, select `New Job -> From Default Template`. then click the blue `Create New Job` button on the left hand side of the page:

![Jobs Created](_media/ondemand/jobs_created.png ':size=900')


From the table, select the job you just created, then modify and/or add any files to this job by clicking `Edit Files`

![Jobs Edit Files](_media/ondemand/jobs_edit_files.png ':size=900')

You will be taken to the File Explorer, where you can upload any files required for your job. See the "Files" section above for instructions on uploading files.

If you need to make changes to a job's settings, select the job and click "Job Options":

![Jobs Options](_media/ondemand/jobs_options.png ':size=900')

Here, you can change the job name, cluster, job script, project account, or job array specification:

![Jobs Options Menu](_media/ondemand/jobs_options_menu.png ':size=900')

After you've created your job, added files, and changed any settings as necessary, you can submit the job using the green "Submit" button from the Jobs page. You can also similarly use the yellow "Stop" button to stop a running job, or the red "Delete" button to delete a job from your list:

![Jobs Submit Stop Delete](_media/ondemand/jobs_submit_stop_delete.png ':size=900')

You can also monitor the job status on the Jobs page:

![Jobs Status](_media/ondemand/jobs_status.png ':size=900')

Currently, you must reload the page to see job status changes.

### Shell access

OnDemand provides the ability SSH into the [campus cluster](getting-started.md) from inside your web browser:

![Shell Links](_media/ondemand/shell_links.png ':size=900')

#### campus cluster

To access the campus cluster:

- Select `Clusters->CC Cluster Shell Access` from the drop-down. You will see a password authentication prompt upon launching the shell:

![Shell Prompt](_media/ondemand/shell_prompt.png ':size=900')

Shell access will be connected to the campus cluster login node. For detailed information on the campus cluster, see the [Getting Started](getting-started.md) user guide.

SIUE file systems (/home, /project) can be accessed using the OnDemand File Explorer - see the "[Files](#files)" section above.

### Interactive apps
The Interactive Apps section of OnDemand is a selection of apps that range from a complete desktop VNC session to a Jupyter Lab web browser session.

- CC Cluster Desktop
- MATLAB
- Jupyter

![Interactive Apps Links](_media/ondemand/interactive_apps_links.png)

### Additional information
- [OnDemand documentation](https://www.osc.edu/resources/online_portals/ondemand)
