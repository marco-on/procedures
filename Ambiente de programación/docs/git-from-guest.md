# git from **_Guest_**

1. Create a new repository from https://github.com/user-name/

		1.1 Create repository name.
		The name should be the same than the created as a directory in the _guest_. _repo_name_ in this exapmle.
		https://github.com/user-name/repo_name
		
		1.2 Add a description.
		1.3 Add License. Do not add README.md at this point. It will be created and pushed from _guest_ in the next step.

2. Create a new repository on the command line at Guest

		a. mkdir repo_name
		b. cd repo_name
		c. printf "#include<stdio.h>\nint main (void){\n\tprintf(\"Hello World\!\");\n\treturn 0;\n}" >> hello-world.c
		d. echo "# repo_name" >> README.md
		e. git init
		f. git status
		g. git add README.md
		h. git add hello-world.c
		i. git status
		j. git commit -m "first commit"
		k. git remote add origin https://github.com/user-name/repo_name.git
		l. git push -u origin master
                
	After editing hello-world.c repeat from h skipping k.


3. Other commands. Review pending

	- …or push an existing repository from the command line
	- git remote add origin https://github.com/user-name/repo_name.git
	git push -u origin master


	- git pull origin --allow-unrelated-histories HEAD
	- git status
	- git add README.md
	- git add smallobj.cpp
	- git status
	- git commit -m "otra pruebaa" smallobj.cpp README.md

