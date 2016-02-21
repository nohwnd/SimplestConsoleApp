#Simplest console app

A bare minimum of code to create a console application in ASP.NET Core 1.0.

###Running
- Download code.
- Go to project folder. That is the folder where project.json is.
- Run `dnu restore`.
- Run `dnu build`.
- Run `dnx web`.


###Note
This project includes a locked `project.lock.json` file, to keep dependency versions from drifting. To unlock the file run `dnu restore --unlock`. More information [here](https://docs.asp.net/en/latest/dnx/projects.html#project-lock-file).