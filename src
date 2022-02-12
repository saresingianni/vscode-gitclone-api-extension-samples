'use strict';

import * as vscode from 'vscode';

interface CatInfo {
	age: number;
	breed: string;
  }
  type CatName = "miffy" | "boris" | "mordred";

  const cats: Record<CatName, CatInfo> = {
	miffy: { age: 10, breed: "Persian" },
	boris: { age: 5, breed: "Maine Coon" },
	mordred: { age: 16, breed: "British Shorthair" },
  };

  
  console.log("cats.boris: " + cats.boris.age +" " +cats.boris.breed);
  console.log("cats.mordred: " + cats.mordred.age +" " +cats.mordred.breed);
  console.log("cats.miffy: " + cats.miffy.age +" " +cats.miffy.breed);
  
   interface GitInfo {
	comandi_01: string;
	esecuzione_01: string;
	comandi_02: string;
	esecuzione_02: string;
	comandi_03: string;
	esecuzione_03: string;
	comandi_04: string;
	esecuzione_04: string;
	comandi_05: string;
	esecuzione_05: string;
	comandi_06: string;
	esecuzione_06: string;
	comandi_07: string;
	esecuzione_07: string;
	comandi_08: string;
	esecuzione_08: string;
	comandi_09: string;
	esecuzione_09: string;
  }

  type RepName = "jasminegianni" | "leaflet_catasto" | 
				"phyton_date" |
				"Python_date" |
				"ServerSentEvents" |
				"Java_8_Stream_" |
				"EsempioFreeMarkerH2Test" |
				"struts_site" |
				"tutorials"
				;


