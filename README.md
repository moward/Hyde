# Hyde
Static website compiler written in Node.js for Battle of The Hacks hosted by Andreessen Horowitz.

![Hyde logo](https://raw.githubusercontent.com/moward/Hyde/master/logo.png)

# How to run

### Create Empty Project
Run Hyde init
```
$ node hyde init
```
Will create a new directory Hyde_Project, where all files can be added.

### Compile Project
To compile
```
$ node hyde compile (desired directory name)
```
### Custom Compile
To use custom directories
```
$ node hyde (desired source name) (desired target name)
```

# Features
Supports the following languages/pre-processors:
- Markdown
- Jade
- Less
- JSON Variables


Backlog:
- Github webhook
