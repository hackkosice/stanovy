# Stanovy Hack Kosice

## Building

A PDF document `stanovy.pdf` can be generated from `stanovy.md` using [Pandoc](https://pandoc.org/) and the `stanovy_pdf.yaml` configuration file.

```shell script
pandoc -d stanovy_pdf
```
Use the following to re-format the `stanovy.md` source file.

```shell script
pandoc -d stanovy_md
```
