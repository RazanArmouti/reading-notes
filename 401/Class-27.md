# Configuring Django Settings: Best Practices
+ Issues
    - Different environments : an approach that allows you to keep all these Django setting configurations.
    - Sensitive data : You have SECRET_KEY in each Django project. On top of this there can be DB passwords and tokens for third-party APIs like Amazon or Twitter. This data cannot be stored in VCS.
    - Sharing settings between team members :a general approach to eliminate human error when working with the settings. For example, a developer may add a third-party app or some API integration and fail to add specific settings
    - Django settings are a Python code: This is a curse and a blessing at the same time. It gives you a lot of flexibility, but can also be a problem – instead of key-value pairs, settings.py can have a very tricky logic.

## Different Approaches
- settings_local.py : he basic idea of this method is to extend all environment-specific settings in the settings_local.py file

- Separate settings file for each environment :In this case, you make a settings package

```bash
settings/
   ├── __init__.py
   ├── base.py
   ├── ci.py
   ├── local.py
   ├── staging.py
   ├── production.py
   └── qa.py
```
## what is SSH
SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet. The service was created as a secure replacement for the unencrypted Telnet and uses cryptographic techniques to ensure that all communication to and from the remote server happens in an encrypted manner. It provides a mechanism for authenticating a remote user, transferring inputs from the client to the host, and relaying the output back to the client.

## How Does SSH Work
`ssh {user}@{host}`
The SSH key command instructs your system that you want to open an encrypted Secure Shell Connection. `{user}` represents the account you want to access. For example, you may want to access the root user, which is basically synonymous for system administrator with complete rights to modify anything on the system.` {host} `refers to the computer you want to access. This can be an IP Address or a domain name 