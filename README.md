# SBT AutoJump Plugin
[![Build Status](https://travis-ci.org/luismfonseca/sbt-autojump.svg?branch=master)](https://travis-ci.org/luismfonseca/sbt-autojump)

For autojump-like jumps between sbt projects - no need to type the project full name as it will try
to guess the one you are referring to and switch to that project.

## Usage

```
> projects
[info] 	   bar
[info] 	   footprint
[info] 	 * root
> j print
[info] Set current project to footprint
> j br
[info] Set current project to bar
```

## Installing the plugin

### Stable version

Add the following line to one of these files:

- The project-specific file at project/sbt-j.sbt
- Your global file at ~/.sbt/0.13/plugins/sbt-j.sbt

```
addSbtPlugin("xyz.luisfonseca" % "sbt-autojump" % "1.0.1")
```
