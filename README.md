URL: apidocs.intelycare.com


Documentation page for IntelyCare's Public APIs

## Steps to Update and Publish API documentation:

Update the API documentation in the file `apidocs.yaml`.

Build the html file with the following command

```npx @redocly/cli build-docs apidocs.yaml --output=index.html ```

Note: If you get the error "npx command not found", install node.js on your system before running the command again.

