## Info on Creating a New Certificate Request File (using a template):

Navigate to the desired location of your certificates and run the following command:
* `openssl req -new -nodes -out sitename.csr -newkey rsa:2048 -nodes -keyout sitename.key -config request.txt`
> [Use if New Private Key is Needed]
* `openssl req -new -nodes -out sitename.csr -key sitename.key -config request.txt`
> [Using Pre-Existing Private Key]
