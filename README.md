# 🐔 Chicken Empire Tycoon 🥚

A fun and engaging web-based incremental business tycoon game where you build a chicken farming empire!

## How to Play

1. **Open the Game**: Simply open `index.html` in any modern web browser
2. **Start Small**: Begin with 3 chickens and $10
3. **Collect Eggs**: Click the collect button to gather eggs and earn money
4. **Expand**: Use your earnings to buy more chickens and upgrades
5. **Automate**: Purchase upgrades to increase efficiency and automation

## Game Features

### 🐔 Basic Gameplay
- **Chickens**: Each chicken lays 1 egg every 6 seconds (only when not starving!)
- **Egg Collection**: Collect eggs manually to earn $2 per egg
- **Feeding**: Chickens lose 2 hunger per minute and need regular feeding to survive
- **Growth**: Buy more chickens to increase production

### 🍽️ **NEW: Hunger System**
- **Hunger Decay**: All chickens lose hunger over time (2 points per minute)
- **Starvation**: Chickens with 0 hunger stop laying eggs and show as skulls 💀
- **Critical Warning**: Flashing warning when chickens reach dangerously low hunger
- **Visual Health Bars**: Each chicken shows a color-coded hunger bar
  - 🟢 Green (60-100%): Healthy and productive
  - 🟡 Yellow (30-60%): Getting hungry
  - 🔴 Red (0-30%): Starving and unproductive

### 🏠 Upgrades Available
- **Better Coop**: +20% egg production rate
- **Premium Feed**: +50% egg production rate  
- **Auto-Collector**: Advanced automation system with timeout and running costs
- **Golden Chickens**: Special chickens that lay golden eggs worth $10 each!

### 🌾 **Feeding Options**
- **Basic Feed ($1 per chicken)**: Restores 50 hunger points
- **Premium Feed ($3 per chicken)**: Restores 100 hunger points (full health!)
- **Auto-Feeder ($400)**: Automated feeding system with timeout and running costs ($0.15/sec)

### 💸 **NEW: Comprehensive Expense System**
**Automatic Business Expenses (Every 10 seconds - Fast cash flow pressure!):**
- **🏠 Rent**: $0.4 per chicken (facility costs scale with farm size)
- **⚡ Utilities**: Base $1.2 + $0.15 per chicken (electricity, water, heating)
- **👷 Staff Wages**: $1.5 per automation system (maintenance staff)
- **🛡️ Insurance**: 0.8% of total farm value (liability and equipment coverage)
- **🔧 Equipment Maintenance**: 1.2% of upgrade costs (repairs and upkeep)
- **🗑️ Feed Waste**: 3% of chicken count (spillage and spoilage)
- **📋 Regulatory Fees**: $0.6 per 10 chickens (government compliance)
- **📢 Marketing**: 0.8% of revenue (advertising to sell eggs)

**Automation Running Costs:**
- **🤖 Auto-Collector**: $0.10/second when active (5min max, $30 to start)
- **🌾 Auto-Feeder**: $0.15/second when active (10min max, $90 to start)

### 💀 **NEW: Bankruptcy & Failure System**
**Progressive Consequences When Money Runs Out:**
- **-$20**: Automation systems shut down (unpaid bills)
- **-$50**: Start losing chickens to bankruptcy
- **-$100**: Golden chickens get repossessed
- **-$150**: Equipment and upgrades downgraded/repossessed
- **-$200**: Complete game over → Emergency restart with loan

### 🏆 Achievements
- **First Egg**: Collect your first egg
- **Growing Flock**: Own 10 chickens  
- **Golden Touch**: Buy your first golden chicken
- **Caring Farmer**: Feed your chickens for the first time
- **Feeding Master**: Use the auto-feeder
- **Well-Fed Flock**: Keep all chickens above 80% hunger
- **Egg-cellent**: Collect 100 eggs total
- **Egg Millionaire**: Earn $1000
- **Automation Master**: Use the auto-collector
- **Golden Empire**: Own 5 golden chickens
- **Profit Master**: Achieve $50/min net profit
- **Cost Controller**: Pay $1000 total in expenses
- **Phoenix Rising**: Survive bankruptcy and recover
- **Full Automation**: Run both auto-systems simultaneously

### 💾 Game Progress
- Your progress is automatically saved to localStorage
- Game continues to generate eggs even when you're away (with auto-collector)
- Responsive design works on desktop and mobile devices

## Game Strategy Tips

### 💰 **Financial Management (CRITICAL!)**
1. **Watch Cash Flow**: Monitor net profit/min and costs/min - negative profit leads to bankruptcy!
2. **Expense Control**: Every chicken adds ~$2.40/min in expenses (rent, utilities, insurance)
3. **Start Conservative**: Don't expand faster than your revenue can support
4. **Emergency Fund**: Always keep reserve money for feeding and emergencies
5. **Automation Costs**: Auto-systems are expensive to run - use strategically

### 🐔 **Operations Strategy**
1. **Early Game**: Start with 3-5 chickens, focus on sustainable growth
2. **Feeding Balance**: Basic feed for maintenance, premium for emergencies
3. **Hunger Management**: Starving chickens = zero income but same expenses
4. **Upgrade Timing**: Coop/feed upgrades boost efficiency but increase maintenance costs
5. **Golden Chickens**: High income but very expensive to maintain

### 🤖 **Automation Strategy**
1. **Auto-Collector**: $30 for 5min runtime - only profitable with high egg production
2. **Auto-Feeder**: $90 for 10min runtime - expensive but prevents starvation
3. **Running Costs**: $0.10-0.15/sec adds up fast - monitor usage carefully
4. **Staff Wages**: $3/automation system even when not running

### 💀 **Bankruptcy Survival**
1. **Early Warning**: Red flashing profit = immediate danger
2. **Emergency Measures**: Sell chickens before you can't feed them
3. **Debt Levels**: -$20 shuts automation, -$50 kills chickens, -$200 game over
4. **Recovery**: Focus on basic chickens and manual collection until profitable

### 🏆 **Advanced Tips**
- **Real-Time Costs**: Check "Costs/Min" and expense breakdown for immediate cash flow impact
- **10-Second Billing**: Expenses hit every 10 seconds - much more frequent pressure!
- **Profit Margins**: Aim for positive green profit before expanding
- **Full Automation**: Requires massive income to support both systems
- **Golden Strategy**: 1 golden chicken = ~5 regular chickens in revenue but much higher costs

## Technical Details

- **Built with**: Pure HTML, CSS, and JavaScript
- **No Dependencies**: Runs entirely in the browser
- **Local Storage**: Game state persists between sessions
- **Responsive**: Works on desktop and mobile devices

## Getting Started

1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start building your chicken empire!

---

**Have fun building your poultry empire! 🐔🏆**
