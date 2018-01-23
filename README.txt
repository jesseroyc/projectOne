## PROJECT ONE EVALUATION ##

1) Proper and consistent indentation and spacing
2) Clear and consistent function and variable names
3) Modular and reusable code (small, single-serving functions)
4) Well-commented code
5) No presence of dead/un-used code
6) Good commit history (multiple commits, at least one for each major step, and clear and helpful commit messages)
7) Sensible structure for the project's files and directories


## PROJECT ONE PROBLEM STATEMENT ##

Given a GitHub repository name and owner, download all the contributors' profile images and save them to a subdirectory, avatars/.


## EXPECTED USAGE ##

Your program should be executed from the command line in the following manner,

node download_avatars.js jquery jquery

Any valid repo-owner + repo combination can be used, such as this:

node download_avatars.js nodejs node


## FUNCTIONAL REQUIREMENTS ##

	# Given

		I have node installed
		I am in the shell
		I have your file in my current folder


	# When

		I execute your file using node, providing a github user and repository as command-line arguments For example: $ node download_avatars.js nodejs node


	# Then

		I should find a folder called avatars in my current directory
		The avatars folder should contain images corresponding to the avatars of the contributors of the repo
		The name of each image file should be the contributor's name and the file extension (ex. johnny.png)

## IMPLEMENTATION REQUIREMENTS ##

uses 'request' library to make the HTTP requests

uses git for version control