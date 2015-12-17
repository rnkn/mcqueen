McQueen
=======

*"I live for myself and I answer to nobody."*

McQueen is style for HTML screenplays.

Usage
-----

The main stylesheet `mcqueen.scss` is designed not to be edited. All
configuration can be achieved by outputting key-value variables to
`_config.scss`, which is then imported on compile.

Variables
---------

| Variable                | Default                                           | Type/Value            |
|-------------------------|---------------------------------------------------|-----------------------|
| $page-size              | letter                                            | letter, us-letter, a4 |
| $font-size              | 12pt                                              | size                  |
| $font-stack             | "Courier Prime", "Courier", "Courier Final Draft" | array                 |
| $line-height            | 1                                                 | integer               |
| $text-body-width        | 6in                                               | length                |
| $title-upcase           | true                                              | boolean               |
| $title-underline        | true                                              | boolean               |
| $title-bold             | false                                             | boolean               |
| $scene-double-space     | false                                             | boolean               |
| $scene-bold             | false                                             | boolean               |
| $scene-underline        | false                                             | boolean               |
| $dialog-contd           | "(CONT'D)"                                        | string                |
| $dialog-more            | "(MORE)"                                          | string                |
| $action-orphans         | 2                                                 | integer               |
| $action-widows          | 2                                                 | integer               |
| $dialog-orphans         | 2                                                 | integer               |
| $dialog-widows          | 2                                                 | integer               |
| $highlight-change-color | yellow                                            | color                 |

CSS derived from Textplay (c) Oliver Taylor <https://github.com/olivertaylor/Textplay>
