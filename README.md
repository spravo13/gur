GUR(GNU Usage Recorder)
===========

This started as just a simple file to log current memory usage, but from there it has grown(Currently at v2.3).
I origally defined it by calling it "a bash script to take note of current usage"
This description is still pretty accurate. gur creates a directory (~/usage) as well as a date directory  every time you log usage; in there it keeps the actual data in files based on the time the usage was recorded. You can also use the -t option to set a time interval to check and record usage for whatever time interval you want. gur records data on memory, CPU, storage, network, and top procceses. 

| Option | Description                 |
| ------ | --------------------------- |
| -h     | Show help/info              |
| -u     | Log usage               |
| -t      | Log usage on time delay  |
| -k     | Kill current time delay   |
| -c    | Clear all usage logs   |
## Installation
First clone the repository and then all you need to do is to move the `gur` file to somewhere in your `$PATH`.

## Contributing

I am open to pull requests just as long as you know <a href="http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html" target= "_blank">how to to write a commit message</a>.
Please report any bugs/issues you find. I am also very open to new ideas and
critique, see Contact section below on how to contact me. :-)

## Contact

If you have any questions or comments please contact me at <a title="Spencer@codeshrub.com" href="mailto:Spencer@codeshrub.com">Spencer@CodeShrub.com</a> or leave a comment wherever.

/Spencer Bravo

## Licence

GPL v3 License
