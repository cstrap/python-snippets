# Python snippets

Python snippets collections.

Initially ported from PyCharm, TextMate, SublimeText and other editors/IDEs.

If you'd like to contribute, feel free to [submit a pull request on github](https://github.com/cstrap/python-snippets)

Thanks!

## Features

### Base snippets

| Abbreviation | Description                       |
|--------------|-----------------------------------|
| env          | #!/usr/bin/env python             |
| env3         | #!/usr/bin/env python3            |
| enc          | # -*- coding=utf-8 -*-            |
| enco         | # coding=utf-8                    |
| fenc         | from future import ...            |
| fenco        | from future import ... (no `-*-`) |
| im           | import                            |
| fim          | from ... import ...               |
| class        | New class                         |
| classd       | New dataclass                     |
| defs         | New method                        |
| def          | New function                      |
| adef         | Async function                    |
| property     | New property                      |
| enum         | New Enum                          |
| if           | if                                |
| for          | for                               |
| while        | while                             |
| try          | try:except:                       |
| tryef        | try:except:else:finally:          |
| trye         | try:except:else:                  |
| tryf         | try:except:finally:               |
| s            | self                              |
| __           | __magic__                         |
| ifmain       | if __name__ == "__main__"         |

### Comprehensions

| Abbreviation | Description                        |
|--------------|------------------------------------|
| lc           | List comprehension                 |
| lcie         | List comprehension if else         |
| lci          | List comprehension if filter       |
| dc           | Dictionary comprehension           |
| dci          | Dictionary comprehension if filter |
| sc           | Set comprehension                  |
| sci          | Set Comprehension if filter        |
| gc           | Generator comprehension            |
| gci          | Generator comprehension if filter  |

### Unittest

| Abbreviation | Description        |
|--------------|--------------------|
| ase          | Assert equal       |
| asne         | Assert not equal   |
| asr          | Assert raises      |
| ast          | Assert True        |
| asf          | Assert False       |
| asi          | Assert is          |
| asint        | Assert is not      |
| asino        | Assert is None     |
| asinno       | Assert is not None |
| asin         | Assert in          |
| asni         | Assert not in      |
| as           | Assert             |
| fail         | Fail (a test)      |

### Debugging

| Abbreviation | Description    |
|--------------|----------------|
| pdb          | PDB set trace  |
| ipdb         | iPDB set trace |
| rpdb         | rPDB set trace |
| pudb         | PuDB set trace |

### Tkinter

| Abbreviation  | Description        |
|---------------|--------------------|
| imtk          | Import Tkinter py2 |
| imtk3         | Import tkinter py3 |
| config        | Root configuration |
| button        | Button             |
| label         | Label              |
| frame         | Frame              |
| entry         | Entry              |
| grid          | Grid               |
| sticky        | Sticky             |
| checkbutton   | Check button       |
| mainloop      | Main loop          |
| pack          | Pack               |
| side          | Side               |
| bind          | Bind               |
| menu          | Menu               |
| addcascade    | Add cascade        |
| addcommand    | Add command        |
| addseperator  | Add seperator      |

## Release Notes

See [changelog](CHANGELOG.md) for all changes and releases.

## Troubleshooting

If you experience problems with the auto-formatting of certain snippets, make sure you have the option `editor.tabCompletion` set on `onlySnippets` or `on`.