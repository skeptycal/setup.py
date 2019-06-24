# 📦 setup.py (for humans)

This repo exists to provide [an example setup.py] file, that can be used
to bootstrap your next Python project. It includes some advanced
patterns and best practices for `setup.py`, as well as some
commented–out nice–to–haves.

For example, this `setup.py` provides a `$ python setup.py upload`
command, which creates a _universal wheel_ (and _sdist_) and uploads
your package to [PyPi] using [Twine], without the need for an annoying
`setup.cfg` file. It also creates/uploads a new git tag, automatically.

In short, `setup.py` files can be daunting to approach, when first
starting out — even Guido has been heard saying, "everyone cargo cults
thems". It's true — so, I want this repo to be the best place to
copy–paste from :)

**If you're interested in financially supporting Kenneth Reitz open source, consider [visiting this link](https://cash.me/$KennethReitz). Your support helps tremendously with sustainability of motivation, as Open Source is no longer part of my day job.**

[Check out the example!][an example setup.py]

![image]

## To Do

- Tests via `$ setup.py test` (if it's concise).

Pull requests are encouraged!

## More Resources

- [What is setup.py?] on Stack Overflow
- [Official Python Packaging User Guide](https://packaging.python.org)
- [The Hitchhiker's Guide to Packaging]
- [Cookiecutter template for a Python package]

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any means.

✨🍰✨

[an example setup.py]: https://github.com/kennethreitz/setup.py/blob/master/setup.py
[pypi]: https://docs.python.org/3/distutils/packageindex.html
[twine]: https://pypi.python.org/pypi/twine
[image]: https://farm1.staticflickr.com/628/33173824932_58add34581_k_d.jpg
[what is setup.py?]: https://stackoverflow.com/questions/1471994/what-is-setup-py
[the hitchhiker's guide to packaging]: https://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/creation.html
[cookiecutter template for a python package]: https://github.com/audreyr/cookiecutter-pypackage
