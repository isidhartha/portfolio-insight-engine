# API Reference — Portfolio Insight Engine

## Trigger.dev Jobs

### `weeklyPortfolioReport`

**ID:** `weekly-portfolio-report`  
**Schedule:** Every Monday at 08:00 UTC

**Input payload (optional override):**
```ts
{
  portfolioCsvPath?: string;  // default: reads from PORTFOLIO_CSV env var
  recipient?: string;          // overrides TO_EMAIL
  dryRun?: boolean;            // generate report but don't send email
}
```

**Output:**
```ts
{
  success: boolean;
  emailId: string;
  tickersProcessed: number;
  totalValue: number;
  weekChangePercent: number;
  reportGeneratedAt: string;  // ISO 8601
}
```

---

## Portfolio CSV Format

The input CSV follows this schema:

```csv
ticker,shares,purchase_price,purchase_date
AAPL,10,150.00,2023-01-15
MSFT,5,250.00,2022-06-01
```

---

## yfin.dev Integration

Each ticker is queried against `https://api.yfin.dev/v1/quote/{ticker}`.

**Response fields used:** `regularMarketPrice`, `regularMarketChangePercent`, `sector`, `marketCap`, `fiftyTwoWeekHigh`, `fiftyTwoWeekLow`
