# To-Do List Application (C++)

A beginner C++ console application that manages a list of tasks using a vector.

## What it does

- Add tasks with descriptions
- View all numbered tasks
- Remove a completed task by its number
- Exit the program

The task list lives in memory for the duration of the session.

## Who it's for

Students learning C++ basics: `std::vector`, strings, loops, switch statements,
and console I/O.

## Features

- Interactive menu (add / view / remove / exit)
- Dynamic task storage (`std::vector<std::string>`)
- Input validation for task selection (rejects out-of-range numbers)
- Empty-list handling for view and remove

## Compile and run

Prerequisites: a C++ compiler (e.g. `g++`).

```bash
# clone
git clone https://github.com/subhanbhatti50134-jpg/To-Do-List-Application.git
cd To-Do-List-Application

# compile
g++ "Project code" -o todo

# run
./todo
```

Windows (PowerShell):

```powershell
g++ "Project code" -o todo.exe
.\todo.exe
```

## Notes

- Tasks are held in memory only; they are not saved to disk and are lost when
  the program exits. (A good next step for extending the project.)
- The source file is named `Project code` (with a space), so it must be quoted
  when compiling.
- Compilation was not tested in this environment; the GitHub Actions workflow
  verifies it builds with `g++`.

## License

This repository does not yet carry an open-source license. See
`LICENSE_DECISION.md` for recommended options.
