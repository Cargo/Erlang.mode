# Erlang Coda Syntax Mode

[Coda 2](http://panic.com/coda) syntax mode for the [Erlang](http://www.erlang.org) programming language. Current features include:

* Erlang syntax highlighting
* Navigator symbols for modules, includes, defines, and functions
* Custom bookmarks for the Code Navigator, e.g. `%% !Bookmark`
* Autocomplete for builtin functions, keywords, and more

## Installation

#### Automatic, via Finder

Either *Clone in Desktop* or *Download ZIP*. Note that when downloading a ZIP you will need to first unzip, then, if necessary, rename the unzipped directory from `Erlang.mode-branchname` to `Erlang.mode`. Next, double-click `Erlang.mode` or open it with Coda 2. When asked by Coda 2 if you want to install the mode, click *Install*.

#### Manual, via Terminal

Installing via Terminal with git has the added bonus of easily staying up-to-date. Open Terminal, run the commands below, and launch/restart Coda 2:

```bash
mkdir -p ~/Library/Application\ Support/Coda\ 2/Modes
cd ~/Library/Application\ Support/Coda\ 2/Modes
git clone https://github.com/Cargo/Erlang.mode
```

Updating to the latest version `Erlang.mode` can then be as simple as the following (don't forget to restart Coda 2 afterwards):

```bash
cd ~/Library/Application\ Support/Coda\ 2/Modes/Erlang.mode
git pull
```

## License
```
Copyright 2013 Cargo Collective, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
