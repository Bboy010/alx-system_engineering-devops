# Web server project

In this project, I learned to set up and use my first web server. I was Nginx configuration

## Tasks :page_with_curl:

* **0. Transfer a file to your server**
  * [0-transfer_file](./0-transfer_file): Bash script that transfers a file
  from our client to a server.
  * Accepts 4 arguments:
    1 The path of the file to be transferred.
    2 The IP of the server to transfer the file to.
    3 The username that `scp` connects with.
    4 The path of the SSH privtae key that `scp` uses.
 * Display Usage: 0-transfer_file PATH_TO_FILE IP USERNAME PATH_TO_SSH_KEY if less than 3 parameters passed
  * `scp` transfers the file to the user home directory `~/`.
 * Strict host key checking must be disabled when using scp

* **1. Install nginx web server**
  * [1-install_nginx_web_server](./1-install_nginx_web_server): Bash script
  that configures a new Ubuntu machine with Nginx.
  * Nginx listens on port 80.
  * When querying Nginx at its root `/` with a `curl` GET request,
  it returns a page containing the string `Hello World!`.

* **2. Setup a domain name**
  * [2-setup_a_domain_name](./2-setup_a_domain_name): A text file containing
  the domain name set up for the server through .TECH Domains.

* **3. Redirection**
  * [3-redirection](./3-redirection): Bash script that configures a new Ubuntu
  machine with Nginx.
  * Setup is identical to [1-install_nginx_web_server](./1-install_nginx_web_server)
  plus:
    * The location `/redirect_me` returns a `301 Moved Permanently` redirection
    to another page.

* **4. Not found page 404**
  * [4-not_found_page_404](./4-not_found_page_404): Bash script that configures
  a new Ubuntu machine with Nginx.
  * Setup is identical to [1-install_nginx_web_server](./1-install_nginx_web_server)
  plus:
    * Features a custom 404 page containing the string `Ceci n'est pas une page`.

* **5. Install Nginx web server (W/ Puppet)**
  * [7-puppet_install_nginx_web_server.pp](./7-puppet_install_nginx_web_server.pp): Configuring server with puppet

* Requirements:

	* Nginx should be listening on port 80
	* When querying Nginx at its root / with a GET request (requesting a page) using curl, it must return a page that contains the string Hello World!
	* The redirection must be a “301 Moved Permanently”
	* Your answer file should be a Puppet manifest containing commands to automatically configure an Ubuntu machine to respect above requirements
