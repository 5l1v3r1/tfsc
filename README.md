# tfsc - Temporary File Source Code (disclosure script)
Automated tool to find backup files that may disclose the website's source code.

## Usage example
tfcs.py is based in two required parameters (-u [url] and -f [file(s)]) and an optional one, -v (verbose):

```pyhton
python tfsc.py -u http://player.htb/launcher -f index.php,stats.php
```

![example](https://xh4h.com/img/upload/tfsc.png)

## Parameters
| Command                                                    | Description                                                             |
|------------------------------------------------------------|-------------------------------------------------------------------------|
| -f (--file)                                                | file (or comma separated list of files to be searched)                  |
| -u (--url)                                                 | base url                                                                |
| -v (--verbose)                                             | enable verbose debugging (accepts any value)                            |


## More info
More info about Temporary File Source Code Disclosure Vulnerability [here](https://www.rapid7.com/db/vulnerabilities/http-php-temporary-file-source-disclosure).
