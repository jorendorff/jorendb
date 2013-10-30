**jorendb** is a simple command-line debugger for shell-js programs. It is
intended as a demo of the Debugger object (as there are no shell js programs
 to speak of).

To run it: `$JS -d path/to/this/file/jorendb.js`
To run some JS code under it, try:

    (jorendb) print load("my-script-to-debug.js")

Execution will stop at debugger statements and you'll get a jorendb prompt.
