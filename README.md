# mkup
mkup - fast update or create a makefile

Automatically searches and updates source files (C++)

#### installation
```
./mkup
```

#### usage
```
mkup
# update a makefile in your current folder
```
```
mkup [DIRECTORY]
# otherwise you can specify a relative directory path
# default source directory is 'DIRECTORY/src'
```

#### options
```
mkup  -s, --source-dir <src_dir> [DIRECTORY]
# Specify the source directory, subfolders allowed
```
```
mkup --default-source-dir <src_dir>
# Change the default source directory.
```
```
mkup --default-extension <.extension>
# Change the default extension.
```

#### version
```
mkup.22.12.17
```
