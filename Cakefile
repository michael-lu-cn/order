{exec} = require 'child_process'
task 'test', 'Run library tests', ->
  exec '/usr/local/bin/mocha --compilers cf:coffee-script/register -r "coffee-script" -R spec --colors ./test/*.cf', (err, stdout) ->
      console.log stdout
      throw err if err
