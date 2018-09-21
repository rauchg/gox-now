# gox-now

An example of leveraging [Now](https://zeit.co/github) as a way of cross-compiling a Go program
and hosting its binaries in the [Now CDN](https://zeit.co/cdn).

This will make it so that:

- Every push / merge to `master` is built ([more](https://zeit.co/blog/every-push-now))
- All pushes inside pull requests will be built, and Now will show up as a Check
