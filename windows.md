# Windows Instructions</br>

- ### [Installing `git`](#win_installing_git)</br>
- ### [Installing `cmake`](#win_installing_cmake)</br>
- ### [Installing `MinGW`](#win_installing_mingw)</br>

- ### [Accepting the assignment](#accepting_the_assignment)</br>
- ### [Cloning the assignment](#cloning_the_assignment)</br>
- ### [Project organization](#project_organization)</br>
- ### [Git commands](#git_commands)</br>
- ### [Getting started with the project](#getting_started)</br>
- ### [Completing the project](#completing_the_project)</br>

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

<a name="accepting_the_assignment"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Accepting the assignment ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

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

<a name="cloning_the_assignment"></a>

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

<a name="project_organization"></a>

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

<a name="git_commands"></a>

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

<a name="getting_started"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Getting started ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

### Step 1: Find <a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a>

You will be supplied with a <a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a> file. You will copy this file and overwrite the existing _generic_ `basic_test.cpp` in your project folder. After this, you will __NEVER__ edit the `basic_test.cpp` file.

<a href="./basic_test.cpp" target="_blank">`basic_test.cpp`</a> demonstrtes the functionality of the project and gives you an opportunity to make sure your function signatures and class declarations match those of the grader.
You should be able to compile and run the `basic_test.cpp` with your functions.

Pay special attention to the `#include` path at the top. Your file structure has to be __exactly__ the same as the one depicted here.

###### click <a href="./basic_test.cpp" target="_blank">here</a> to download basic_test.cpp if you have not already

<br>

### Step 2: Create project folder

Create a new function folder under the `includes/` folde and name this folder to `array_functions`. This is the directory you will add your `.h` and `.cpp` files.

<br>

### Step 3: Add two project files

Add two files in the project folder:

- `array_functions.h`
- `array_functions.cpp`

<img src="images/mac_images/08-project_folder.png" alt="project_folder" width="200"/>

</br>

### Step 4: Add the function signatures

Add these function signatures to the `array_functions.h`

```c++
#ifndef ARRAY_FUNCTIONS_H
#define ARRAY_FUNCTIONS_H

#include <iostream>
#include <iomanip>

using namespace std;

//initialize the first size elements of the array
void _array_init(int a[], int size, int x=0);
//add append_me to the end of the array and size++
void _append(int a[], int& size, int append_me);
//return index of find_me -1 if not found
int _find(const int a[], int size, int find_me);
//return item at index pos
int& _at(int a[], int size, int pos);
//print the array
void _print_array(const int a[], int size);

#endif // ARRAY_FUNCTIONS_H
```

Normally, you will either be given these function signatures or you will _deduce_ them from the code in `basic_test.cpp`

</br>

#### Tips

I normally copy the function signatures and paste them into the `.cpp` file. Then, I replace the `;` at the end of the line with braces (`{}`). Then, I add the returns whenever necessary.

__Note__: removing the default value of x in `_array_init`

```c++
#include "array_functions.h"

void _array_init(int a[], int size, int x) {

}

void _append(int a[], int &size, int append_me) {

}

int _find(const int a[], int size, int find_me) {
    return 0;
}

int& _at(int a[], int size, int pos) {
    return a[0];
}

void _print_array(const int a[], int size) {
    cout << endl;
}
```
</br>

### Step 5: Open terminal

If you are using VSCode, you can open the terminal by pressing [`ctrl`]+[`]

[`] is the key in the top left of the keyboard

Using the terminal in this way is very convenient.

</br>

### Step 6: Build project

```sh
# under project folder: ./00_lab_0
# create build folder
$ mkdir build

# go to build folder
$ cd build

# cmake project
$ cmake ..
```

