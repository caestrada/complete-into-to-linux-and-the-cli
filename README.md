# Complete Intro to Linux and the Command-Line

Course Website - [LINK](https://btholt.github.io/complete-intro-to-linux-and-the-cli/)

- [X] [Introduction](https://frontendmasters.com/courses/linux-command-line/introduction/)
- [X] [The CLI]()
- [X] [Editors]()
- [X] [Files, Pipes, & Permissions]()
- [X] [Environments & Processes]()
- [X] [Networking & the Internet]()
- [X] [Package Management]()
- [ ] [Shell Scripts]()
- [ ] [Automation & Customization]()
- [ ] [Wrapping Up]()

## Installing Multipass on macOS

Here is the [link](https://multipass.run/docs/installing-on-macos) to the multipass documentation.

## Notes

### Users
```bash
# Will show the name of all users in the OS
$ cat /etc/passwd
```

### Running Multipass

To run in the `Termial`
```bash
# To create a virtual instance.
$ multipass launch

# To see available instances.
$ multipass list

# To run the shell instance.
$ multipass shell <instance_name>
```

OR

 Use the `Multipass` app.