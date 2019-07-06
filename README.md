# Bash-TarTime

Simple tool for compressing files to an auto timestamped bz2 archive.

*Note: I use this script for my own projects, it contains only the features I need.*

## Table of Contents

[Installation](#installation) | [Features](#features) | [Test](#test) | [Contributing](#contributing) | [License](#license)

## Installation

Requires: a Debian/Ubuntu version of linux and a Bash version ~4.4.

1. [Download a release](https://github.com/ojullien/bash-tartime/releases) or clone this repository.
2. Use [scripts/install.sh](https://github.com/ojullien/bash-tartime/tree/master/scripts) to automatically install the application in the /opt/oju/bash project folder.
3. If needed, add `PATH="$PATH:/opt/oju/bash/bin"` to the .profile files.

## Features

This tool is a wrapper to the tar command. It allows you to compress files to an auto timestamped bz2 archive.

```bash
Usage: tartime.sh <destination> <source1> [source2] ...

  <destination>   Destination archive: destination-hostname-YYYYMMDD_HHMM.tar.bz2.
  <source>        Source to compress.
```

## Test

As this tool is just a wrapper to the tar command, I didn't write any line of 'unit test' code. Sorry.

## Contributing

Thanks you for taking the time to contribute. Please fork the repository and make changes as you'd like.

As I use these scripts for my own projects, they contain only the features I need. But If you have any ideas, just open an [issue](https://github.com/ojullien/bash-tartime/issues/new) and tell me what you think. Pull requests are also warmly welcome.

If you encounter any **bugs**, please open an [issue](https://github.com/ojullien/bash-tartime/issues/new).

Be sure to include a title and clear description,as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.

## License

This project is open-source and is licensed under the [MIT License](https://github.com/ojullien/bash-tartime/blob/master/LICENSE).
