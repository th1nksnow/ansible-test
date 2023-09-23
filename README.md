# ansible-test

Testing Ansible

Playbook description:

- playbook.yml

  ==WebServer and WebPage setup==

Tasks include Block for Debian Family OS:  Install Nginx; Pushing files; Start Nginx.

Handlers: Restart Nginx; Clear destination.

- rolebook.yml

  ==WebServer and WebPage setup as Role==

Another method to realize the same tasks (playbook.yml).
Added template and task for generating one more page.

- pingbook.yml

  ==Ping servers==

- varsbook.yml

  ==Enjoy variables==
