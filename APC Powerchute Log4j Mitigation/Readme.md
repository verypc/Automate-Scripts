APC Powerchute Business Edition Log4j Mitigation

Script to apply the mitigations from APC recommendations https://www.se.com/ww/en/download/document/SESB-2021-347-01/

Required 7za.exe to be present in LTShare\Transfer\Utilities\7za.exe

The script will download the 7za.exe to the c:\windows\ltsvc\packages folder to carry out the mitigation by deleting the JndiLookup.class file from the affected JAR.

The script will check Automate's software table to confirm you have a supported version of the software installed.

Once confirmed, it will delete the class file from the JAR.
