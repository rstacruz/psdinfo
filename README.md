# psdinfo

> Inspect PSD files from the command line.

![](https://www.evernote.com/l/AYOnmuV6pJVANbUk4XIDCtYEUh5XH2onzJkB/image.png)

```
npm install -g psdinfo
```

```sh
$ psdinfo file.psd --fonts

# file.psd
fonts:
  - DIN-Bold
  - FreightSansLight
  - Glosa-Roman
  - ...
```

```sh
$ psdinfo file.psd --text

# file.psd
text:
  - "Hello"
  - "This is text from the document"
  - ...
```

<br>

## Thanks

**psdinfo** © 2015+, Rico Sta. Cruz. Released under the [MIT] License.<br>
Authored and maintained by Rico Sta. Cruz with help from contributors ([list][contributors]).

> [ricostacruz.com](http://ricostacruz.com) &nbsp;&middot;&nbsp;
> GitHub [@rstacruz](https://github.com/rstacruz) &nbsp;&middot;&nbsp;
> Twitter [@rstacruz](https://twitter.com/rstacruz)

[MIT]: http://mit-license.org/
[contributors]: http://github.com/rstacruz/psdinfo/contributors
