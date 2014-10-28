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

| Variable                | Default                                           | Values      |
|-------------------------|---------------------------------------------------|-------------|
| $page-size              | letter                                            | letter, a4  |
| $font-size              | 12pt                                              |             |
| $font-stack             | "Courier Prime", "Courier", "Courier Final Draft" |             |
| $line-height            | 1                                                 |             |
| $text-body-width        | 6in                                               |             |
| $title-upcase           | true                                              | true, false |
| $title-underline        | true                                              | true, false |
| $title-bold             | false                                             | true, false |
| $scene-double-space     | false                                             | true, false |
| $scene-bold             | false                                             | true, false |
| $scene-underline        | false                                             | true, false |
| $dialog-contd           | "(CONT'D)"                                        |             |
| $dialog-more            | "(MORE)"                                          |             |
| $action-orphans         | 2                                                 |             |
| $action-widows          | 2                                                 |             |
| $dialog-orphans         | 2                                                 |             |
| $dialog-widows          | 2                                                 |             |
| $highlight-change-color | yellow                                            |             |
