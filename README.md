# Windows RDP
## Specifications :
  * OS : Windows Server 2019 (Current Latest)
  * CPU : Intel Xeon Dual Core
  * RAM : 7GB
  * SSD : 14GB Ephemeral
  * Duration : 6 Hours
## Usage :
  * Fork this repository.
  * Visit [Ngrok](https://dashboard.ngrok.com) & get your auth token.
  * In Github go to Settings > Secrets > New Repository Secret.
  * Add secret ```NGROK_AUTH_TOKEN``` with value of Ngrok Token
  * In Github go to Actions > Select ```Windows-RDP``` Workflow > Start the Workflow.
  * Reload the page and select the Running Workflow > Build > At last 2nd stage get your login credentials.
## Credits :
  * [Coff9n](https://github.com/c9ffin/rdp)
