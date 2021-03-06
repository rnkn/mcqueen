McQueen
=======

*"I live for myself and I answer to nobody." – Steve McQueen*

McQueen is style for responsive HTML screenplays.

Preview the [Nicholl Fellowship sample script][1]. HTML documents can
also include [snippets of screenplay content][2].

Usage
-----

The main stylesheet `mcqueen.scss` is designed not to be edited. All
configuration can be achieved by outputting key-value variables to
`_config.scss`, which is then imported on compile.

The classes are element-agnostic, so you can use `div` or `section` or
`p`, etc. Screenplay content must be wrapped in a `class="screenplay"`,
which allows for snippets within other content flow.

Variables
---------

| Variable                | Default                                           | Type/Value |
|-------------------------|---------------------------------------------------|------------|
| $page-size              | letter                                            | letter, a4 |
| $font-size              | 12pt                                              | size       |
| $font-stack             | "Courier Prime", "Courier", "Courier Final Draft" | array      |
| $line-height            | 1                                                 | integer    |
| $text-body-width        | 6in                                               | size       |
| $show-title-page        | true                                              | boolean    |
| $title-upcase           | true                                              | boolean    |
| $title-underline        | true                                              | boolean    |
| $title-bold             | false                                             | boolean    |
| $title-contact-right    | false                                             | boolean    |
| $hide-first-page-number | true                                              | boolean    |
| $scene-double-space     | false                                             | boolean    |
| $scene-bold             | false                                             | boolean    |
| $scene-underline        | false                                             | boolean    |
| $dialog-contd           | "(CONT'D)"                                        | string     |
| $dialog-more            | "(MORE)"                                          | string     |
| $action-orphans         | 2                                                 | integer    |
| $action-widows          | 2                                                 | integer    |
| $dialog-orphans         | 2                                                 | integer    |
| $dialog-widows          | 2                                                 | integer    |
| $show-notes             | false                                             | boolean    |
| $note-font-size         | 11pt                                              | size       |
| $note-font              | "Comic Sans MS"                                   | array      |
| $note-line-height       | 1.5                                               | size       |
| $note-color             | lightgoldenrodyellow                              | color      |
| $show-section-headings  | false                                             | boolean    |
| $highlight-change-color | yellow                                            | color      |
| $link-hover-color       | white                                             | color      |
| $link-hover-bg          | black                                             | color      |


[1]: https://git.bydasein.com/mcqueen/plain/sample/sample.html
[2]: https://git.bydasein.com/mcqueen/plain/sample/snippet.html
