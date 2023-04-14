Network Address Logger; Scripted Batch Tool

Update: Summary updated...

There are plans to try and finish the remote function. I don't have a current immediate need or use case for this tool so this is a "when I can" type of situation. Additionally, I'd like to branch this off to run in PowerShell instead as the specific scenario requiring it to be in batch no longer exists. I've also considered starting this project over again in Python but considering this would ultimately defeat the purpose of the "only one file needed" with the easiest approach, I have no current plans to do this.

Summary: Original creation ~ 2016-2017 Approach type ~ ORF (Only Required File)

The reason this tool was written in batch is the original job it was intended for required compatibility for Win 98, Win XP, and Win Vista systems.

A scripted tool for logging NAT changes (IP, Gateway, Subnet, or MAC address) for the device it's running on by pulling "ipconfig" lines. The was a remote deployment feature was last being worked on. It allows the ability monitor multiple machines using PStools suite integration. The remote feature is currently incomplete and will be worked to finish in the future.