# Library starter for Enonic XP

<img align="right" alt="Starter Lib Logo" width="128" src="./src/main/resources/assets/icon.svg">

This starter kit will set up the basics for creating a new library project for Enonic XP.

[See documentation for creating libraries using this starter here.](https://github.com/enonic/starter-lib/blob/master/docs/index.adoc)


## For XP 7 users

You first need to install [Enonic CLI](https://developer.enonic.com/docs/enonic-cli/) and choose _starter-lib_ from the list of starters when asked. Then run the following commands to build and deploy it:

```bash
~ $ enonic project create
... Answer wizard question

~ $ cd <project-folder>
~/new-project $ enonic project deploy
```

You can now build your lib and use it as a dependency in other apps


## For XP 6.x users

To get started, use the `toolbox` script to initiate your project:

```bash
mkdir new-project
cd new-project
[$XP_INSTALL]/toolbox/toolbox.sh init-project -n com.example.name -r starter-lib
```
