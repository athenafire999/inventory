# 🛋️ Furniture Inventory Manager

A beautiful, static HTML inventory management app for furniture businesses. Track your inventory, sales, and profits all in one place! (Currency in £ GBP)

## Features

### 📦 Inventory Management
- **Organized Tabs by Status**: 
  - **Inventory tab**: Items marked as "Ready to Sell"
  - **Needs Work tab**: Items that need repairs/refinishing
  - **Sold tab**: All sold items with profit displayed
  - Clean separation for easy tracking and workflow management
- **Random Item Numbers**: Each item is automatically assigned a unique ID (e.g., FUR-123456)
- **Days in Stock Tracker**: Automatically calculates how many days each item has been in inventory
  - Color-coded: Green (0-30 days), Yellow (31-90 days), Red (90+ days)
  - Shows time from purchase to sale (for sold items) or purchase to today (for unsold items)
- **Profit Display**: Sold items show prominent profit box with color-coding
  - Green for profit, Red for loss
  - Large, easy-to-read profit amount
- **Multiple Photos**: Upload multiple photos per item
  - Click on any photo to view full-size gallery
  - Navigate between photos with arrow buttons or keyboard (← →)
  - Photo counter shows how many images each item has (e.g., 📷 3)
- **Work Required Photos**: Upload photos showing exactly what needs to be done
  - Take photos of scratches, damage, broken parts, areas needing refinishing
  - Photos displayed in yellow highlighted "Work Required" section
  - Click any work photo to view it full-screen
  - Add/delete work photos when editing items
  - Optional text notes to supplement the photos
- **Add Items**: Record furniture items with photos, purchase date, and price
- **Edit Items**: Update item details, mark as sold, add sold date and price
- **Delete Items**: Remove items from your inventory
- **Status Tracking**: Mark items as "Ready to Sell" or "Needs Work"

### 📊 Statistics Dashboard
- **Current Balance**: See your overall profit/loss (includes inventory + additional transactions)
  - Click "Edit Balance" to manage additional income and expenses
  - Track business expenses (rent, tools, repairs, etc.)
  - Record additional income or cash deposits
  - View complete transaction history
- **Money In**: Total revenue from sales
- **Money Out**: Total spent on purchases
- **Total Profit**: Automatic profit calculation from inventory
- **This Month's Sales**: See current month's performance at a glance
- **Monthly Sales Chart**: Beautiful bar graph showing revenue by month
- **Month by Month Breakdown**: Click to expand any month and see detailed sales
  - Revenue and profit per month
  - List of all items sold that month
  - Individual item profit calculations
- **Inventory Summary**: Count of total items, ready items, items needing work, and sold items
- **Average Days Metrics**: 
  - Average days in stock (for all items)
  - Average days to sell (for sold items only)
- **Transaction Details**: Complete table of all transactions with profit calculations and days in stock

### 💾 Data Persistence
- All data is saved automatically to your browser's local storage
- No server required - works completely offline
- Data persists between sessions

## How to Use

1. **Open the App**: Simply open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari)

2. **Add Your First Item**:
   - Click the **"Add New Item"** tab
   - Enter the item name (e.g., "Oak Dining Table")
   - Select purchase date
   - Enter purchase price (in £)
   - Choose status (Ready to Sell or Needs Work)
   - Upload one or multiple photos of the item (select multiple files at once)
   - Upload work photos showing damage/areas needing repair (optional)
   - Add text notes about work needed (optional)
   - Click "Add Item to Inventory"
   - You'll be automatically switched to the Inventory tab to see your new item

3. **Manage Items**:
   - View items by status:
     - **Inventory tab**: Items ready to sell
     - **Needs Work tab**: Items requiring repairs/work
     - **Sold tab**: All sold items with profit highlighted
   - Click on any item photo to view it full-screen
   - Use arrow buttons (or keyboard ← →) to navigate between multiple photos
   - **Work photos** appear in a yellow box showing what needs repair
   - Click any work photo to view it full-screen and see the damage clearly
   - Click **Edit** to:
     - Update item details or mark as sold
     - Change status (moves item to appropriate tab)
     - Add or delete work photos
     - Add text notes about work needed
   - When sold, enter the sold date and sold price - item automatically moves to Sold tab
   - Click **Delete** to remove an item

4. **View Statistics**:
   - Switch to the "Statistics" tab
   - See your overall financial overview
   - Check this month's sales performance
   - View the monthly sales chart
   - Click on any month in the breakdown to see detailed sales for that period
   - Review complete transaction history

5. **Manage Your Balance**:
   - Click "Edit Balance" button on the Current Balance card
   - Add expenses like rent, utilities, repairs, advertising, etc.
   - Add other income like cash deposits, refunds, etc.
   - View and delete transaction history
   - Your balance automatically updates to include all transactions

## Technical Details

- **Pure HTML/CSS/JavaScript**: No dependencies, frameworks, or build tools required
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations
- **Local Storage**: Data stored in browser's localStorage API

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## Tips

- **Backup Your Data**: Export your localStorage data periodically (browser settings)
- **Photo Quality**: Use reasonable image sizes for better performance
- **Regular Updates**: Mark items as sold promptly to keep accurate statistics
- **Status Updates**: Change status from "Needs Work" to "Ready to Sell" as you refurbish items

## Future Enhancements (Optional)

- Export data to CSV/Excel
- Print reports
- Search and filter functionality
- Multiple photo support per item
- Category/type classification

---

**No installation required - just open and use!** 🚀

