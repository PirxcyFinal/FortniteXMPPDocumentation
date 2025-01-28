- I've put these XMPP Messages together with the help of other projects such as `rebootpy` `fnbr.js` `Neonite`, also with the help of tools such as Fiddler and other "Man in the Middle" tools.
- As of now, this isn't in any particular order, nor is it in a good format (be greatful that i got bored and made this shit 😉)
- If you have any commands I may have missed, feel free to make a pull request and ill add it

# Commands
## `com.epicgames.gift.received`

- **Type**: From Server
- **Purpose**: 
  - This command is sent from the server to make the client refresh the `Common Core` profile. 
  - The client then checks if a giftbox item has been added to the profile.
  - Once the client comfirms a gift been added, a nice gift popup will show up with the items from the giftbox.

## `com.epicgames.social.party.notification.v0.MEMBER_STATE_UPDATED`

- **Type**: Both to the Server and From the Client
- **Purpose**: 
  - This command is mainly used in the Frontend (Lobby)
  - This command is used to Update information like equipped cosmetics, in lobby presence, or account level it is commonly used when in partys. 
