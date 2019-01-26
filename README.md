# Gold
Habbo packet logger & manipulator for Windows, Linux and Mac.

- Requires Java 8 https://www.java.com/nl/download/
- Requires The last supported Visual C ++ https://support.microsoft.com/nl-be/help/2977003/the-latest-supported-visual-c-downloads

# Windows execution
Double click Gold.exe, which will be delivered in the release. Note that executing Gold requires admin privileges.

# Linux execution
Execution command (temporary, verified in Ubuntu):
> $ sudo java -jar Gold.jar 

Additionally, you can add the -t flag to log the packets in your terminal instead of opening a new window for it.

Execute this command if you get the following error:
> Invalid MIT-MAGIC-COOKIE-1 keyInvalid MIT-MAGIC-COOKIE-1 keyException

> $ xhost +local:


# Features
* Log outgoing and incoming packets
* Injection, both sides
* Blocking & replacing packets functionality
* Packet expressions
* Encoding/decoding
* Auto detect hotel
* Retro support - enter game host & port manually (only the first time)
* Advanced scheduler
* Advanced extension support
* 2 included extensions on-release
