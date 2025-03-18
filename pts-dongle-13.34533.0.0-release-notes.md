# Laird PTS Dongle 13.34533.0.0  Release Notes

## Version 13.34533.0.0

#### Fixes several issues that are related to MIC failure with or without loss of BIG sync:

*   **#247455:**  While streaming LE Audio data got the Connection Terminated Due To MIC Failure

*   **#27966:**   HCI_CONNECTION_TERMINATED_DUE_TO_MIC_FAILURE observed for TC TMAP/CT/VRC/BV-06-I

*   **#105184:**  Encrypted streams test fails

*   **#29171:**   [PBP/PBS/STR/BV-03-I]Connection Terminated due to MIC Failure

*   **#25826:**   PTS test fails citing MIC error after receiving ISO data

*   **#103505:**  BIG Sync lost 7/15/24

*   **#24617:**   Valid series of Public Broadcast Announcements as required in pass criteria are not compared and BIG Sync loss ends the case

*   **#33004:**   Regression:** BIG Sync Lost with MIC failure 3/11/24

#### Resolves issues related to the establishment of a second CIS connection:

*   **#145991:**  [BAP] Second CIS establishment failed with LL_REJECT_EXT_IND for audio configuration 7(i)

*   **#146841:**  [BAP] PTS not transmitting CIS packets on second CIS

*   **#30999:**   GMAP_UGG_LLU_BV-28-C

#### Resolves issues related to PAST:

*   **#26098:**    PTS does not receive the PAST sent by IUT resulting in test case failure

*   **#90742:**    Unicast to Broadcast Handover always can't get PAST

#### Resolves additional issues:

*   **#104137:**   PTS disconnects the link after moving all ASEs to streaming state

*   **#28604:**    [CAP] CIS establishment fails with status 0xb on broadcast to unicast handover test

*   **#145810:**   BAP/USR/STR/BV-364-C can not pass (by some parameter setting)

*   **#104317:**   Sometimes UL sound from Headset is not outputted during test BAP/USR/STR/BV-369-C

*   **#26360:**    PTS stops responding abruptly leading to test failure

*   **#144812:**   PBP/PBS/STR/BV-03-C (Failed to setup data path)

*   **#90116:**    Pairing fails as the PTS doesn't sends SMP PDU "pairing public key"

*   **#27626:**    Failed to send ASE notification for streaming state to TMAP unicast client

*   **#17063:**   Invalid ConnEvent Counter in LLCP CIS Indication (sent by PTS dongle)

*   **#26571:**   Both BAP/UCL/STR/BV-529-C and BAP/UCL/STR/BV-533-C tests are failing with connection timeout reason even after receiving ISO packets

*   **#28335:**   PTS crash during test case execution 4/6/24

*   **#135888:**  Failed to establish 2nd CIS with synchronization timeout for 7(i) audio configuration

*   **#103060:**  The BIS parameters vary depending on the PTS dongle version, and the BIS data becomes NULL every other time


## Packetcraft rel/r24.12.build34533

Dec 17, 2024
