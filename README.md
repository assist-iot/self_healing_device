- # Self-healing & Node-RED

In iot2050_selfhealing_flow.json file you will find the self-healing implementation of the IOT2050 gateway device using Node-RED, Unix commands and Javascript.

In [Wiki](https://gitlab.assist-iot.eu/wp5/t51/self-healing/-/wikis/SIMATIC%20IOT2050) you will find more info about the device and the features considered to apply self-healing.

## Installation

Self-healing requires [Node-RED](https://nodered.org/docs/getting-started/local) running locally.
Install with NPM:
```sh
sudo npm install -g --unsafe-perm node-red
```

## Modules

Self-healing features (like network availability) requires these modules.

| Module | Version |
| ------ | ------ |
| [node-red-contrib-battery](https://flows.nodered.org/node/node-red-contrib-battery) | 1.0.1 |
| [node-red-node-ping](https://flows.nodered.org/node/node-red-node-ping) | >= 0.3.1 |

You can install modules directly within the editor by selecting the Manage Palette option from the main menu to open the Palette Manager.

- The ‘Nodes’ tab lists all of the modules you have installed. It shows which you are using and whether updates are available for any of them.
- The ‘Install’ tab lets you search the catalogue of available node modules and install them.

## Flows

Once Node-RED and modules have been installed it is needed to import the Self-healing flows, for example, **iot2050_selfhealing_flow.json**.

Like previous step, you can import flows directly within the editor by selecting the Import option from the main menu to open the Import Nodes Manager.

You can 'Paste flow json' or 'select a file to import' and finally press Import button.

