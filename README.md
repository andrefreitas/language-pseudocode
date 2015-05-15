# language-pseudocode package [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/andrefreitas/language-pseudocode?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
Have you ever tried to explain an algorithm on a presentation or document and felt the lack of having a standard to
write pseudocode? Well, this Atom package is a syntax highlighter for a pseudocode language.

*Is still in development and open for new contributors.*

## Install
- Install the [Atom editor](https://atom.io/)
- cd ~/.atom/packages
- git clone https://github.com/andrefreitas/language-pseudocode

## Usage
- Open Atom Editor
- Create a file called hello.pseudo
- Learn the language by the examples here

## Language examples
Here you can see some examples and as you can see, the language is still not complete but can be enough just to write
simple algorithms.

### 1. For loop
    FOR each component in commit
        component.revisions_twr += twr

        IF is_bug_fix(commit) THEN
          component.fixes_twr += twr
        ENDIF

        IF is_new_author(component, commit.author) THEN
          component.authors_twr += twr
        ENDIF
    ENDFOR

### 2. Function
    FUNCTION twr(ti)
        RETURN 1 / (1 + e ^ ( -12 * ti + 12) )
    ENDFUNCTION

## Contributing
I would love to have contributors to improve this language. Just send me an email hello@andrefreitas.pt

## Authors
- André Freitas - hello@andrefreitas.pt

## Roadmap and ideas
- Write a grammar
- Support for classes, prints, optional typing,
- Define a standard library for io, network, etc
- Build a parser to analyze time complexity
- Publish on Atom (when language will be more complete)
- Have a brainstorming session of what would be useful for pseudocode

## License
Copyright 2015 André Freitas

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.