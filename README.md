<div align="center">
  <h1><code> ToolZ Slot Bot</code></h1>
  <h2>🙌 Discord bot designed to streamline slot management in your server </h2>
   <h5>Click the thumbnail below to watch the tutorial on setting it up!</h5>
  <a href="https://drive.google.com/file/d/1ESOROJ6V65hZ3IOk70nerMaDbOmP12UQ/view">
    <img src="https://github.com/codewithriza/SlotBot/blob/main/image/banner.png" alt="Slot Bot Thumbnail" >
  </a>
</div>

---

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](##contributing)
- [Support](#support)


---


## Features

- Create slots with specified durations and categories
- Renew slots with updated durations
- Hold slots temporarily
- Unhold slots when ready
- Add and remove users from slots
- Set slot rules and guidelines
- Receive notifications for slot activities

## Usage 

To use the bot, follow these steps:

1. **Create a Slot:** Use the `,create` command to create a new slot. Example: `,create @user 1 d category1 4 Slot`.

2. **Add Users:** Use the `,add` command to add users to a slot. Example: `,add @user`.

3. **Renew a Slot:** Use the `,renew` command to renew a slot with updated duration. Example: `,renew @user #channel 1 m/d his Slot`.

4. **Hold a Slot:** Use the `,hold` command to temporarily hold a slot.

5. **Unhold a Slot:** Use the `,unhold` command to unhold a slot.

6. **Remove Users:** Use the `,remove` command to remove users from a slot. Example: `,remove @user`.

7. **Ping Notification:** Use the `,ping` command to receive a notification in the slot channel. You can use `,ping everyone` or `,ping @here` to mention everyone or here respectively. Example: `,ping`.

8. **Nuke Command:** Use the `,nuke` command to delete all messages in the slot channel if you have owner permissions. Example: `,nuke`.





> [!note]
> The Discord bot needs to have admin permissions and be positioned at the top of the role hierarchy, above the `buyers` in order to create a slot




## Installation

To install the bot, follow these steps:

1. Clone the repository: `git clone https://github.com/arshh1337/sbot.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your configuration: Create a `config.json` file with your bot token, category ID, staff ID, etc. Make sure to keep your bot token private and secure.
4. Replace token and other guild id, channel id, 2 category id in `main.py`
5. Run the bot: `python3 main.py`

> [!IMPORTANT]
> Ensure that your bot token is kept private and setup in config.json along with category id staff id etc create separate category for 1 and 2 and read through the code to understand


## Support

If you find this project useful, please consider giving it a star on GitHub! 🌟 

