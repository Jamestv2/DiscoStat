![](https://i.imgur.com/03Ub9hj.png)
DiscoStat is a powerful and flexible Discord server status plugin for Rust servers. This plugin seamlessly integrates with Discohook, allowing server administrators to showcase the current status of their server through customizable webhooks.

##     Features:
* Fully customizable webhooks for displaying server status.
* Three distinct statuses: Online, Offline, and Restart.
* Each status can have its own unique Discord webhook URL and Discohook Sharelink.
* In-game commands for administrators to easily set and update webhook configurations.
* Automatic reloading of configurations with the "/discoreload" command.
* Uses Discohook to send formatted messages to Discord for enhanced visibility.

##     How to Use:
1. Configure the plugin by setting Discord webhook URLs and Discohook Sharelinks for Online, Offline, and Restart statuses.
2. Customize messages and colors to match your server's theme.
3. Enjoy real-time updates on your Discord server's status, effortlessly communicated through Discohook.

##     Permissions:
**The plugin doesn't rely heavily on permissions but requires administrator privileges for certain in-game commands.**

##    Console Commands:
**/discoreload - Reloads the DiscoStat configuration.**

##    In-Game Commands:
**/setdiscohookurl <type> <webhook_url> <sharelink> - Set or update the Discord webhook URL and Discohook Sharelink for a specific status type (online, offline, restart).**

##    Localization:
**All messages are in English by default. Localization in other languages can be added using the Lang API.**

##     Note:
**Ensure that DiscoStat is configured with accurate webhook URLs to display server status updates correctly on your Discord server.**

##     License:
**This plugin is released under a MIT license.**

##    Performance Considerations:
**(https://docs.google.com/document/d/1Nn-ODG3TtUMWdtx3QOVcX3e3F5QdBXSsiLT5sUlyWGY/edit?usp=sharing)[All proformance optimizations are listed on the google document.]**

##     Contact:
**For support or inquiries, reach me using discord, @solorads or [solorads.site](https://solorads.site)** Or if you'd like to use the rusttools method: **contact@rusttools.site or [rusttools.site](https://rusttools.site) has the rest of contact information.**



# Plugin uses [Discohook](https://https://discohook.org/?data=eyJtZXNzYWdlcyI6W3siZGF0YSI6eyJjb250ZW50IjpudWxsLCJlbWJlZHMiOlt7InRpdGxlIjoiVGhhbmsgeW91IGZvciB1c2luZyBEaXNjb1N0YXQsIERpc2NvU3RhdCB3aWxsIGJlIGFwYXJ0IG9mIHJ1c3R0b29scy5zaXRlIHBsdWdpbnMgYnV0IGZvciBub3cgaXMgYW4gb3BlbiBzb3VyY2UgcHJvamVjdCEiLCJjb2xvciI6MjAzMTg3MX1dLCJmaWxlcyI6W3t9XX19XX0) for webhook customization!