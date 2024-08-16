# Laird PTS Dongle 13.23310.0.0 Release Notes

## Version 13.23310.0.0

**28272**: Fixes a regression issue where an ACL connection failed to be re-established

**27822** and **17899**: fixes an issue where LL\_START\_ENC\_RSP PDU was not encrypted

**24239**: Fixes BIG sync lost with MIC error.

**17373**: Fixes issue where PTS tool does not acknowledge the CODEC config and Receiver Start Ready messages sent by the IUT

**16728**: Fixes an issue where there was no periodic advertisement being received for 48\_5\_1 and 48\_5\_2 HQ QoS setting

**22894**, **17127**, **17854** and **22930**: Fixes a collision between power control and encryption procedures

**17494**: Fixes an issue where erratum 17583 was not implemented

**21390**: Fixes an issue when creating 2 CISs. Improvements to the adjacent scheduling.

**19844**: Fixes issue where the LE Channel Reporting Indication was incorrectly categorized as a "receive request event"

**21919**: Fixes issue where BIG sync lost with reason "MIC Failure"

**19845**: Fixes an encryption scratch buffer overrun that was causing a MIC failure

**31306**: Fixes an issue where the BIS encryption state was not properly reset

**31308**: Fixes an issue where the PAwR event was not properly initialized if the PAST procedure was used

**25826**: Fixes a BIG sync lost error with reason as MIC failure

**28335**: Fixes an issue where the extended header was included in the Advertising Response report

**33004**: Fixes BIG\_sync\_lost error with an encrypted ISO packet

**24617**: Fixes a BIG sync lost error with the reason as MIC failure

### Packetcraft r23.12.4.build19404

05 Mar 2024