# Linux debian package



I wrote a sample Debian package structure to make it understandable in its simplest form.

### Download
```console
git clone https://github.com/diloabininyeri/hello.git

chmod 755 -R hello/ #change the permissions
```

### Build 
```console
dpkg-deb --build hello
```
>You can install the created deb file with apt-get or double click.


### Test
Just type hello command in the terminal after the installation of the package
```console
hello
```
