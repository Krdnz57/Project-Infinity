# Project Infinity
Project Infinity ist ein CarSharing System basierend auf der Blockchain.
Um das Projekt verwenden zu können muss folgende Software vorhanden sein.

* Remix IDE
* Node.js
    * npm
* Ganache CLI
* Atom Editor

## [Remix IDE](https://remix.ethereum.org/)
Die Remix IDE bietet einige Features zur Entwicklung von Smart Contracts.
Sie unterstützt die Programmiersprache Solidity vollständig (Syntax Highlighting,
Auto Completion, Error Detection, Compiler). Man kann Smart Contracts testen und
auf die JavaScript VM, den Web3 Provider deployen.

## [Node.js](https://nodejs.org/)
Node.js ist eine in JavaScript geschriebene Open-Source Server Environment. Bei der
Installation von Node.js ist [npm] (https://www.npmjs.com/) - Node Package Manager mit dabei.

```bash
    npm init
```

mit npm init kann ein npm package angelegt werden. Dabei wird eine Datei package.json erstellt,
in der die benötigten Informationen des Projekts definiert sind.

```bash
    npm install bootstrap
```

mit npm install können packages installiert werden.

```bash
    npm build
```
mit npm build wird nach der package.json gesucht und die dependencies installiert.

## [Ganache CLI](https://truffleframework.com/docs/ganache/quickstart)
Ganache CLI ist ein command line interface, welches die Ethereum Blockchain auf
dem PC abbildet. Ganache legt automatisch 10 Accounts mit jeweils 100 Ether zur freien Verwendung.

```bash
    npm install -g ganache-cli
```

danach kann Ganache über die Konsole gestartet werden mit

```bash
    ganache-cli
```

Ganache CLI hört standardmäßig auf [localhost:8545](https://localhost:8545)

## [Atom Editor](https://atom.io/)
Atom ist ein hoch konfigurierbarer Editor. Man kann so gut wie alles einstellen
und Atom unterstützt so ziemlich jede Programmiersprache (sogar Solidity).

### Eine Liste von nützlichen Packages:
* language-solidity
* linter-solidity
* autocomplete-solidity
* atom-live-Server
* atom-beautify
* file-icons
* emmet
* ask-stack

## Referenzen
[Interacting with Ethereum Smart Contracts](https://medium.com/coinmonks/interacting-with-ethereum-smart-contracts-through-web3-js-e0efad17977)

[Remix Docs](https://remix.readthedocs.io/en/latest/)
[Solidity Docs](https://solidity.readthedocs.io/en/v0.4.25/)
[Web3.js Docs](https://web3js.readthedocs.io/en/1.0/)

[Interneting is hard](https://internetingishard.com/)
[Bootstrap](https://getbootstrap.com/docs/4.1/getting-started/introduction/)
[JQuery](https://www.w3schools.com/angular/default.asp)
[Angular](https://www.w3schools.com/jquery/default.asp)
