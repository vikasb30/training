# Process for GitHub Assignment Creation

## Login to your GitHub via https://github.com/

### I Create New Organization
1. Click on the + at the upper-right corner of your page and choose a new organization.
2. Choose the option, join for free, and enter a valid organization name of your choice, email, and select my account and click on next.
3. Click on skip to continue to enter your details later.

### II Create New Repository
1. Click on the + at the upper-right corner of your page and choose a new repository.
2. Under the Owner drop-down, select the organization that you created and give a valid repository name.
3. Choose private to and click on Create repository.
4. Copy the two statements under "…or push an existing repository from the command line" to the notepad.
5. Goto settings tab and enable template repository.

## Access GitHub classroom via https://classroom.github.com/classrooms

### III Classroom creation

1. Click on a new classroom and if you don't find the organization you created, click on grant us access.
2. Under organization access, click on grant shown beside the organization.
3. Refresh the classroom page and choose the organization.
4. You may change the name of the classroom else click on continue.
5. Copy the link of the classroom, paste it in a notepad for later use, and click on continue.
6. Skip without choosing any learning management tools.
7. Add the students by entering their GitHub ids.

### IV Adding Files to Repository
1. Create a folder with all the necessary files to be pushed into the repository.
2. Open terminal from VSCode, go to the created folder and perform the following steps:
	+ git init
	+ git status
	+ git add .
	+ git status
	+ git commit -m "Any message"
	+ Enter the two statements from the notepad(git remote add and git push)
3. Refresh the repository page to see the pushed files.

### V Creating an Assignment in GitHub Classroom
1. Click on create your first assignment.
2. Enter the title starting with "Assign-" followed by a number(Ex: Assign-02) and click on continue.
3.  Click on select a repository and type the repository name created in GitHub and choose it.
4. Select the template repository and click on continue.
5. Under Add Autograding tests, click on Add test and choose run python.
6. For each file in your repository perform the following steps:
	+ Enter program filename in the test name field.
	+ Clear setup command field.
	+ Enter *python3 filename.py* in the run command field
	+ Enter the points for the program(optional)
	+ Save the test case.
7. Click on create assignment.
8. Share the assignment link with the students.

**For more information on assignment, setup watch below video**
[Video Link](https://youtu.be/rTsfBAV7sOo)


