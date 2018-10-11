# readme-badge
Python script to generate SVG badges. Right now we focus on coverage.


##Coverage

usage: coverage.py [-h] [-o FILEPATH] [c] [-p] [-f] [-q] [-v]

Generate coverage badges for test coverage.

```optional arguments:
  -h, --help         show this help message and exit
  -c COVERAGE        The coverage value for the file
  -cf COVERAGE_FILE  Path to the scala coverage file
  -o FILEPATH        Save the file to the specified path.
  -p                 Plain color mode. Standard green badge.
  -f                 Force overwrite image, use with -o key.
  -q                 Don't output any non-error messages.
  -v                 Show version.
```