# Jenkins Quick Start VM

This VM is useful for testing out Jenkins scripts and configurations in a sandbox
before modifying a production Jenkins server.

It is also useful to test out plugins with full admin privileges for times when
you may not be the one with admin privileges on the production server.

## Getting Started

1. Build the VM:

                vagrant up

2. Look for the default admin password as the last line of the build:

               ==> default: Initial Admin Password:
               ==> default: [a random string  here will be the password]

3. Connect to jenkins: [http://localhost:8080](http://localhost:8080)

4. At this point it depends on the task at hand. I usuall install the default plugins.