This will run `cmake` on your _parent_ folder. (that's what `..` means, `cmake ..` means run `cmake` on my parent folder) `cmake` creates a bunch of files and you do not want these files in the root folder of project. Running `cmake` from `build/` will make sure all your auxiliary files are created inside the `build/` folder.

Hopefully, your `cmake` will run without any problems and it will tell you that "Build files are written to `. . . build/`"

</br>

### Install cmake tools

Another method to build project. If you have not already install CMake and CMake Tools in VS Code:

1. On the left of VS Code, click on `extensions`.
1. Search `cmake`.
1. Install `CMake` and `CMake Tools`

<img src="images/mac_images/b-02-cmake_tools_1.png" alt="cmake_tools"/>

</br>

#### Rebuild
You should be able to right click on `CMakeLists.txt` and click on `Clean Reconfigure All Projects`:

<img src="images/mac_images/b-02-cmake_tools_2.png" alt="cmake_tools" width="400"/>

</br>

A prompt should appear on top, just click on similar compiler to:

- MAC: `Clang 13.0.0`
- WIN: `GCC 6.3.0 mingw`


<img src="images/mac_images/b-02-cmake_tools_3.png" alt="cmake_tools" width="1000"/>

<img src="images/mac_images/b-02-cmake_tools_4.png" alt="cmake_tools" width="1000"/>

</br>

If it does not show up, you will need to manually select it on the bottom there is a button as shown:

<img src="images/mac_images/b-02-cmake_tools_5.png" alt="cmake_tools"/>

</br>

- If it does not show `Clang 13.0.0` or `GCC 6.3.0 mingw32` click on that button and select it.
- If there is no option, try scanning for kits and try again.
- If it still doesn’t show up, you probably messed up your Mingw installation.

The output should look something like this:

<img src="images/mac_images/b-02-cmake_tools_6.png" alt="cmake_tools" width="1000"/>

</br>

Some buttons should be on the bottom:

<img src="images/mac_images/b-02-cmake_tools_7.png" alt="cmake_tools" width="1000"/>

</br>

__Note__: With every future project, just `Clean Reconfigure All Projects` and everything should be more or less the same. __If there are any errors, just delete the build folder and retry__.

</br>

### Step 7: Compile project

Now, we are ready to compile project using `make`

```sh
# under project folder: ./00_lab_0

# compile project
$ make
```

<img src="images/mac_images/21-make.png" alt="make" width="1000"/>

</br>

### Step 8: Push changes to Github

Run git commands to commit changes:

```sh
$ git status
$ git add .
$ git commit - m "success on make with stubs"
```

__Note__: The importance of having __regular__ `commit`s in your project cannot be overstated. This is a large part of the evaluation of your project by me.

<img src="images/mac_images/22-git_add_commit.png" alt="git_add_commit" width="1000"/>

</br>

Now, you can implement functions one by one in `array_functions.cpp` and write tests in the `testB.cpp` file for it to complete the project.

---

</br>

<a name="completing_the_project"></a>

# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Completing the project ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)

</br>

### Writing tests

After implementing the `_array_init` and `_print_array` functions, we will write a simple test that will verify the function works as it should.

The test function is boolean. It returns `true` if the init function works properly and false otherwise.

Call the `_array_init` function and then go through each and every cell and verify that each element is -1. If you find one cell that is not -1, return false.

Note also that we return `true` at the end of the test function. I do this in every test function I write.

```c++
bool test_init_array(bool debug=false) {
  int a[20];
  int size = 5;
  const char tabs[] = "\t--------------------------\t";
  if (debug) {
    cout << tabs << "size: 5, init array to -1" << endl;
  }
  _array_init(a, size, -1);
  if (debug) {
    cout << tabs;
    _print_array(a, size);
    cout << endl;
  }
  for (int i=0; i<size; i++) {
    if (a[i] != -1) {
      cout << "FAILED: Expected -1 at a[" << i << "], but found: " << a[i] << endl;
      return false;
    }
  }
  return true;
}
```

</br>

### The `TEST`

The `TEST` function is part of the google test testing framework. To simplify our work, we always use the same format for the `TEST` function: Declare a `bool success` and assign it to the return value of the test function.

Then, compare `success` with `1` or `true`

A quick word about the two arguments of the `TEST` function:

- test suit
- test name

The first is the name of the _test suit_ and the second is the name of this very test. Each test suit may contain multiple tests. Later, we will write another test for the `_append` function with the same first argument as this test: `TEST_ARRAY`. By the time we are done, the `TEST_ARRAY` test suite will have three individual tests.

Pay attention to the _naming conventions_ for this course:

- __test suite__ will be in __ALL uppercase__ with underscores between the words.
- __test names__ will be in __camel case__.
- __test function names__ will be in __ALL lowercase__ with underscores between the words.

```c++
//Lord help me! 
const bool debug = false;

TEST(TEST_ARRAY, TestInit) {
  bool success = test_init_array(debug);
  EXPECT_EQ(success, true);
}
```

</br>

### make and run

This time, we will run `make` successfully and then, we run the `testB` executable by typing `./bin/testB`

This means execute the file named `testB` that is located in the `bin` folder which is under the `current folder`. The bin folder is created by `make`

remember that `.` means current folder and is not optional. You __must__ include the dot in the call to execute `testB`

This will display two successful test runs: one for the `stub` test that was already part of the project, and one for the `TestInit` that we just wrote.

This means that our test function returned `true`.

<img src="images/mac_images/27-make_run_testB.png" alt="make_run_testB" width="1000"/>

---

</br>

### Implement all functions

Let's implement all other functions in `array_functions.cpp`:

```c++
void _append(int a[], int& size, int append_me) {
  a[size] = append_me;
}

int _find(const int a[], int size, int find_me) {
  // Implement the _find() function on your own
}

int& _at(int a[], int size, int pos) {
    assert(pos<size);
    return a[pos];
}
```

### Writing all tests

Let's write all other test in `testB.cpp`:

```c++
bool test_append(bool debug=false) {
  int a[20];
  int size = 5;
  const char tabs[] = "\t--------------------------\t";
  if (debug) {
    cout << tabs << "size: 5, init array to -1" << endl;
  }
  _array_init(a, size, -1);
  if (debug) {
    cout << tabs;
    _print_array(a, size);
    cout << endl;
  }
  for (int i = size; i < 10; i++) {
    _append(a, size, i * 10);
    if (debug) {
      cout << tabs;
      _print_array(a, size);
      cout << endl;
    }
  }
  if (size != 10) {
    cout << "FAILED: Expected size to be 10, but found: " << size << endl;
    return false;
  }
  if (a[size-1] != (size-1)*10) {
    cout << "FAILED: Expected: " << (size-1)*10 
         << " at a[" << size-1 << "], but found: " << a[size-1] << endl;
    return false;
  }
  return true;
}

bool test_at(bool debug=false) {
  int a[20];
  int size = 5;
  const char tabs[] = "\t--------------------------\t";
  if (debug) {
    cout << tabs << "size: 5, init array to -1" << endl;
  }
  _array_init(a, size, -1);
  if (debug) {
    cout << tabs;
    _print_array(a, size);
    cout << endl;
  }
  int at_i;
  for (int i=0; i<size; i++) {
    at_i = _at(a, size, i);
    if (at_i != -1) {
      cout << "FAILED: Expected at{i} to return -1, but found: " << at_i << endl;
      return false;
    }
  }
  _at(a, size, 3) = 300;
  at_i = _at(a, size, 3);
  if (at_i != 300) {
    cout << "FAILED: Expected to find 300 at{3}, but found: " << at_i << endl;
    return false;
  }
  return true;
}

bool test_find(bool debug=false) {
  // Implement the _find() test function on your own
}
```

Obviously, you are done in the testB.cpp file, do not forget to add the `TEST()`  for all test functions.

Let's `make` and run `testB` to make sure all test functions pass.

<img src="images/mac_images/30-PASSED_three_tests.png" alt="PASSED_three_tests" width="1000"/>

</br>

Once you have successfully run `testB`, you can run git commands to commit changes:

```sh
# under project folder: ./00_lab_0

$ git status
$ git add .
$ git commit - m "success on make with stubs"
$ git push origin master
```

</br>

### Run `basic_test.cpp`:

Now that we have implemented all the functions that are used in `basic_test.cpp`, we can `make` and run this file.

I cannot overemphasize how important it is for this test to be able to compile and run __without__ your editing it in any way. If your project cannot compile and run `basic_test`, the grader will not be able to run your project.

<img src="images/mac_images/31-PASSED-basic_test.png" alt="PASSED-basic_test" width="1000"/>

</br>

# Autograder Status

You can keep track of the grading status of your project on the assignment page. A yellow dot means that the tests are still being compiled and run by the autograder.This shouldn't take more than a minute or two. You can refresh the page to update the status. A green checkmark means that all your tests have passed. A red x means that at least one test failed.

<br/>

> <img src="images/win_images/test-04_results_github_02.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_results_github_04.png" alt="vscode_after_cloning" width="1000"/>

</br>

To see a more in depth output of the autograder test runs, click on the Details link:

<br/>

> <img src="images/win_images/test-04_results_github_05.png" alt="vscode_after_cloning" width="1000"/>

</br>

It will take you to this page:
<br/>

> <img src="images/win_images/test-04_results_github_07.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_results_github_08.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_results_github_10_zoom.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_results_github_11_zoom.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_results_github_12.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_results_github_13.png" alt="vscode_after_cloning" width="1000"/>

</br>

> <img src="images/win_images/test-04_results_github_15.png" alt="vscode_after_cloning" width="1000"/>
