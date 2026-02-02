jekyll-theme-minimal

@import "{{ site.theme }}";
# Recode Ticket Bot - Setup & Commands

Welcome to **Recode**, your Discord ticket management bot. This guide will show you how to set it up and explain every command.

---

## 1. Setting Up Recode

Before using Recode, you need to configure the ticket system.

### Step 1: Run `/ticketsetup`
Use `/ticketsetup` to initialize the ticket system on your server.  

This will create the necessary channels and prepare the system for panels and tickets.  

After setup, you can send the ticket panel.

### Step 2: Send the Ticket Panel
**Command:** `/ticketpanel`  

Sends an interactive ticket panel to a selected channel. Users can click buttons to open tickets.

---

## 2. Ticket Commands

### User Commands
| Command | Description |
|---------|-------------|
| `/adduser` | Add a user to the current ticket, giving them access. |
| `/removeuser` | Remove a user's access from the current ticket. |
| `/close` | Close the ticket in the current channel (works like the Close button). |
| `/silentclose` | Close the ticket silently without notifications or transcript. |

### Admin Commands
| Command | Description |
|---------|-------------|
| `/closeall` | Close all open tickets in the server. |
| `/createticket <user>` | Create a ticket for a specified user, claiming it for you. |
| `/disable` | Disable ticket creation on this server. |
| `/enable` | Enable ticket creation on this server. |
| `/forceunclaim` | Force unclaim a ticket claimed by another support member (permissions only). |
| `/setreview` | Set the channel where ticket reviews are posted. |

### Blacklist / Permissions
| Command | Description |
|---------|-------------|
| `/blacklist <user>` | Prevent a user from creating tickets (reason required). |
| `/blacklistrole <role>` | Prevent all users with a role from creating tickets. |
| `/unblacklist <user>` | Remove a user from the blacklist. |
| `/unblacklistrole <role>` | Remove a role from the blacklist. |

### Ticket List & Tracking
| Command | Description |
|---------|-------------|
| `/list` | List all current tickets in the server. |
| `/ticketlist` | Shows a list of all current tickets with details. |

---


**Help and Support**

Need help or have questions? Join our **Support Server**: [https://discord.gg/NEUHRcV8Aw](https://discord.gg/NEUHRcV8Aw)  

The bot runs **24/7**, so your tickets are always active and ready.

