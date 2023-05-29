# upaste

```
Paste client

  Usage :

    -h    Print this usage
    -a    Enable autocopy in clipboard
    -t    Set extension

  Use a $HOME/.paste.conf file to select a different paste service. List
  all URL choices there, one in each line. If a single URL is present
  that will be chosen. If more than one is present, a random working one
  will be chosen.

  Default is https://0x0.st/.

  Working instances are: https://x0.at/, https://ttm.sh/,
  https://0x0.st/, https://xzz.dk/, https://0.vern.cc/, https://envs.sh/
  and https://null.slipfox.xyz/.

  Examples:

      echo "Text here" | up
      cat file.[ext] | up [-t] [ext]
      up filename.[ext]

  Links are logged in $HOME/.paste
```
