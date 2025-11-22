# `node-notifier` CLI

Separate package for [`node-notifier`](https://github.com/startvibe/node-notifier) CLI.

## Install

```
npm i [-g] @startvibe/node-notifier-cli
```

or try it out with [npx](https://www.npmjs.com/package/npx)

```
npx -p @startvibe/node-notifier-cli notify -t 'Hello' -m 'My message'
```

## usage

```
notify -h
```

```
# notify
## Options

    * --help (alias -h)

    * --title (alias -t)
    * --subtitle (alias -st; not available on Windows OS)
    * --message (alias -m)
    * --icon (alias -i)
    * --sound (alias -s; use none to disable default sound notification)
    * --open (alias -o)
    * --port (alias -p)
    * --host
    * --failsafe (alias -x; time in milliseconds)

## Example

   $ notify -t "Hello" -m "My Message" -s --open http://github.com
   $ notify -t "Agent Coulson" --icon https://raw.githubusercontent.com/startvibe/node-notifier/master/example/coulson.jpg
   $ notify -m "My Message" -s Glass
   $ echo "My Message" | notify -t "Hello"
```
