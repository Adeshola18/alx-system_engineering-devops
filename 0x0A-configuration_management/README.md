# Configuration management

In this project, I started working with Puppet as a configuration management
tool. I practiced writing Puppet manifest files to create a file, install a
package, and execute a command.

## Tasks :page_with_curl:

- **0. Create a file**
  Using Puppet, create a file in /tmp.

Requirements:

- File path is /tmp/school
- File permission is 0744
- File owner is www-data
- File group is www-data
- File contains I love Puppet

- **1. Create a file**
  Using Puppet, install flask from pip3.

Requirements:

- Install flask
- Version must be 2.1.0

- **2. Execute a command**
  Using Puppet, create a manifest that kills a process named killmenow.

Requirements:

- Must use the exec Puppet resource
- Must use pkill
  Example:

Terminal #0 - starting my process
