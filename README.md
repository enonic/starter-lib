# Library Starter for Enonic XP

This starter kit will set up an empty shell for your new Enonic lib.

Once initiated, you'll have the bare minimum needed to create a new Enonic
library. You'll have all the folders set up, and can get
straight to creating what you're creating.

## Enonic CLI

You first need to install Enonic CLI:

```bash
npm install -g enonic-cli
```

## Building

### XP 8

Run the following commands to create and build it:

```bash
~ $ enonic project create -r starter-lib mylib

~ $ cd mylib

~/mylib $ enonic project build
```

### XP 7

Run the following commands to create and build it:

```bash
~ $ enonic project create -r starter-lib -b xp7 mylib

~ $ cd mylib

~/mylib $ enonic project build
```

## Development

After you have created the project, you can use following command to publish to the local gradle repository:

```bash
~/mylib $ enonic project gradle pTML
```

This will make the library available for use in other projects on the same machine.
