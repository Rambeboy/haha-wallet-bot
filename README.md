## HAHA WALLET AUTO CLAIMER

An automated tool for claiming karma and completing tasks in Haha Wallet. Built with Node.js and features a terminal-based dashboard interface.

## BOT FEATURE

- Automated daily check-in
- Automatic task completion (basic and social tasks)
- Karma and rank tracking
- Beautiful terminal dashboard interface
- Multi-account support
- Real-time status updates

## PREREQUISITE

1. Register a Haha Wallet account:

- Download and install the Haha Wallet extension: [Chrome Web Store](https://chromewebstore.google.com/detail/haha-wallet/andhndehpcjpmneneealacgnmealilal?hl=en-US&utm_source=ext_sidebar)
- [Register Haha Wallet](https://join.haha.me/NOFAN-4L3VVJ)
- Complete the registration process

2. Make sure you have installed:
- Node.js (version 14 or higher)
- npm (normally comes with Node.js)

## INSTALLATION

1. Clone this repository:

```bash
git clone https://github.com/Rambeboy/haha-wallet-bot.git && cd haha-wallet-bot
```

2. Install dependencies:

```bash
npm install && npm run setup
```

3. Configure your accounts:

```bash
nano accounts/accounts.js
```

## USAGE

To start the bot:

```bash
npm run start
```

### DASHBOARD CONTROLS

- Press `q` or `ESC` to quit
- Press `r` to refresh the screen

## FEATURES EXPLANATION

1. **Multi-Account Support**

- Process multiple accounts sequentially
- Each account's progress is tracked separately
- Secured password storage in local file

2. **Automated Tasks**

- Daily check-in
- Basic task completion
- Social task claiming
- Karma collection

3. **Dashboard Interface**

- Real-time status updates
- Account balance display
- Task progress tracking
- Clear visual organization
- Colored sections for easy reading

4. **Auto-Retry System**
- Automatic retry on failures
- 12-hour cycle for daily tasks
- Error handling and recovery

## LICENSE

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

## DISCLAIMER

This tool is for educational purposes only. Use at your own risk. The developers are not responsible for any banned accounts or lost karma points.