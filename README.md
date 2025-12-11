# Lesson materials generator

## WebView engine for Linux: WebView engine

It is used for displaying web content inside desktop applications.

It is generally included in the operative system.

### Command to check if it is intalled

```sh
rpm -qa | grep webkit2gtk
```

## Development package webkit2gtk4.1-devel

Provides the header files and build metadata required for compiling applications that use the WebKitGTK 4.1 WebView engine.

### Installation command

```sh
sudo dnf install webkit2gtk4.1-devel
```

### Command to check installation

```sh
dnf list installed | grep webkit2gtk4.1-devel
```
