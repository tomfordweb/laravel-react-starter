# Local Development

### First time setup

The app will complain that you did not set an encryption key.

On the first startup, run the following command to create the environments encryption key in the `.env` file.
```
./bin/artisan key:generate

```


### Starting the app

The below script will setup the apps dependencies, the environment, and boot it up in local development mode.

```
./bin/start
```


### Backend artisan CLI

To run the artisan CLI, it is easiest to use the script.

```
./bin/artisan <command>
```


Ex:
```
./bin/artisan make:migration create_some_table
./bin/artisan key:generate
```

