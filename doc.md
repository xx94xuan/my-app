# ReactApp

## Setup the React App

1. `$ npx creact-react-app my-app`
- If Error: 

	1). "error Received malformed response from registry for undefined. The registry may be down."

    **Reason**: Cause by the local network(in China)

    **Solution**: add proxy

	2). "error eslint@6.2.1: The engine "node" is incompatible with this module. Expected version "^8.10.0 || ^10.13.0 || >=11.10.1"."

    **Reason**: node version(v10.0.0)

    **Solution**: update latest node version by run `$ nvm install node --reinstall-packages-from=node` **OR**  `$ nvm ls-remote` to see node versions remote and choose the latest version(Now is v12.9.0) to install: `nvm install v12.9.0`

    **Additional**: [install nvm - office doc](https://github.com/nvm-sh/nvm)

    - `$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.0/install.sh | bash`
    - `$ export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"`

    - `[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"` # This loads nvm

    - `nvm --version` to check the nvm installed correctly

2. `$ cd my-app`

3. `$ yarn start`

## /my-app folder structure

TODO...

- /public/index.html: The basic html template of the page 
- /src/index.js: ~~default entry point of the js???~~
- /src/App.js: Established a component named 'App'











