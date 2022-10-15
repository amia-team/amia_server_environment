# amia_server_environment

Make sure you have hak/, module/, and tlk/ filled out with the necessary server files. Refer to the forums for what these should be.

To run, type into Powershell: `docker-compose up -d`
To stop, type into Powershell: `docker-compose down`

## Loading Anvil Plugins

Build your Anvil plugins, then copy their output to a subdirectory of server/anvil/Plugins, where the subdirectory must have the same name as the plugin's dll. For example, if your plugin is called `AmiaReforged.Example`, then you should copy the plugin files to the directory: `server/anvil/Plugins/AmiaReforged.Example`.

## Loading the database

Create a file the `config` folder named `db.env`, and create a variable inside the file named `POSTGRES_PASSWORD`. Assign the variable whatever value you like, e.g.: `POSTGRES_PASSWORD=1234`.
