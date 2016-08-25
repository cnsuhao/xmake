---
layout: default
title: {{ site.name }}
---

## Simple description

```lua
    target("console")
        set_kind("binary")
        add_files("src/*.c") 
```

## Build project

```bash
   $ xmake
```

## Run target

```bash
   $ xmake run console
```

## Support features

* Tasks
* Macros
* Actions
* Options
* Plugins
* Templates

## Support platforms

* Windows (x86, x64, amd64, x86_amd64)
* Macosx (i386, x86_64)
* Linux (i386, x86_64, cross-toolchains ...)
* Android (armv5te, armv6, armv7-a, armv8-a, arm64-v8a)
* iPhoneOS (armv7, armv7s, arm64, i386, x86_64)
* WatchOS (armv7k, i386)
* Mingw (i386, x86_64)

## Support Languages

* C/C++
* Objc/Objc++
* Swift
* Assembly

## Builtin Plugins

* Macros script plugin
* Run the custom lua script plugin
* Generate IDE project file plugin（makefile, vs2002 - vs2008, developing vs2010 .. ）
* Generate doxygen document plugin

## In the plans

* Manage package and dependencies
* Download package automatically
* Create package repository for porting other third-party source codes, it's goal is that one people port it and many people shared.
* Implement more plugins

