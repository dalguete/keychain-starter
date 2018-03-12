# keychain-starter (DEPRECATED)

Enable keychain per user login.

Basically that's all. Sets some profile config files, so keychain can start as soon
as the user login process finishes.

Started as a requirement in Docker containers, to have a ssh-agent running as soon
as a user has entered, and to avoid having to write a custom solution to start
that ssh-agent, well keychain appeared as the obvious solution.

What this does is nothing else than adding profile config files, so the keychain
can start automatically, and with it, the ssh-agent

Ubuntu PPA
==========

You can find the package as a PPA here https://launchpad.net/~dalguete/+archive/ubuntu/keychain-starter

Sidenote: About My Experience Creating Deb Packages Plus Ubuntu's PPA
---------------------------------------------------------------------

http://dalguete.github.io/#about-my-experiences-creating-deb-packages-plus-ubuntus-ppa
