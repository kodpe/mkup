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
# if your makefile is in your current folder, 
```
```
mkup [OPTION] [DIRECTORY]
```

```
default extension is '.cpp'
default source directory is 'DIRECTORY/src'
```

#### options
```
mkup  -s, --source-dir <src_dir>
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
