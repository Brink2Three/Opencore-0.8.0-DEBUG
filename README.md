# Opencore-0.8.0-DEBUG
In progress config for a Lenovo Flex 5-15IIL05
Opencore configured in Debug mode
Most flags are set from the Comet lake "config.plist" segment, with the exception of the iGPU identifier and ensuring SetupVirtalMap is set to True.

Current state:
EFI boots into installer and will get through most of the install, then seems to get stuck on AppleKeyStore Operation Failed errors. 