const gits: Record<RepName, GitInfo> = {
	jasminegianni: {comandi_01: "echo ", esecuzione_01: "******inizio*******",
					comandi_02: "dir ", esecuzione_02: "",
					comandi_03: "md ", esecuzione_03: "jasminegianni", 
					comandi_04: "cd ", esecuzione_04: "jasminegianni",
					comandi_05: "git ", esecuzione_05: "init",
					comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/jasminegianni.git",
					comandi_07: "dir ", esecuzione_07: "",
					comandi_08: "echo ", esecuzione_08: "******fine*******",
					comandi_09: "cd ", esecuzione_09: ".."},
	leaflet_catasto: { 
					comandi_01: "echo ", esecuzione_01: "******inizio*******",
					comandi_02: "dir ", esecuzione_02: "",
					comandi_03: "md ", esecuzione_03: "leaflet_catasto", 
					comandi_04: "cd ", esecuzione_04: "leaflet_catasto",
					comandi_05: "git ", esecuzione_05: "init",
					comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/leaflet_catasto.git",
					comandi_07: "dir ", esecuzione_07: "",
					comandi_08: "echo ", esecuzione_08: "******fine*******",
					comandi_09: "cd ", esecuzione_09: ".." },
	phyton_date: 	{
						comandi_01: "echo ", esecuzione_01: "******inizio*******",
						comandi_02: "dir ", esecuzione_02: "",
						comandi_03: "md ", esecuzione_03: "phyton_date", 
						comandi_04: "cd ", esecuzione_04: "phyton_date",
						comandi_05: "git ", esecuzione_05: "init",
						comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/phyton-date.git",
						comandi_07: "dir ", esecuzione_07: "",
						comandi_08: "echo ", esecuzione_08: "******fine*******",
						comandi_09: "cd ", esecuzione_09: ".." },
	Python_date:	{
						comandi_01: "echo ", esecuzione_01: "******inizio*******",
						comandi_02: "dir ", esecuzione_02: "",
						comandi_03: "md ", esecuzione_03: "Python_date", 
						comandi_04: "cd ", esecuzione_04: "Python_date",
						comandi_05: "git ", esecuzione_05: "init",
						comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/Python_date.git",
						comandi_07: "dir ", esecuzione_07: "",
						comandi_08: "echo ", esecuzione_08: "******fine*******",
						comandi_09: "cd ", esecuzione_09: ".." },
	ServerSentEvents:	{
						comandi_01: "echo ", esecuzione_01: "******inizio*******",
						comandi_02: "dir ", esecuzione_02: "",
						comandi_03: "md ", esecuzione_03: "ServerSentEvents", 
						comandi_04: "cd ", esecuzione_04: "ServerSentEvents",
						comandi_05: "git ", esecuzione_05: "init",
						comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/ServerSentEvents.git",
						comandi_07: "dir ", esecuzione_07: "",
						comandi_08: "echo ", esecuzione_08: "******fine*******",
						comandi_09: "cd ", esecuzione_09: ".." },
	Java_8_Stream_:{
						comandi_01: "echo ", esecuzione_01: "******inizio*******",
						comandi_02: "dir ", esecuzione_02: "",
						comandi_03: "md ", esecuzione_03: "Java_8_Stream_", 
						comandi_04: "cd ", esecuzione_04: "Java_8_Stream_",
						comandi_05: "git ", esecuzione_05: "init",
						comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/Java-8-Stream-.git",
						comandi_07: "dir ", esecuzione_07: "",
						comandi_08: "echo ", esecuzione_08: "******fine*******",
						comandi_09: "cd ", esecuzione_09: ".." },
	EsempioFreeMarkerH2Test: { 
					comandi_01: "echo ", esecuzione_01: "******inizio*******",
					comandi_02: "dir ", esecuzione_02: "",
					comandi_03: "md ", esecuzione_03: "EsempioFreeMarkerH2Test", 
					comandi_04: "cd ", esecuzione_04: "EsempioFreeMarkerH2Test",
					comandi_05: "git ", esecuzione_05: "init",
					comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/EsempioFreeMarkerH2Test.git",
					comandi_07: "dir ", esecuzione_07: "",
					comandi_08: "echo ", esecuzione_08: "******fine*******",
					comandi_09: "cd ", esecuzione_09: ".." },	
	struts_site: 	{
					comandi_01: "echo ", esecuzione_01: "******inizio*******",
					comandi_02: "dir ", esecuzione_02: "",
					comandi_03: "md ", esecuzione_03: "struts_site", 
					comandi_04: "cd ", esecuzione_04: "struts_site",
					comandi_05: "git ", esecuzione_05: "init",
					comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/struts-site.git",
					comandi_07: "dir ", esecuzione_07: "",
					comandi_08: "echo ", esecuzione_08: "******fine*******",
					comandi_09: "cd ", esecuzione_09: ".." },
	tutorials: 	{
					comandi_01: "echo ", esecuzione_01: "******inizio*******",
					comandi_02: "dir ", esecuzione_02: "",
					comandi_03: "md ", esecuzione_03: "tutorials", 
					comandi_04: "cd ", esecuzione_04: "tutorials",
					comandi_05: "git ", esecuzione_05: "init",
					comandi_06: "git ", esecuzione_06: "clone https://github.com/saresingianni/tutorials.git",
					comandi_07: "dir ", esecuzione_07: "",
					comandi_08: "echo ", esecuzione_08: "******fine*******",
					comandi_09: "cd ", esecuzione_09: ".." }		
  };

  


  export function activate(context: vscode.ExtensionContext) {
	let NEXT_TERM_ID = 1;
	
	console.log("Terminals: " + (<any>vscode.window).terminals.length);

	// vscode.window.onDidOpenTerminal
	vscode.window.onDidOpenTerminal(terminal => {
		console.log("Terminal opened. Total count: " + (<any>vscode.window).terminals.length);
	});
	vscode.window.onDidOpenTerminal((terminal: vscode.Terminal) => {
		vscode.window.showInformationMessage(`onDidOpenTerminal, name: ${terminal.name}`);
	});

	// vscode.window.onDidChangeActiveTerminal
	vscode.window.onDidChangeActiveTerminal(e => {
		console.log(`Active terminal changed, name=${e ? e.name : 'undefined'}`);
	});

	// vscode.window.createTerminal
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.createTerminal', () => {
		vscode.window.createTerminal(`Ext Terminal #${NEXT_TERM_ID++}`);
		vscode.window.showInformationMessage('Hello World 2!');
	}));
		// vscode.window.createTerminal
		context.subscriptions.push(vscode.commands.registerCommand('terminalTest.createTerminalGianni', () => {
			vscode.window.createTerminal(`Ext Terminal Gianni #${NEXT_TERM_ID++}`);
			vscode.window.showInformationMessage('Hello World Gianni!');
		}));
	
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.createTerminalHideFromUser', () => {
		vscode.window.createTerminal({
			name: `Ext Terminal #${NEXT_TERM_ID++}`,
			hideFromUser: true
		} as any);
	}));
	
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.createAndSend', () => {
		const terminal = vscode.window.createTerminal(`Ext Terminal #${NEXT_TERM_ID++}`);
		terminal.sendText("echo 'Sent text immediately after creating'");
	}));
	context.subscriptions.push(vscode.commands.registerCommand('GitClone.jasminegianni', () => {
		const terminal = vscode.window.createTerminal(`Git Clone jasminegianni #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.jasminegianni.comandi_01+gits.jasminegianni.esecuzione_01);
					terminal.sendText(gits.jasminegianni.comandi_02+gits.jasminegianni.esecuzione_02);
					terminal.sendText(gits.jasminegianni.comandi_03+gits.jasminegianni.esecuzione_03);
					terminal.sendText(gits.jasminegianni.comandi_04+gits.jasminegianni.esecuzione_04);
					terminal.sendText(gits.jasminegianni.comandi_05+gits.jasminegianni.esecuzione_05);
					terminal.sendText(gits.jasminegianni.comandi_06+gits.jasminegianni.esecuzione_06);
					terminal.sendText(gits.jasminegianni.comandi_07+gits.jasminegianni.esecuzione_07);
					terminal.sendText(gits.jasminegianni.comandi_08+gits.jasminegianni.esecuzione_08);
					terminal.sendText(gits.jasminegianni.comandi_09+gits.jasminegianni.esecuzione_09);
				
				
					
				}
			});
		}
	}));
	context.subscriptions.push(vscode.commands.registerCommand('GitClone.leaflet_catasto', () => {
		const terminal = vscode.window.createTerminal(`Git Clone leaflet_catasto #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.leaflet_catasto.comandi_01+gits.leaflet_catasto.esecuzione_01);
					terminal.sendText(gits.leaflet_catasto.comandi_02+gits.leaflet_catasto.esecuzione_02);
					terminal.sendText(gits.leaflet_catasto.comandi_03+gits.leaflet_catasto.esecuzione_03);
					terminal.sendText(gits.leaflet_catasto.comandi_04+gits.leaflet_catasto.esecuzione_04);
					terminal.sendText(gits.leaflet_catasto.comandi_05+gits.leaflet_catasto.esecuzione_05);
					terminal.sendText(gits.leaflet_catasto.comandi_06+gits.leaflet_catasto.esecuzione_06);
					terminal.sendText(gits.leaflet_catasto.comandi_07+gits.leaflet_catasto.esecuzione_07);
					terminal.sendText(gits.leaflet_catasto.comandi_08+gits.leaflet_catasto.esecuzione_08);
					terminal.sendText(gits.leaflet_catasto.comandi_09+gits.leaflet_catasto.esecuzione_09);
				
				
					
				}
			});
		}
	}));
	context.subscriptions.push(vscode.commands.registerCommand('GitClone.phyton_date', () => {
		const terminal = vscode.window.createTerminal(`Git Clone phyton_date #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.phyton_date.comandi_01+gits.phyton_date.esecuzione_01);
					terminal.sendText(gits.phyton_date.comandi_02+gits.phyton_date.esecuzione_02);
					terminal.sendText(gits.phyton_date.comandi_03+gits.phyton_date.esecuzione_03);
					terminal.sendText(gits.phyton_date.comandi_04+gits.phyton_date.esecuzione_04);
					terminal.sendText(gits.phyton_date.comandi_05+gits.phyton_date.esecuzione_05);
					terminal.sendText(gits.phyton_date.comandi_06+gits.phyton_date.esecuzione_06);
					terminal.sendText(gits.phyton_date.comandi_07+gits.phyton_date.esecuzione_07);
					terminal.sendText(gits.phyton_date.comandi_08+gits.phyton_date.esecuzione_08);
					terminal.sendText(gits.phyton_date.comandi_09+gits.phyton_date.esecuzione_09);
				
				
					
				}
			});
		}
	}));
	context.subscriptions.push(vscode.commands.registerCommand('GitClone.Python_date', () => {
		const terminal = vscode.window.createTerminal(`Git Clone Python_date #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.Python_date.comandi_01+gits.Python_date.esecuzione_01);
					terminal.sendText(gits.Python_date.comandi_02+gits.Python_date.esecuzione_02);
					terminal.sendText(gits.Python_date.comandi_03+gits.Python_date.esecuzione_03);
					terminal.sendText(gits.Python_date.comandi_04+gits.Python_date.esecuzione_04);
					terminal.sendText(gits.Python_date.comandi_05+gits.Python_date.esecuzione_05);
					terminal.sendText(gits.Python_date.comandi_06+gits.Python_date.esecuzione_06);
					terminal.sendText(gits.Python_date.comandi_07+gits.Python_date.esecuzione_07);
					terminal.sendText(gits.Python_date.comandi_08+gits.Python_date.esecuzione_08);
					terminal.sendText(gits.Python_date.comandi_09+gits.Python_date.esecuzione_09);
				
				
					
				}
			});
		}
	}));
	context.subscriptions.push(vscode.commands.registerCommand('GitClone.ServerSentEvents', () => {
		const terminal = vscode.window.createTerminal(`Git Clone ServerSentEvents #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.ServerSentEvents.comandi_01+gits.ServerSentEvents.esecuzione_01);
					terminal.sendText(gits.ServerSentEvents.comandi_02+gits.ServerSentEvents.esecuzione_02);
					terminal.sendText(gits.ServerSentEvents.comandi_03+gits.ServerSentEvents.esecuzione_03);
					terminal.sendText(gits.ServerSentEvents.comandi_04+gits.ServerSentEvents.esecuzione_04);
					terminal.sendText(gits.ServerSentEvents.comandi_05+gits.ServerSentEvents.esecuzione_05);
					terminal.sendText(gits.ServerSentEvents.comandi_06+gits.ServerSentEvents.esecuzione_06);
					terminal.sendText(gits.ServerSentEvents.comandi_07+gits.ServerSentEvents.esecuzione_07);
					terminal.sendText(gits.ServerSentEvents.comandi_08+gits.ServerSentEvents.esecuzione_08);
					terminal.sendText(gits.ServerSentEvents.comandi_09+gits.ServerSentEvents.esecuzione_09);
				
				
					
				}
			});
		}
	}));

	context.subscriptions.push(vscode.commands.registerCommand('GitClone.Java_8_Stream_', () => {
		const terminal = vscode.window.createTerminal(`Git Clone Java_8_Stream_ #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.Java_8_Stream_.comandi_01+gits.Java_8_Stream_.esecuzione_01);
					terminal.sendText(gits.Java_8_Stream_.comandi_02+gits.Java_8_Stream_.esecuzione_02);
					terminal.sendText(gits.Java_8_Stream_.comandi_03+gits.Java_8_Stream_.esecuzione_03);
					terminal.sendText(gits.Java_8_Stream_.comandi_04+gits.Java_8_Stream_.esecuzione_04);
					terminal.sendText(gits.Java_8_Stream_.comandi_05+gits.Java_8_Stream_.esecuzione_05);
					terminal.sendText(gits.Java_8_Stream_.comandi_06+gits.Java_8_Stream_.esecuzione_06);
					terminal.sendText(gits.Java_8_Stream_.comandi_07+gits.Java_8_Stream_.esecuzione_07);
					terminal.sendText(gits.Java_8_Stream_.comandi_08+gits.Java_8_Stream_.esecuzione_08);
					terminal.sendText(gits.Java_8_Stream_.comandi_09+gits.Java_8_Stream_.esecuzione_09);
				
				
					
				}
			});
		}
	}));
	
	context.subscriptions.push(vscode.commands.registerCommand('GitClone.EsempioFreeMarkerH2Test', () => {
		const terminal = vscode.window.createTerminal(`Git Clone EsempioFreeMarkerH2Test #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_01+gits.EsempioFreeMarkerH2Test.esecuzione_01);
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_02+gits.EsempioFreeMarkerH2Test.esecuzione_02);
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_03+gits.EsempioFreeMarkerH2Test.esecuzione_03);
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_04+gits.EsempioFreeMarkerH2Test.esecuzione_04);
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_05+gits.EsempioFreeMarkerH2Test.esecuzione_05);
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_06+gits.EsempioFreeMarkerH2Test.esecuzione_06);
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_07+gits.EsempioFreeMarkerH2Test.esecuzione_07);
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_08+gits.EsempioFreeMarkerH2Test.esecuzione_08);
					terminal.sendText(gits.EsempioFreeMarkerH2Test.comandi_09+gits.EsempioFreeMarkerH2Test.esecuzione_09);
				
				
					
				}
			});
		}
	}));
	
	context.subscriptions.push(vscode.commands.registerCommand('GitClone.struts_site', () => {
		const terminal = vscode.window.createTerminal(`Git Clone struts_site #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.struts_site.comandi_01+gits.struts_site.esecuzione_01);
					terminal.sendText(gits.struts_site.comandi_02+gits.struts_site.esecuzione_02);
					terminal.sendText(gits.struts_site.comandi_03+gits.struts_site.esecuzione_03);
					terminal.sendText(gits.struts_site.comandi_04+gits.struts_site.esecuzione_04);
					terminal.sendText(gits.struts_site.comandi_05+gits.struts_site.esecuzione_05);
					terminal.sendText(gits.struts_site.comandi_06+gits.struts_site.esecuzione_06);
					terminal.sendText(gits.struts_site.comandi_07+gits.struts_site.esecuzione_07);
					terminal.sendText(gits.struts_site.comandi_08+gits.struts_site.esecuzione_08);
					terminal.sendText(gits.struts_site.comandi_09+gits.struts_site.esecuzione_09);
				
				
					
				}
			});
		}
	}));
	context.subscriptions.push(vscode.commands.registerCommand('GitClone.tutorials', () => {
		const terminal = vscode.window.createTerminal(`Git Clone tutorials #${NEXT_TERM_ID++}`);
	
	
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
						terminal.show();
						

						
					terminal.sendText(gits.tutorials.comandi_01+gits.tutorials.esecuzione_01);
					terminal.sendText(gits.tutorials.comandi_02+gits.tutorials.esecuzione_02);
					terminal.sendText(gits.tutorials.comandi_03+gits.tutorials.esecuzione_03);
					terminal.sendText(gits.tutorials.comandi_04+gits.tutorials.esecuzione_04);
					terminal.sendText(gits.tutorials.comandi_05+gits.tutorials.esecuzione_05);
					terminal.sendText(gits.tutorials.comandi_06+gits.tutorials.esecuzione_06);
					terminal.sendText(gits.tutorials.comandi_07+gits.tutorials.esecuzione_07);
					terminal.sendText(gits.tutorials.comandi_08+gits.tutorials.esecuzione_08);
					terminal.sendText(gits.tutorials.comandi_09+gits.tutorials.esecuzione_09);
				
				
					
				}
			});
		}
	}));
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.createZshLoginShell', () => {
		vscode.window.createTerminal(`Ext Terminal #${NEXT_TERM_ID++}`, '/bin/zsh', ['-l']);
	}));

	// Terminal.hide
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.hide', () => {
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
					terminal.hide();
				}
			});
		}
	}));

	// Terminal.show
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.show', () => {
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
					terminal.show();
				}
			});
		}
	}));
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.showPreserveFocus', () => {
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
					terminal.show(true);
				}
			});
		}
	}));

	// Terminal.sendText
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.sendText', () => {
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
					terminal.sendText("echo 'Hello world!'");
				}
			});
		}
	}));
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.sendTextNoNewLine', () => {
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
					terminal.sendText("echo 'Hello world!'", false);
				}
			});
		}
	}));

	// Terminal.dispose
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.dispose', () => {
		if (ensureTerminalExists()) {
			selectTerminal().then(terminal => {
				if (terminal) {
					terminal.dispose();
				}
			});
		}
	}));

	// Terminal.processId
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.processId', () => {
		selectTerminal().then(terminal => {
			if (!terminal) {
				return;
			}
			terminal.processId.then((processId) => {
				if (processId) {
					vscode.window.showInformationMessage(`Terminal.processId: ${processId}`);
				} else {
					vscode.window.showInformationMessage('Terminal does not have a process ID');
				}
			});
		});
	}));

	// vscode.window.onDidCloseTerminal
	vscode.window.onDidCloseTerminal((terminal) => {
		vscode.window.showInformationMessage(`onDidCloseTerminal, name: ${terminal.name}`);
	});

	// vscode.window.terminals
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.terminals', () => {
		selectTerminal();
	}));

	// ExtensionContext.environmentVariableCollection
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.updateEnvironment', () => {
		const collection = context.environmentVariableCollection;
		collection.replace('FOO', 'BAR');
		collection.append('PATH', '/test/path');
	}));

	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.clearEnvironment', () => {
		context.environmentVariableCollection.clear();
	}));

	// vvv Proposed APIs below vvv

	// vscode.window.onDidWriteTerminalData
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.onDidWriteTerminalData', () => {
		(<any>vscode.window).onDidWriteTerminalData((e: any) => {
			vscode.window.showInformationMessage(`onDidWriteTerminalData listener attached, check the devtools console to see events`);
			console.log('onDidWriteData', e);
		});
	}));

	// vscode.window.onDidChangeTerminalDimensions
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.onDidChangeTerminalDimensions', () => {
		vscode.window.showInformationMessage(`Listening to onDidChangeTerminalDimensions, check the devtools console to see events`);
		(<any>vscode.window).onDidChangeTerminalDimensions((event: any) => {
			console.log(`onDidChangeTerminalDimensions: terminal:${event.terminal.name}, columns=${event.dimensions.columns}, rows=${event.dimensions.rows}`);
		});
	}));

	// vscode.window.registerTerminalLinkProvider
	context.subscriptions.push(vscode.commands.registerCommand('terminalTest.registerTerminalLinkProvider', () => {
		(<any>vscode.window).registerTerminalLinkProvider({
			provideTerminalLinks: (context: any, token: vscode.CancellationToken) => {
				// Detect the first instance of the word "link" if it exists and linkify it
				const startIndex = (context.line as string).indexOf('link');
				if (startIndex === -1) {
					return [];
				}
				return [
					{
						startIndex,
						length: 'link'.length,
						tooltip: 'Show a notification',
						// You can return data in this object to access inside handleTerminalLink
						data: 'Example data'
					}
				];
			},
			handleTerminalLink: (link: any) => {
				vscode.window.showInformationMessage(`Link activated (data = ${link.data})`);
			}
		});
	}));

	context.subscriptions.push(vscode.window.registerTerminalProfileProvider('terminalTest.terminal-profile', {
		provideTerminalProfile(token: vscode.CancellationToken): vscode.ProviderResult<vscode.TerminalProfile> {
			return {
				options: {
					name: 'Terminal GitClone API',
					shellPath: process.title || 'C:/Windows/System32/cmd.exe'
				}
			};
		}
	}));
}

function colorText(text: string): string {
	let output = '';
	let colorIndex = 1;
	for (let i = 0; i < text.length; i++) {
		const char = text.charAt(i);
		if (char === ' ' || char === '\r' || char === '\n') {
			output += char;
		} else {
			output += `\x1b[3${colorIndex++}m${text.charAt(i)}\x1b[0m`;
			if (colorIndex > 6) {
				colorIndex = 1;
			}
		}
	}
	return output;
}

function selectTerminal(): Thenable<vscode.Terminal | undefined> {
	interface TerminalQuickPickItem extends vscode.QuickPickItem {
		terminal: vscode.Terminal;
	}
	const terminals = <vscode.Terminal[]>(<any>vscode.window).terminals;
	const items: TerminalQuickPickItem[] = terminals.map(t => {
		return {
			label: `name: ${t.name}`,
			terminal: t
		};
	});
	return vscode.window.showQuickPick(items).then(item => {
		return item ? item.terminal : undefined;
	});
}

function ensureTerminalExists(): boolean {
	if ((<any>vscode.window).terminals.length === 0) {
		vscode.window.showErrorMessage('No active terminals');
		return false;
	}
	return true;
}
