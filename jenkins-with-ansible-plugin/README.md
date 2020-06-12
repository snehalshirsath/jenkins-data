# ansible-plugin-jenkins-march20

troubleshooting:

1) add below line in /ansible.cfg file to make ignore key checking :

[defaults]
host_key_checking = False

https://stackoverflow.com/questions/46929624/failed-to-connect-to-the-host-via-ssh-host-key-verification-failed-r-n/46933307

2) make chnage in /ansible.cfg file :

deprecation_warnings = False

3) credentials:  The plugin supports the credential type "SSH Username with private key"
add ssh private key in credentials
