# Stegano

> Embed data in files using steganography.


## Install

```
$ curl https://raw.githubusercontent.com/kjbrum/stegano/master/stegano > ~/bin/stegano
$ chmod +x ~/bin/stegano
```


## Usage

```
Stegano

Embed data in files using steganography.

Usage:
    $ stegano

Options:
    --data=<path/to/file>     Path to the data file that will be embedded
    --embed=<path/to/file>    Path to the file to embed the data in
    --help                    Display the help text

Examples:
    $ stegano
    $ stegano --data=secret.zip --embed=image.jpg
```


## Extracting Data

You can extract the embedded data by running the following on the resulting file:

```
unzip <filename>
```

[Learn more about steganography.](https://en.wikipedia.org/wiki/Steganography)


## License

Copyright © [Kyle Brumm](http://kylebrumm.com). Free to use on whatever and may be redistributed under the terms specified in the [license](LICENSE.md).
