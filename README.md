# devcontainers-clojure

This project contains a basic Clojure app and the configuration required to create a [developer container](https://microsoft.github.io/code-with-engineering-playbook/developer-experience/devcontainers/) so you can experiment and start learning Clojure.

## Getting started

See the [official documentation](https://code.visualstudio.com/docs/remote/containers#_getting-started) or review the checklist below:

System requirements

* [Docker Desktop](https://www.docker.com/get-started) 2.0 or later
* Install the [Remote Development expansion pack](https://aka.ms/vscode-remote/download/extension)
## Usage


* Clone this repository from Visual Studio Code, then open it
* When asked, allow it to *Reopen in Container*

The first time it's opened, a Docker image including Java, Clojure and Leiningen will be created (this takes a while depending on your computer and network speed).

When finished, it should open a Clojure project and load the **Calva** extension automatically.

You can start editing the code in `src/myapp/core.clj` to get your feet wet. Also, you can open the Calva extension's excellent *Calva: Fire up the Getting Started REPL* by pressing `F1` and searching for it.

## License

Copyright © 2022 Denis Fuenzalida

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

This Source Code may also be made available under the following Secondary
Licenses when the conditions for such availability set forth in the Eclipse
Public License, v. 2.0 are satisfied: GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your
option) any later version, with the GNU Classpath Exception which is available
at https://www.gnu.org/software/classpath/license.html.
