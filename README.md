# server-bootstrap
Automatic deployment and configuration for server.

# Configuration

## Hosts:

Create a file ./hosts at the root of the project:
Then add:

```
[servers]
192.168.1.75 ansible_connection=ssh ansible_port=22 ansible_user="user"
```
