# Project
A test script to discovery spring apps in your linux system, there is steps
1) login to the your linux system
2) find the java process for spring application
3) collect the spring apps runtime env and config
4) print the info to console

## Build the project
1) For linux, run build.sh
2) For Window, run build.bat

## Run the project
1) For linux: execute cmd output/discovery-l -server <servername> -port <port> -username <userwithsudo> -password <password>
2) For windows: execute cmd output/discovery.exe -server <servername> -port <port> -username <userwithsudo> -password <password>

### Limitation
Only probe the spring apps from linux VM

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
