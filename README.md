# Gorep - A Grep alternative written in Go

## Install from source

*Note: Golang v1.19+ must be installed.*

```bash 
git clone https://github.com/msharran/gorep.git
cd gorep
make install
```

## Usage

### Search a file

```bash
gorep foo foo.txt
```

### Pass file to STDIN

```bash
cat foo.txt | gorep foo
```

### Options

```bash
$ gorep -h
Usage of gorep:
  -c    Prints the searched line count. This will not print the search result
  -i    Case insensitive search
  -l    Prints line numbers along with the search result
```
