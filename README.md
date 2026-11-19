# AlgoTrader dashboard

Live view of AlgoTrader trades, open positions, daily P&L, engine events and backtest results, stored in Supabase.

This repo holds only the built page (`index.html`). It contains no passwords or private keys: the Supabase URL and
publishable key are public by design, and data is shown only after signing in as an allowed user.
The source code is in the private AlgoTrader repo (`dashboard/`). To update: build there with `npm run build`
and copy `dashboard/dist/index.html` here.
