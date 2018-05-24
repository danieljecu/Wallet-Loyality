# Wallet
# Loyality
@ Smart Cards and Applications Course

## [Run Wallet from Command line:](https://docs.oracle.com/javacard/3.0.5/guide/running-wallet-sample-command-line.htm)
* [a) Run `cref` from JC_CLASSIC_HOME//bin.](README.MD#a)
* [b) In `|applet` execute `ant all`](README.MD#b)

### a) Run `cref` from JC_CLASSIC_HOME//bin.

```cmd
C:\Program Files (x86)\Oracle\Java Card Development Kit 3.0.5u1\bin> cref
```

![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `Note`
> default.output will contain 
>```java.net.ConnectException: Connection refused: connect```
> if you don't start the CREF (javacard simulator).

Required file structure:
```
Wallet
	|applet
		|build.xml*
		|applet.opt*
		|src*
		|apdu_scripts
	|wallet.scr
```

### b) In `|applet` execute 
```
> ant all
```
* or just `ant` because by default is `all`. You'll notice that an `.output` file is generated.


```
Wallet
	|applet
		|...
		|default.output
	|wallet.scr
```

