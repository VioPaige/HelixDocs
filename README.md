Helix Discord Bot Documentation

    Prefix info

        Currently, changeable prefixes aren't out for Helix, they will most likely be coming before the end of June, the default prefix is "!!".

    Command info 

        - Verify
            - Arguments:                            <prefix>verify <robloxusername>
            - Requirements to use:                  none
            - Usage example:                        !!verify VioPaige
            - Bot response:
                - If verified before:               Sucessfully verified as <username>, enjoy your stay!
                - First time:                       Sucessfully found your roblox account, send a friend request to <botuser>, and then re-run the command.
                - After friend request:             Sucessfully verified as <username>, enjoy your stay!
                - Invalid username:                 This username does not exist.

 
        - Ban
            - Arguments:                            <prefix>ban <user mention> <reason>
            - Requirements to use:                  Ban members/Administrator permission
            - Usage example:                        !!ban @Paige#3198 breaking rules
            - Bot response:                 
                - Success case:                     <user mention> was succesfully banned with reason <reason>.
                - Ban reason(in serv. settings):    Banned by <moderator name> with reason <reason>
                - Dms (target user):                You were banned from the server <server name> by <moderator name> with reason <reason>.
                - Not enough permissions:           You do not have permission to use this command.


        - Kick
            - Arguments:                            <prefix>kick <user mention> <reason>
            - Requirements to use:                  Kick members/Administrator permission
            - Usage example:                        !!kick @Paige#3198 breaking rules
            - Bot response:                 
                - Success case:                     <user mention> was succesfully kicked with reason <reason>.
                - Dms (target user):                You were kicked from the server <server name> by <moderator name> with reason <reason>.
                - Not enough permissions:           You do not have permission to use this command.


        - Serverinfo
            - Arguments:                            <prefix>serverinfo
            - Requirements to use:                  none
            - Usage example:                        !!serverinfo
            - Bot response:                         Embed with info about the server the command was ran in.


       - Setwelcome
            - Arguments:                            <prefix>setwelcome <welcome message>
                - Additional info:                  If you fill in "<@>" in the welcome message, it will get replaced by mention of the user who joined.
                                                    The welcome messages will be sent in the channel you run the command in.

            - Requirements to use:                  Administrator permission.
            - Usage example:                        !!setwelcome Welcome to the server <@>! Enjoy your stay!
            - Bot response:
                - If welcome message is missing:    Please set a valid welcome message!
                - Sucess case:                      Succesfully set the welcome channel to <channel> and welcome message to <welcome message>
