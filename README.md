Say
===

Simple [Forvo][1] client


## About

**say** - used to listen pronunciations of words from [forvo][1] service. For more details see [post][2].


## Usage

For listen pronunciation of word(s), just type (in terminal) the command:

    say some word

for example:

    say example
    say hello world

Default language - English, language can be changed (persistently) by invoking:

    say -lng=XXX  (where XXX: language abbreviation)

For example, the following call changes the language to Russian, and all subsequent invocations will be use this language:

    say -lng=ru


## License terms
**say** is published under the liberal terms of the BSD License. Although the BSD License does not require you to share any modifications you make to the source code, you are very much encouraged and invited to contribute back your modifications to the project, preferably in a Github fork, of course.




[1]: http://www.forvo.com "Forvo, the pronunciation dictionary"
[2]: http://habrahabr.ru/post/147842/ "Клиент для сервиса Forvo.com подручными средствами"

<pre>
  ___   __
  //_/\// 
_// _//\\
</pre>
Copyright (C) 2012, Eldar Zakirov <unixod@gmail.com>
