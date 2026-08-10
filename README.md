# NightFrame

NightFrame is a Windows desktop app for Warframe Market trading. It keeps your stock, orders, chats, and trade history in one place.

## Features

### Live Trader

- Creates, updates, and removes WTB and WTS orders as market prices change.
- Runs WTB, WTS, and Wishlist modes separately.
- Uses your buy quantity, minimum profit, maximum buy price, refresh time, and 0p stock pricing settings.
- Removes WTB orders that no longer meet your profit target and adds them again when the profit returns.
- Tracks your remaining daily trades and shows the next Warframe reset.
- Lets you blacklist an item for WTB, WTS, or both. The item's trade tax is shown in the blacklist.

### Stock and trades

- Add bought or farmed items with their quantity, level, and price paid.
- Remembers the cost and order of each copy when you own the same item more than once.
- Reads completed trades from Warframe's `EE.log` and updates stock, history, profit, Wishlist quantity, and daily trades.
- Matches trades with your WFM orders so free extras are not counted as paid items.
- Shows a review popup when a purchase or sale cannot be matched safely.
- Search, edit, hide, list, sell, or remove stock items. Bulk actions are included.

### Wishlist

- Add a WFM item with the level and quantity you want.
- Set your own price, or use 0p to follow the market price.
- Reduces the quantity after each purchase and removes the item when it is complete.
- Bypasses the normal WTB blacklist when Wishlist mode is enabled.

### Warframe Market

- Login with WFM and switch between Online, In Game, and Invisible.
- View, search, filter, review, and remove your WTB and WTS orders.
- See order totals and a list of interesting items with volume, price, profit, and trade tax.
- Read and reply to WFM chats without leaving the app.
- Refreshes new chat messages and supports deleting one or several chats.

### Reports and alerts

- Dashboard for total profit, today's profit, the last 7 days, platinum spent and earned, margins, best items, and recent trades.
- Full buy and sell history with quantity, price, profit or cost, player, and date.
- Sound and Windows notifications for completed trades, in-game messages, and WFM chats.
- Separate notification controls, volume settings, test buttons, and Quiet mode.

### Local data and updates

- Stores stock, settings, trade history, and app data locally in `nightframe.db`.
- Can keep automatic `nightframe.db` backups in the user's Google Drive and restore them on another PC.
- Keeps WFM login details and device data out of Google Drive backups.
- Checks for new versions and lets you install them from inside the app.

## Download

Download the latest installer from [GitHub Releases](https://github.com/i-KaBoS/nightframe/releases/latest). You only need the setup `.exe`.

NightFrame is an independent project inspired by QuantFrame.
