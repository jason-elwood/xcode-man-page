# Xcode Manpage

Xcode Manpage is the man page when didn't know we needed for Xcode.

## Installation

1) Create the directory:

```bash
sudo mkdir /usr/local/man/man1
```

2) Download the Xcode manpage:

Just click on the xcode.1.gz file and download it to your system.

3) Copy the manpage to your direcory:

```bash
sudo cp xcode.1.gz /usr/local/man/man1
```

4) Add new path to the /etc/man.conf file:

```base
sudo vim /etc/man.conf
# Add the following line where you see the other MANPATH entries:
MANPATH /usr/local/man
```

Now you can use the xcode manpage like so:

```bash
man xcode
```

That's all there is to it.


## Usage

```bash
man xcode
```

## Creator
Jason Elwood

## License
[MIT](https://choosealicense.com/licenses/mit/)
