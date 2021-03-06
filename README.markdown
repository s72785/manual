![ReadersAgainstDRM](img/rad-logo.png "Readers Against DRM")

# The Radical Militant Manual

[This is really a community thing](./readingclub-man.markdown), written by the librarians [kittyhawk], [ewa4boeker], [Jotunbane] and contributors like [nek0].

Read first and then maybe add your own experiences.
If you found some mistakes or can help to enhance this, do not hesitate to let us know.

## License Terms

All contributors should be aware that the collective result is published under [Creative Commons](https://creativecommons.org/) Attribution Share-Alike 4.0 or later as long as not stated otherwise.

The Logo the Library uses refers to the [Readers Bill of Rights (RBoR)](http://readersbillofrights.info/RAD/). It is *created by* [Nina Paley] *for* the [RBoR, who then released it](http://readersbillofrights.info/librariansagainstDRM/) *under* [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).

[kittyhawk]: https://gitlab.com/kittyhawk/
[ewa4boeker]: https://github.com/ewa4boeker/
[Jotunbane]: https://github.com/Jotunbane/
[nek0]: https://nek0.eu/
[Nina Paley]: http://blog.ninapaley.com/

## how to build

in case you have the converter [pandoc](https://github.com/jgm/pandoc/) you can have it as TeX, HTML, ODT and many more;
for PDF you will need [pdflatex with e.g. TeX live](https://tug.org/texlive/) or a tool of your choice to convert yourself.

Please note that in Versions of Pandoc before 1.15.1 the resulting ODT was broken.

### Examples

for TeX, PDF, HTML5 and EPUB just start:

```sh
$ make
```

or for a single, specific target like ODT:

```sh
$ make odt
```
