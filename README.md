# Pay Accumulator 💰

A real-time earnings visualizer for Australian workers. Watch your salary accumulate second-by-second throughout your work day.

## Features

- **Real-time earnings counter** - See your after-tax (or before-tax) earnings tick up live
- **Australian tax calculations** - Accurate 2024-25 tax brackets, Medicare Levy, and Medicare Levy Surcharge
- **Private health insurance consideration** - Accounts for MLS if you don't have hospital cover
- **Cash visualization** - See your earnings represented as physical Australian banknotes and coins
- **Configurable settings**:
  - Working hours per day
  - Start time
  - Lunch break duration (0-60 minutes)
- **Detailed pay breakdown** - Per second, minute, hour, day, week, month, and year

## Usage

1. Enter your annual before-tax salary
2. Toggle whether you have private health insurance
3. Click "Start Accumulating"
4. Watch your earnings grow in real-time!

Use the Before Tax / After Tax toggle to switch views, and expand Advanced Settings to customize your work schedule.

## Deployment

This is a static single-page app. Simply host `index.html` on any static hosting service:

- **GitHub Pages** - Push to a repo and enable Pages in settings
- **Netlify** - Drag and drop the file
- **Vercel** - Import the repository

## Tax Calculations

Based on Australian Tax Office rates for 2024-25:

| Taxable Income | Tax Rate |
|----------------|----------|
| $0 – $18,200 | Nil |
| $18,201 – $45,000 | 16c per $1 over $18,200 |
| $45,001 – $135,000 | $4,288 + 30c per $1 over $45,000 |
| $135,001 – $190,000 | $31,288 + 37c per $1 over $135,000 |
| $190,001+ | $51,638 + 45c per $1 over $190,000 |

Plus 2% Medicare Levy (with low-income thresholds) and Medicare Levy Surcharge for high earners without private hospital cover.

## License

MIT

