# Windows Instructions</br>

- ### [Installing `git`](#win_installing_git)</br>
- ### [Installing `cmake`](#win_installing_cmake)</br>
- ### [Installing `MinGW`](#win_installing_mingw)</br>
- ### [Accepting the assignment](#win_accepting_the_assignment)</br>
- ### [Cloning the assignment](#win_cloning_the_assignment)</br>
- ### [Project organization](#win_project_organization)</br>
- ### [Git commands](#win_git_commands)</br>
- ### [Build and run walk through](#win_build_and_run_walkthrough)</br>
- ### [Getting started with the project](#win_getting_started)</br>
- ### [Completing the project](#win_completing_the_project)</br>

---

</br>

<a name="win_installing_git"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Installing git ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

### Download `git`

Download git from [here](https://git-scm.com/download/win). You should get an exe similar to this: `Git-2.30.0.2-64-bit.exe`

<img src="images/win_images/git-01-download_git_00.png" alt="download_git" width="1000"/>

</br>

### Install `git`

Open/Run the executable file, and follow the steps to install.

Choose Default.

<img src="images/win_images/git-01-download_git_01.png" alt="download_git" width="1000"/>

</br>

Choose Git Credential Manager Core.

<img src="images/win_images/git-01-download_git_02.png" alt="download_git" width="1000"/>

</br>

Select Only show new options if not selected, and click next.

<img src="images/win_images/git-01-download_git_03.png" alt="download_git" width="1000"/>

Choose Let git decide.

<img src="images/win_images/git-01-download_git_04.png" alt="download_git" width="1000"/>

</br>

Choose Use OpenSSH.

<img src="images/win_images/git-01-download_git_05.png" alt="download_git" width="1000"/>

</br>

Choose Default (fast-forward or merge).

<img src="images/win_images/git-01-download_git_06.png" alt="download_git" width="1000"/>

</br>

Choose Git Credential Manager Core

<img src="images/win_images/git-01-download_git_07.png" alt="download_git" width="1000"/>

</br>

And Install!

<img src="images/win_images/git-01-download_git_08png.png" alt="download_git" width="1000"/>

<img src="images/win_images/git-01-download_git_10.png" alt="download_git" width="400"/>

<img src="images/win_images/git-01-download_git_11.png" alt="download_git" width="400"/>

</br>

When it is done installing, click Finish.

<img src="images/win_images/git-01-download_git_12.png" alt="download_git" width="1000"/>

</br>

You may view release notes if you want.

<img src="images/win_images/git-01-download_git_13.png" alt="download_git" width="1000"/>

</br>

### Check git installation

To make sure git is installed correctly

```sh 
$ git --version
```

<img src="images/win_images/git-00-git_version.png" alt="download_git" width="1000"/>

<br/>

### Login git

Login git with username and email address:

```sh
$ git config --global user.name "stephengineer"
$ git config --global user.email swang03@pasadena.edu
```

---

</br>

<a name="win_installing_cmake"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Installing cmake ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

### Download `cmake`

Download cmake from [here](https://cmake.org/download/). Choose the Windows win64-x64 Installer. You should get an msi with a name similar to this: `cmake-3.19.4-win64-x64.msi`

<img src="images/win_images/cm-00-download_site.png" alt="download_cmake" width="1000"/>

</br>

### Install `cmake`

Open/Run the executable file, and follow the steps to install.

<img src="images/win_images/cm-01-download_00.png" alt="install_cmake" width="1000"/>

</br>

Check I accept the terms in the License Agreement.

<img src="images/win_images/cm-01-download_01.png" alt="install_cmake" width="1000"/>

</br>

**Make sure** to select Add CMake to the system PATH for all users. You can create a Desktop icon if you want, but you will not need to use it for this class.

<img src="images/win_images/cm-01-download_03.png" alt="install_cmake" width="1000"/>

</br>

The default install location should be C:\Program Files\CMake\

> <img src="images/win_images/cm-01-download_04.png" alt="install_cmake" width="1000"/>

</br>

Install!

<img src="images/win_images/cm-01-download_05.png" alt="install_cmake" width="300"/>

<img src="images/win_images/cm-01-download_06.png" alt="install_cmake" width="300"/>

</br>

When it is done installing, click Finish.

<img src="images/win_images/cm-01-download_07.png" alt="install_cmake" width="1000"/>

</br>

### Check the version of the git again:

Let's check to see if `cmake` is installed successfully:

```sh
$ cmake --version
```

<img src="images/win_images/cm-02-cmake_version.png" alt="cmake_version" width="1000"/>

---

</br>

<a name="win_installing_mingw"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Install MinGW ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

### Is `MinGW` installed?

Let's check to see if `g++` is installed on your system:

```sh
$ g++ --version
```

If you do not get a response similar to this, then you do not have `g++` and/or `MinGW` on your system and you have to install it.

<img src="images/win_images/g++-00-g++_version.png" alt="g++_version" width="1000"/>

</br>

### Download `MinGW`

Download cmake from [here](https://sourceforge.net/projects/mingw/files/). You should get an exe named similar to this: `mingw-get-setup.exe`

</br>

### Install `MinGW`/`g++`

Open/Run the executable file, and follow the steps to install.

<img src="images/win_images/g++-01-download_00.png" alt="g++_install" width="300"/>

<img src="images/win_images/g++-01-download_01.png" alt="g++_install" width="300"/>

</br>

The default Installation location should be `C:/MinGW`. Once again, you can add a Desktop shortcut, but it will not be necessary for this class.

<img src="images/win_images/g++-01-download_02.png" alt="g++_install" width="1000"/>

</br>

If you get a warning that MinGW is already installed, you can either reinstall and continue with this walk through or choose `Run Now` and skip to the steps below with the MinGW Install Manager.

<img src="images/win_images/g++-01-download_03.png" alt="g++_install" width="1000"/>

</br>

Installing...

<img src="images/win_images/g++-01-download_04.png" alt="g++_install" width="1000"/>

</br>

When it is done installing, click Continue.

<img src="images/win_images/g++-01-download_06.png" alt="g++_install" width="1000"/>

</br>

The **MinGW Installation Manager** should be opened up automatically. For this class, you will need mingw32-base, mingw-gcc-g++, and mingw23-gcc-objc.

<img src="images/win_images/g++-02-selection_00.png" alt="g++_install" width="1000"/>

</br>

To select a package for installation, right click on it in the menu and select Mark for Installation.

<img src="images/win_images/g++-02-selection_01.png" alt="g++_install" width="1000"/>

</br>

Marked packages will be selected like this:

<img src="images/win_images/g++-02-selection_02_zoom.png" alt="g++_install" width="1000"/>

</br>

You **also** need to select the pthreads package from under <br/>
All Packages -> MinGW Libraries

<img src="images/win_images/99-01-pthread.png" alt="g++_install" width="1000"/>

</br>

Once all necessary packages have been marked, go to Installations > Apply Changes to install.

<img src="images/win_images/g++-02-selection_03.png" alt="g++_install" width="1000"/>

</br>

Click Apply

<img src="images/win_images/g++-02-selection_04.png" alt="g++_install" width="1000"/>

</br>

Once the changes are applied you may close the Installation Manager.

<img src="images/win_images/g++-02-selection_07.png" alt="g++_install" width="1000"/>

</br>

### Add g++ as a System Variable and to your path

Search for "path" in the task bar search box. Open Edit the system environment variables.

<img src="images/win_images/g++-03-path_00.png" alt="g++_path" width="600"/>

</br>

Click on "Environment Variables..."

<img src="images/win_images/g++-03-path_01.png" alt="g++_path" width="600"/>

</br>

Add the path to the gcc and g++ executables to environment variables as shown below and press OK.

<img src="images/win_images/g++-03-path_02.png" alt="g++_path" width="600"/>

</br>

Next, double click on the **user variable** Path (in the top half of the window). A window like this should pop up:

<img src="images/win_images/g++-03-path_before.png" alt="g++_path" width="600"/>

</br>

Click New, and enter `C:\MinGW\bin` to the text box. Click OK.

<img src="images/win_images/g++-03-path_after.png" alt="g++_path" width="400"/>

</br>

Your environment and user variables should look like this after you are done:

<img src="images/win_images/g++-03-path_03.png" alt="g++_path" width="400"/>

</br>

### Check the version of the g++ again:

To make sure `MinGW`/`g++` is installed correctly, if the version output doesn't show, reboot your machine and try again.

```sh
$ g++ --version
```

<img src="images/win_images/g++-00-g++_version.png" alt="g++_path" width="1000"/>

---

</br>

<a name="win_accepting_the_assignment"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Accept the assignment ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

Here is the **assignment link** for [CS3A]() and here is the link for [CS8]()

</br>

### Accept assignment

1. Click on the assignment link.
1. Select yourself from the list with your name.
1. Click on the green button, `Accept this assignment`  to accept the assignment.

<img src="images/mac_images/a-00-accept_assignment.png" alt="accept_assignment" width="1000"/>

</br>

This will create a repo under your github username. The name of repo will be the name of assignment followed by your github name.

> `00_lab_0-stephengineer`

</br>

### Assignment repo

Once you accepted the assignment, github will begin to create your assignment repo and give it a few seconds, then:

1. Refresh this page to see updates.
1. Click the link of repo.

<img src="images/mac_images/a-04-reload_to_update.png" alt="reload_to_update" width="1000"/>

</br>

__Note__: Bookmark this page to know how to get here. We'll need to check in here soon.

<img src="images/mac_images/a-06-your-repo.png" alt="your-repo" width="1000"/>

---


</br>

<a name="win_cloning_the_assignment"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Cloning the assignment ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

### Get git link of assignment

1. Click on the green `Code` button on the mid-right.
1. Click the little clipboard and that will copy the link into your clipboard so you can paste it in the next step. 

<img src="images/mac_images/a-07-copy_clone_link.png" alt="copy_clone_link" width="1000"/>

</br>

### Clone assignment

Before you can work on your project, you will need a local copy of the assignment. This is called **clone** the repository.

```sh
# create and go the the directory of projects
$ cd /Users/stephen/CS3A/

# clone repo
$ git clone https://github.com/stephengineer-CS003A/00_lab_0-stephengineer.git
```

---

</br>

<a name="win_project_organization"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Project Organization ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

### Open assignment with VSCode

Open VSCode and loads the project folder

```sh
# go the project folder
$ cd 00_lab_0-stephengineer

# open VSCode
$ code .
```

<img src="images/mac_images/01-vscode_after_cloning.png" alt="vscode_after_cloning" width="1000"/>

</br>

### File system

All the projects in this class will follow the same file organization.

On the left panel (Explorer) you will find the `main.cpp` on the root folder, and the three most important folders in this directory:

- `_tests`: holds your google test files. The grader will run these files to obtain your score. You will ignore `testA.cpp` for the most part. The bulk of your work will be done in `testB.cpp`.

- `includes`: contains a folder for each of the libraries/classes your project depends on. In this starter code, you only have a `stub` folder that contains `stub.h` and `stub.cpp`. These files are `#include`d in `testB.cpp`

- `build`: is where you go to build and run your project. This is where all your compiled and executable files will end up.

<img src="images/mac_images/02-vscode_file_structure.png" alt="vscode_after_cloning" width="200"/>

</br>

### Test files

#### basic_test.cpp: Prof's sample test go here

> This is the placeholder file for a sample test file you will be given for each and every project. The purpose of this file is to demonstrate the functionality of the project and for you to make sure that your function signatures and class declarations match the grader's expectations. (otherwise, your projects will not earn a score.)

#### testB.cpp: student's tests go here

> This is the file that will contain the tests of your own functions and classes. All your test files that will demonstrate the correctness of your project are housed here. Part of your grade relies on the quality and success of the tests in this file.

</br>

### List of cpp files

#### stub.h, stub.cpp

> Not too much to see here. The stub is used in testB to demonstrate how a function will be tested by the google test framework in `testB.cpp`. All your functions and classes will be housed under their own folder (`stub/`, `array_functions/`, `vector/`, etc.) which will, in turn, go under the `includes/` folder.

</br>

### CMake file

#### CMakeLists.txt

> The github grader as well as your local Mac or linux systems will use the CMakeLists.txt file to build your project.

---

</br>

<a name="win_git_commands"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Git commands ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

One of the main tasks in this class is tracking changes made to the project. We need to know what happened when and what changed. This is both for your peace of mind (helps you not lose your project accidentally) and for me to track your progress through the course. We use [git](https://git-scm.com/) to track changes.

__Here__, we will make some small change to one of our files and walk through the entire process of tracking that change with `git`, just so you can get used to it.

</br>

### Check status

```sh
# show the working tree status
$ git status
```

Look at the response: It says there is not change as of yet. That's correct. We have not made any changes.

<img src="images/mac_images/c-00-git_status_1.png" alt="git_status" width="1000"/>

</br>

### Edit the README.md
1. Enter your name in the README.md and save it.
2. `$ git status` again.

After you run `$ git status` again, you will see that git has kept track of our changes. This time, it says that the file `README.md` has changed, but the `changes is not staged for commit`.

</br>

### Git workflow

As usual, one picture is worth a thousand words:

<img src="images/mac_images/c-00-git_workflow.png" alt="git_workflow" width="1000"/>

</br>

You go from zone to zone by the [git commands](https://git-scm.com/docs).

```sh
# show the working tree status
$ git status

# to see differences
$ git diff

# to stage all different files
$ git add .

# record changes to the repository
$ git commit -m "comments of changes"

# update code to remote repo
$ git push origin master

# show commit logs
$ git log
```

</br>

Now, Github knows about your changes, take a look at your project repo on Github to see how the changes you made to README.md.

__Note__: `commit` and `push` often: make sure you `commit` your changes after completion of __every__ task. Remeber, `commit`s are the record of your progress. You will be graded on your commits and push your changes frequently.

</br>

### Bonus

- Try to learn git [branches](https://www.atlassian.com/git/tutorials/using-branches).

---

</br>

<a name="win_build_and_run_walkthrough"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) build and run walkthrough ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

Once your project is open in VS Code, we will do a quick excersise to show you how to run it.
<br/><br/>

> <img src="images/win_images/run-00-running_compiling_00.png" alt="vscode_after_cloning" width="1000"/>

</br>

</br></br></br>

## The batch files:

The two batch files gtest.bat and build.bat should look like this:
gtest.bat:

```
git clone https://github.com/google/googletest.git
cd googletest && mkdir build && cd build && cmake -G "MinGW Makefiles" .. && make && cd ../../
```

if this gives you trouble, try replacing make with MinGW32-make like this:

```
git clone https://github.com/google/googletest.git
cd googletest && mkdir build && cd build && cmake -G "MinGW Makefiles" .. && MinGW32-make && cd ../../
```

build.bat:

```
g++ -std=gnu++11 -o basic_test ../_tests/_test_files/basic_test.cpp -Igoogletest/googletest/include -pthread -Lgoogletest/build/lib -lgtest
g++ -std=gnu++11 -o testA ../_tests/_test_files/testA.cpp ../includes/stub/stub.cpp -Igoogletest/googletest/include -pthread -Lgoogletest/build/lib -lgtest
g++ -std=gnu++11 -o testB ../_tests/_test_files/testB.cpp ../includes/stub/stub.cpp -Igoogletest/googletest/include -pthread -Lgoogletest/build/lib -lgtest

```

<a name="win_build_googletesr_framework"></a>

## Build the googletest framework

Before you can run your tests on your program, you must build the googletest framework. This has to be done only once per project **before** you do anything else.

To simplify this process, and the building of your project, a pair of batch files have been written.

The two .bat files you will use to build and compile your project: gtest.bat and build.bat will be included with your startup code for every project.

Navigate into the build folder and run gtest.bat by entering .`\gtest.bat` into the terminal. This will run a series of commands that build the googletest framework for you. This process creates a bunch of files and you do not want these files in the root folder of your project. Running the `gtest.bat` file from `build/` will make sure all your auxilary files are created inside the `build/` folder. The output should look like this.
<br/><br/>

> <img src="images/win_images/run-00-running_compiling_02.png" alt="vscode_after_cloning" width="1000"/>

</br>

build.bat needs to be run every time you make changes to your code. It creates executable files that you can run in the terminal. Run build.bat by entering `.\build.bat` into the VS Code terminal. It will create 3 executable files: testA.exe, testB.exe, and basic_test.exe.

Once your executables have been sucessfully created, you can run the basic_test.exe by entering `.\basic_test.exe` into the VS Code terminal.
<br/><br/>

> <img src="images/win_images/run-00-running_compiling_03.png" alt="vscode_after_cloning" width="1000"/>

</br>

# <BR><BR><BR><BR><BR>

<a name="win_getting_started_with_the_project"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Getting started with the project ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

## Find <a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a>

</br>

You will be supplied with a <a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a> file. You will copy this file and overwrite the existing _generic_ `basic_test.cpp` in your project folder. After this, you will **never** edit the `basic_test.cpp` file.

<a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a> demonstrtes the functionality of the project and gives you an opportunity to make sure your function signatures and class declarations match those of the grader.
You should be able to compile and run the `basic_test.cpp` with your functions.

Pay special attention to the `#include` path at the top. Your file structure has to be **exactly** the same as the one depicted here.

###### click <a href="./basic_test.cpp" target="_blank">here</a> to download basic_test.cpp if you have not already.

<br/><br/>

> <img src="images/win_images/test-00-basic_test_00.png" alt="vscode_after_cloning" width="1000"/>
> </br>

## Add a new folder to the `includes/` folder.

name this folder `array_functions`.

This is where you will add your `.h` and `.cpp` files

<br/><br/>

> <img src="images/win_images/test-00-basic_test_01.png" alt="vscode_after_cloning" width="1000"/>
> </br>

## Add two files to this folder.

Name these two files `array_functions.h` and `array_functions.cpp`

<br/><br/>

> <img src="images/win_images/test-00-basic_test_02.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Add the function signatures.

add these function signatures to the `array_functions.h` file:

```
void _array_init(int a[], int size, int x=0);
void _append(int a[], int& size, int append_me);
int _find(const int a[], int size, int find_me);
int& _at(int a[], int size, int pos);
ostream& _print_array(const int a[], int size, ostream& outs = cout);

```

Normally, you will either be given these function signatures or you will _deduce_ them from the code in `basic_test.cpp`

<br/><br/>

> <img src="images/win_images/test-00-basic_test_03.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Write function _stubs_

Function stubs are just function signatures with a return statement if needed.

Function stubs are a quick way to get the project up and running. I find the students who adopt this method in their workflow have an easier time completing projects.

### TIP:

I normally copy the function signatures and paste them into the `.cpp` file. Then, I replace the `;` at the end of the line with braces (`{}`). Then, I add the returns whenever necessary.

<br/><br/>

> <img src="images/win_images/test-00-basic_test_04.png" alt="vscode_after_cloning" width="1000"/>
> </br>

## Build googletest framework

</br>

</br>

## Go to `build/` and run `gtest.bat`:

`cd` into the `build/` folder, and from there, run `.\gtest.bat` Remember, you only do this per project. So, if you have already done this in the previous steps, you should skip it.

Now, we are ready to compile our project using `.\build.bat`

If you followed these steps faithfully, you will have the same syntax errors that I had, namely that all those functions we defined in `array_functions.h` and `.cpp` are **undefined!**

<br/><br/>

> <img src="images/win_images/test-00-basic_test_06.png" alt="vscode_after_cloning" width="1000"/>

</br>

## `build.bat` errors, zoomed in:

Here is a closer, more readable look at the errors reported by `.\build.bat`

<br/><br/>

> <img src="images/win_images/test-00-basic_test_07_zoom.png" alt="vscode_after_cloning" width="1000"/>

</br>

## the batch file

We will spare you the suspense. The reason for this error is that we never added `array_functions.cpp` to our `build.bat`.

A brief explanation of the line of code in buld.bat follows:
<br/>
`g++ -std-gnb++11 -o basic_test ../_tests/_test_files/basic_test.cpp ../includes/stub/stub.cpp -Igoogletest/googletest/include`

`basic_test` in this command is the name of the executable that will be created.

Starting from `-Igoogletest/googletest/include`, there is nothing you need to change in the line. This is a googletest option.

**All .cpp** files must be listed in the build.bat between the executable name and the googletest options at the end of each command.

<br/><br/>

> <img src="images/win_images/test-00-basic_test_08.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Editing the batch file

<br/><br/>

> <img src="images/win_images/test-00-basic_test_09_zoom.png" alt="vscode_after_cloning" width="1000"/>

</br>

## back at the `CMakeLists.txt`:

Even you, who uses windows and may not have any use for the `CMakeLists.txt` _locally_, **MUST** make sure `CMakeLists.txt` reflects the current state of your project. Otherwise, the grader will not be able to compile and run your project.

Notice that we are missing the `array_functions.cpp` from the `basic_test` `ADD_EXECUTABLE` statement:

So, let's add it...
<br/><br/>

> <img src="images/win_images/test-00-basic_test_10.png" alt="vscode_after_cloning" width="1000"/>
> </br>

</br>
</br>

## Add `array_functions.cpp` to the `ADD_EXECUTABLE(basic_test... )`

**Do not** use commas to separate the files.

**Do NOT** include `.h` files.

Normally, **all** three executables will need all the `.cpp` files

<br/><br/>

> <img src="images/win_images/test-00-basic_test_11.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-00-basic_test_12.png" alt="vscode_after_cloning" width="1000"/>
> </br/>

## `.\build.bat` again:

Let's run `.\build` again and pray that...

... and, we have more syntax errors. Default arguments can only be specified in the declration of the function and **not** in the definition.

So, we must remove all those default values for the defalut arguments on every function.

<br/><br/>

> <img src="images/win_images/test-00-basic_test_13.png" alt="vscode_after_cloning" width="1000"/>
> </br>

## Fix the `_print_array` function...

<br/><br/>

> <img src="images/win_images/test-00-basic_test_14.png" alt="vscode_after_cloning" width="1000"/>
> </br>

## by removing the default value `= cout`

## Same with `_array_init`:

<br/><br/>

> <img src="images/win_images/test-00-basic_test_15.png" alt="vscode_after_cloning" width="1000"/>
> </br>

## `.\build.bat` one more time:

and this time it will run successfully.

This is a huge step. We now have a working project eventhough our functions are basically empty.

You can even run `basic_test.exe`. Of course this will not run satisfactorily. You will get mostly garbage. -afterall, we are running on stubs!- but it **does** run!!

<br/><br/>

> <img src="images/win_images/test-00-basic_test_16.png" alt="vscode_after_cloning" width="1000"/>
> </br>

</br>

## run `git status`, `add`, and `commit` with the message _success on make with stubs_

### The importance of having **regular** `commit`s in your project cannot be overstated. This is a large part of the evaluation of your project by me.

</br></br>

> <img src="images/win_images/test-00-basic_test_18.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-00-basic_test_19.png" alt="vscode_after_cloning" width="1000"/>

</br><br/>

## Implement `_array_init` and `_print_array`. `testB.cpp` can be seen waiting to host the test functions.

Now, we can go in and implement the functions one by one and write tests for them. These tests will be written in the `testB.cpp` file.

</br>

---

# <BR><BR><BR><BR><BR>

<a name="win_writing_tests"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Writing Tests: ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

<br/>
</br>

## `testB`: Our first test:

After implementing the \_array_init and \_print_array functions, we will write a simple test that will verify that the \_init function works as it should.

The test function is boolean. It returns `true` if the init function works properly and false otgherwise.

Call the `_array_init` function and then go through each and every cell and verify that each element is -1.

If you find one cell that is not -1, return false.

Note also that we return `true` at the end of the test function. I do this in every test function I write.

<br/>

</br>

## The `TEST` function:

The `TEST` function is part of the googletest testing framework. To simplify our work, we always use the same format for the `TEST` function: Declare a `bool success` and assign it to the return value of the test function.

Then, compare `success` with `1` or `true`

A quick word about the two arguments of the `TEST` function:

The first is the name of the _test suit_ and the second is the name of this very test. Each test suit may contain multiple tests. Later, we will write another test for the `_append` function with the same first argument as this test: `TEST_ARRAY`. By the time we are done, the `TEST_ARRAY` test suite will have three individual tests.

Pay attention to the **naming conventions** for this course: The test suite will be in ALL CAPS with underscores between the words. The test names will be camel case and regular function names are all lower case with underscores.
<br/><br/>

> <img src="images/win_images/test-01-testb_test_init_00.png" alt="vscode_after_cloning" width="1000"/>
> </br>

## build and RUN!!

This time, we will run `.\build.bat` successfully and then, we run the `testB` executable by typing `.\testB.exe`

This will display two successful test runs: one for the `stub` test that was already part of the project, and one for the `TestInit` that we just wrote.

This means that our test function returned `true`.

<br/><br/>

> <img src="images/win_images/test-01-testb_test_init_01.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-01-testb_test_init_03.png" alt="vscode_after_cloning" width="1000"/>
> </br>

## Implement `_append` and `_at`:

We have thus far implemented `_array_init` and `print_array`. Let's implement `_append` and `_at` as well.

You will _borrow_ my code for this particular lab, but make sure you comment the code very well.

Once we have implemented `_append`, write the test for it in `testB.cpp`. Don't forget to add a `TEST( )` for the `test_append()` function.

<br/><br/>

> <img src="images/win_images/test-02-testb_test_append_00.png" alt="vscode_after_cloning" width="1000"/>

<br/><br/>

Obviously, this is done in the `testB.cpp` file. Again, do not forget to add the `TEST( )` function for `test_at()`

Once again, you will _borrow_ my code for this particular lab, but make sure you comment the code very well.

<br/><br/>

> <img src="images/win_images/test-02-testb_test_append_001.png" alt="vscode_after_cloning" width="1000"/>

<br/><br/>

## `.\build.bat` and run `testB.cpp` again:

Let's `.\build.bat` and run `testB` to make sure our `test_append` and `test_at` pass:

<br/><br/>

> <img src="images/win_images/test-02-testb_test_append_003.png" alt="vscode_after_cloning" width="1000"/>

---

# <BR><BR><BR><BR><BR>

<a name="win_completing_the_project"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Completing the project ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

## Implement the `_find()` function on your own

You will also write a `test_find()` function. Once you have implemented `_find()` and written the test function for it (don't forget to comment) you are ready to `.\build.bat` and run `testB` once again.

Once you have successfully run `testB` with `_find`, you `git add ` and ` commit` your changes. Once again, do not forget to update your CMakeLists.txt file for the autograder.

<br/><br/>

> <img src="images/win_images/test-03_commit_push_00.png" alt="vscode_after_cloning" width="1000"/>

<br/><br/>

## Finally, we can run `basic_test.cpp`:

Now that we have implemented all the functions that are used in `basic_test.cpp`, we can `make` and run this file.

I cannot overemphasize how important it is for this test to be able to compile and run **without** your editing it in any way. If your project cannot compile and run `basic_test`, the grader will not be able to run your project.

<br/><br/>

> <img src="images/win_images/test-03_commit_push_01.png" alt="vscode_after_cloning" width="1000"/>

<br/><br/>

## `git add` and the final `git commit`

Let's go back to the root directory by typing `cd ..` - remember that `..` means parent directory. `cd ..` means change directory to the parent.

My commit message will let me know what stage of the development I am in. I have just PASSED both the `basic_test` and `testB`

<br/><br/>

> <img src="images/win_images/test-04_reslts_github_01.png" alt="vscode_after_cloning" width="1000"/>

</br>

## Autograder Status

You can keep track of the grading status of your project on the assigmment page. A yellow dot means that the tests are still being compiled and run by the autograder.This shouldn't take more than a minute or two. You can refresh the page to update the status. A green checkmark neans that all your tests have passed. A red x means that at least one test failed.

<br/><br/>

> <img src="images/win_images/test-04_reslts_github_02.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_04.png" alt="vscode_after_cloning" width="1000"/>

</br>

To see a more in depth output of the autograder test runs, click on the Details link:

<br/><br/>

> <img src="images/win_images/test-04_reslts_github_05.png" alt="vscode_after_cloning" width="1000"/>

</br>

It will take you to this page:
<br/><br/>

> <img src="images/win_images/test-04_reslts_github_07.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_08.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_10_zoom.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_11_zoom.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_12.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_13.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_reslts_github_15.png" alt="vscode_after_cloning" width="1000"/>
