This project is used for integration testing. Tested features:
- files in the folder are UTF-16LE with BOM
- parsing / ast construction / basic metrics like ncloc, classes etc.
- feeding of issues using:
  - a cppcheck report
  - a valgrind report
- unit test statistics, using the junitReport format
