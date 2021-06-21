Helix Discord Bot Documentation

    If you have more questions after reading the docs, or want to request a feature, dm me at Paige#3198
    
    How to invite the bot to your server
    
        To invite with administrator permission (default invite), paste this oauth url in your browser: 
            https://discord.com/api/oauth2/authorize?client_id=854015657350529064&permissions=8&scope=bot
        
        To invite with weak permissions, use this invite link (You might need to re-invite if new commands are added): 
            https://discord.com/api/oauth2/authorize?client_id=854015657350529064&permissions=469814374&scope=bot
    
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
                
       - Whois
            - Arguments:                            <prefix>whois
            - Requirements to use:                  none
            - Usage example:                        !!whois @Paige#3198
            - Bot response:                         Embed with info about the mentioned discord user (if roblox verified, also roblox user info)
       
       
       
       
       
       
       
       
       
       
       
       
