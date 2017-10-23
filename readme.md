## Overview

Syntax highlighting for [Clojure](https://clojure.org) and EDN, significantly
improved over the built-in Clojure package.

Improvements:

  * The syntax structure is modeled after the AST and the Clojure reader. Should
    handle any formatting, regardless of whitespace and indentation quirks.

  * No unnecessary special cases. Simple and consistent rules. User-defined
    syntax should look and feel the same as standard syntax.

  * Correctly highlights literals in root scope

  * Correctly handles numbers, keywords, and other literals

  * Correctly handles `definterface`, `defprotocol`, `deftype`, `defrecord`

  * Correctly declares functions defined by `defprotocol`

  * Correctly handles defs, particularly in presence of metadata

  * Correctly handles `defmulti` and `defmethod`

  * Allows user-defined defs

  * Highlights mismatched brackets, helping with balancing

  * ≈ 6 times smaller

  * ≈ 6 times faster

## Installation

Clone or download the repo into Sublime's Packages folder. On MacOS, this is
usually `/Users/<user>/Library/Application Support/Sublime Text 3/Packages`.
Find it in menu → Preferences → Browse Packages.

Activate by selecting the `Clj` syntax. If you prefer it, set Sublime to use
this syntax for all Clojure files.

## Contributing

Feedback, criticism, suggestions, and pull requests are welcome!

Guidelines:

  * avoid unnecessary special cases
  * minimize code size

Open an issue or reach me on skype:mitranim.web or me@mitranim.com.
