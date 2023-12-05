# M159
To download the Executable on your VM run the following command:

```bash
curl -O -L https://raw.githubusercontent.com/lupree/m159/master/script
```
Before running the script, you need to add the execute permission to the file.
```bash
chmod +x script
```

To finally run the Executable use the following Syntax:
```bash
sudo ./test -g "groupCode" -t "Personal Access Token"
```
options:
    -g     Set the Group Code. (required)
    -t     Set the Personal Access Token for the Github Repository. (required)
    -h     Display a Help Message
