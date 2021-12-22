# ispx github.com/goplus/spx interp demo

### install ispx
```
go get github.com/visualfc/ispx
```
### ispx command
```
ispc [-dumpsrc|-dumppkg|-dumpssa] dir
  -dumppkg
    	print import packages
  -dumpsrc
    	print source code
  -dumpssa
    	print ssa code information
```

```
$ go get github.com/visualfc/ispx
$ git clone https://github.com/goplus/spx

// run and set spx demo directory
$ ispx spx/tutorial/04-Bullet

// run on current work directory 
$ cd spx/tutorial/04-Bullet
$ ispx .
```

