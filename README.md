# The Node.js/libuv contribution report

The first time:

1. Clone the repo somewhere: `git clone https://github.com/strongloop/node-contributions.git`.
2. From the unix shell, cd to the cloned directory.
3. Run `./contributions`. This will clone the master Node.js and libuv repositories into submodules, then run the standard blog report for contributors by patch, and the number of lines those people have contributed. The first time you run this, the cloning step will take a while.

After the first time:

1. cd to the cloned directory.
2. Run `./contributions` again. After the first time, it will update rather than re-cloning the local copies of Node.js and libuv. This should make the overall operation much faster.

What's reported:

For Node.js and for libuv, the list of committers reverse-sorted by number of commits and by number of patch lines.
