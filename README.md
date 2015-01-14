Tired of manually adding upstream remotes from GitHub and BitBucket?

Then `clone` is for you.

`clone` is a Python 3 script which can clone any Mercurial or Git repo.
If the repo is a fork on GitHub or BitBucket, Beatiful Soup 3 will be 
used to parse the URL for upstream repo and add it to your clone as a
remote called (surprise!) `upstream`.


git example
===

If you have created a fork of `clone`, you could clone it using
```
clone git@github.com:username/clone.git
```
with your GitHub username in place of `username`.
The upstream repo will automatically be added to your clone as a remote called `upstream`.

Mercurial example
===

If you have a fork of the 3D rendering system `ogre` on BitBucket, you could
clone it using

```
clone ssh://hg@bitbucket.org/username/ogre
```
