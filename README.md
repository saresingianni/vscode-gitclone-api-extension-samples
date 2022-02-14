# vscode-terminal--gitclone-api-example

Questo esempio fornisce diversi comandi che illustrano come utilizzare l'API di estensione al terminale integrata per finsetra integrata ctr+shift+p Accedere ai comandi tramite (F1).
 ed eseguire il debug con la freccia a sinistra CTRl+Maiusc+D si avvia  l'Estensione.

I progetti elencati li trovate su questo Git Hub

- [`Saresin Gianni`](https://github.com/saresingianni?tab=repositories)


![demo](https://raw.github.com/saresingianni//vscode-gitclone-api-extension-samples/main/demo.png)



## VS Code GitClone API

### `vscode` modili  da microsoft

- [window.createTerminal](https://code.visualstudio.com/api/references/vscode-api#window.createTerminal)
- [window.onDidChangeActiveTerminal](https://code.visualstudio.com/api/references/vscode-api#window.onDidChangeActiveTerminal)
- [window.onDidCloseTerminal](https://code.visualstudio.com/api/references/vscode-api#window.onDidCloseTerminal)
- [window.onDidOpenTerminal](https://code.visualstudio.com/api/references/vscode-api#window.onDidOpenTerminal)
- [window.Terminal](https://code.visualstudio.com/api/references/vscode-api#window.Terminal)
- [window.terminals](https://code.visualstudio.com/api/references/vscode-api#window.terminals)

### Proposed API da microsoft

- `window.createTerminalRenderer`
- `window.TerminalRenderer`
- `window.registerTerminalProfileProvider`

### Contribution Points

- [`contributes.commands`](https://code.visualstudio.com/api/references/contribution-points#contributes.commands)
- [`contributes.terminal`](https://code.visualstudio.com/updates/v1_57#_terminal-profile-contributions)

## Esecuzione del esenmpio

- Esegui `npm install` nel terminale per installare le dipendenze
- Esegui la destinazione "Esegui estensione" nella vista di debug. Questo sarà:
- Avvia un'attività `npm: watch` per compilare il codice
- Esegui l'estensione in una nuova finestra VS Code
