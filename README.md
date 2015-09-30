# KAIST syntactic parser

## Description

This software is a Korean syntactic parser trained by Sejong treebank (converted into Penn-treebank format, proposed in [Jungyeul Park, "Extraction of tree adjoining grammars from a treebank for Korean", COLING-ACL 06: Student Research Workshop, 2006]. 

Also it is additionally refined to get the better result.

## How to use

This software contains [Hannanum](http://sourceforge.net/projects/hannanum/) morphological analyzer and work with Hanannum.

When using console command:

```
  java - jar BerkeleyParser_KorV2.jar "INPUT TEXT"
```

When using in file:

```
  BerkeleyParserWrapper bpw = new BerkeleyParserWrapper(Configuration.parserModel);   
    result = bpw.parse("INPUT TEXT");
```

## Licenses

* `CC BY-NC-SA` [Attribution-NonCommercial-ShareAlike](https://creativecommons.org/licenses/by-nc-sa/2.0/)
* If you want to commercialize this resource, [please contact to us](http://mrlab.kaist.ac.kr/contact)

## Citation

If you use the current of PROJECT NAME, please cite the following papers.

[Korean Treebank Transformation for Parser Training](http://www.aclweb.org/anthology/W12-3411)

