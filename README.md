# Stock Wars Trading Game

A simple stock market simulation game built with HTML, CSS, and JavaScript.  The goal of the game is to accumulate wealth by trading stocks over a period of 30 in-game days.

## Table of Contents

*   [How to Play](#how-to-play)
*   [Technical Details](#technical-details)
*   [Screenshots](#screenshots) *(Add screenshots as you develop)*
*   [Future Enhancements (TODO)](#future-enhancements-todo)
*   [Running the Game](#running-the-game)
*   [Credits](#credits)
*   [License](#license)

## How to Play

1.  **Market Prices:** The "Market Prices" table shows the current price of each stock.  Prices fluctuate randomly each day, influenced by a global market trend and occasional news events.
2.  **Buy/Sell:** Select a stock from the dropdown menu. Enter the quantity of shares you want to buy or sell in the input fields. Click "Buy" to purchase shares (go long) or "Sell" to sell shares you already own.
3.  **Short Selling:** You can also short sell stocks you expect to decline.  Enter the quantity you want to short sell and click "Short Sell".  To close a short position, you must "Cover Short" by buying back the same number of shares.
4.  **Portfolio:** The "Portfolio" table displays your current stock holdings (long and short positions).
5.  **Cash, Debt, and Health:** Your current cash balance, debt, and health are displayed. Your health will decrease if you are in debt.
6.  **Margin:** You have access to margin (loans) to increase your buying power. Click "Take Loan" to borrow $1000, and "Repay Loan" to repay $1000.
7.  **Event Log:** The "Event Log" displays important events, such as news affecting stock prices, your trades, and loan transactions.
8.  **Locations:** Travel to different locations to potentially encounter different market conditions (not yet fully implemented).
9.  **File Menu:**
    *   **New Game:** Starts a new game, resetting all progress.
    *   **Save Game:** Saves your current game state to your browser's local storage.
    *   **Load Game:** Loads a previously saved game from local storage.
10. **Settings Menu:**
    *   **Difficulty:** Adjusts the game's difficulty (currently only logs the change).
    *   **Transaction Fee:** Enables or disables a $10 fee per trade. *(Currently no transaction fees implemented)*
11. **Help Menu:** Provides instructions on how to play the game.
12. **Price History:** Click "Show Price History" to view the price history of the selected stock.
13. **Game Over:** The game ends after 30 days. Your final score is calculated based on your cash and debt.

## Technical Details

*   **HTML:** Provides the structure of the game interface.
*   **CSS:** Styles the game using a Windows 95-inspired theme and grid/flexbox for layout.
*   **JavaScript:** Implements the game logic, including market price generation, trading, event handling, and UI updates.
*   **Local Storage:** Used to save and load game progress.

## Screenshots

*(Add screenshots of your game here as you develop it.  Use Markdown image syntax: `![Screenshot 1](path/to/screenshot1.png)`)*

## Future Enhancements (TODO)

*   **Location-Based Pricing:** Implement different prices for stocks in different locations.
*   **Improved Event System:** More diverse and impactful random events.
*   **Debt Interest:** Implement interest accrual on debt.
*   **Bankruptcy:** Add a bankruptcy mechanic.
*   **Win/Lose Conditions:** More detailed win/lose conditions.
*   **Visual Stock Trends:** Arrows or other indicators to show stock price trends.
*   **Enhanced UI/UX:** Improve visual clarity and user experience.
*   **More Advanced Trading Features:** Explore short selling, margin trading, etc.
*   **Advanced Game Mechanics:** News events affecting specific stocks, stock splits, dividends, etc.
*   **Sound:** Add sound effects and background music.
*   **Transaction Fees:** Implement transaction fees.

## Running the Game

1.  Clone the repository: `git clone https://github.com/Anderson-s-Projects/Trade-Game.git`
2.  Navigate to the project directory: `cd Trade-Game`
3.  Open `index.html` in your web browser.

## Credits

*   Game concept inspired by classic trading games.
*   Windows 95 UI style inspired by the original operating system.

## License

(No license specified) *(You can add a license later if you choose)*
