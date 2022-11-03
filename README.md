# npmm
Node Package Manager Manager Implements the nmm Node Module Manager. It is based on the concept of content hashing. which can get extended to ast hashing for advanced deduplication in enterprise scale codebases.

## Why=?
The Node Package Manager is not the best maintained Project in the World while it is still a critical Project in the world as many documentation and tutorials do exist that depend on that for historical reason. Today we got more advanced concepts and the Package Managers try to keep up. So it was a logical conclusion to use the new more native methods but stay compatible to the old ecosystem so that it can get converted in a easy way. 

## How?
npm implements what it calls the resolve algorythm we on the other side implement what we call Component Definition. so we can translate NPM it self as also NPM managed modules into Component Definitions which are in general support the following formats: TypeScript, ESM, SystemJS, NodeJS Snapshot, JustJS dynamic/static build. ......
