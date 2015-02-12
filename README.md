# XePersian LaTeX Template (XLT)
---
This repository will contain my XePersian LaTeX template(s) which I am/will develop through next couple of years.

Although this template can get copied from repository and being used manually, I developed a script to make life easier when someone have to write a new document once or twice in a week. If you are not interested in automatic template creatation you can ignore the rest of this text.



Installation Prerequisites
---
* bash interpeter
* Git

Installation
---
Just downlown and run [installation file](https://raw.githubusercontent.com/noise2/xepersian-latex-template/master/install) and it will take care of the rest!

```BASH
# one way 2 go :)
curl https://raw.githubusercontent.com/noise2/xepersian-latex-template/master/install | bash
```

Usages
---
At the moment there is only `paper` template available. To create a `paper` template after the [*XLT* installation](#installation) you can create a paper template like the below demo:

```BASH
# create a directory
mkdir xlt-test
# move into the directory
cd xlt-test
# create a paper template name `test_latex_file`
xlt -p test_latex_file
```

> You can also use `-f` argument for enforce the generator to override the possible existed files.
