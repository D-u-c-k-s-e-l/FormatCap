# FormatCap

A text formatting test for various formats.

## About

I would like to hope that I can format my text however I would like.
Unfortunately, this is rarely the case.
I have decided to instead, share my findings using a text formatting test of my own invention.

## The test

```
FormatCap::<format>@<ver>

Roses are red.
Violets are blue.
Bold dim italic and green dunderlines too!

Please don't delete my subparscripts.
```

This text should be formatted as follows:
- The description line's `<format>` should be the format of the test, i.e. Ansi.
- The description line's `<version>` should be the version of this format's test.
- The description line shoud be made underlined and monospaced
- There should be either a paragraph break (preferred), or a double line break, between the description line and `Roses are red.`
- The middle paragraph should use a proportional (non-monospace) font.
- `red` is plain text on a red background
- `blue` is blue text
- `Bold` is bold
- `dim` is either a lighter color, or thinner weight than normal
- `italic` is italic 
- `green dunderlines too` should have a double underline that is green in color
- There should be either a paragraph break (preferred), or a double line break, between `green dunderlines too!` and `Please don't delete`
- The last paragraph should be in a serif font.
- `delete` should be crossed out.
- `sub` in subparscripts should be subscripted
- `par` in subparscripts should be superscripted

### What is tested

The test tests for underlines, double underlines, monospace, paragraph breaking, proportional fonts, text color support, boldness, dimness, italics, strikethrough, serif fonts, strikethrough, superscripts, and supscripts, colored underlines, and background text color support.

## Files

In [/tests/](/tests/), there are the files to run the tests with.
In [results.csv](/results.csv), the results of the tests are published.
