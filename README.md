### Tempel-CLI uses Python
=========
#### Dependencies:
* python
* requests

#### Usage:

```
	tempel [options]
	tempel -l <lang> namefile
    echo "Hello world" | tempel -l <lang>
    dmesg | tempel

Options:

	-h, --help             output usage information
	-v, --version          output the version number
	-l, --language <lang>  Set language;
    bash c cpp css diff html html+django ini java
    lua make perl php python rst ruby sql text xml yaml
	-t, --text <text>      from text
	<filename>             from filename directly
```

### License MIT
Project License can be found [here](LICENSE.md).
