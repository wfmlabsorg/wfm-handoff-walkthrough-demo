# The Forecaster Hand-off — walk-through

> What an agent team does in the background when one forecaster hands a migration plan to another.

Live: https://handoff.wfmlabs.com

## What it shows

When a client moves between operations, the departure forecaster hands a methodology to the arrival forecaster. The risk sits in the assumptions between them. This eight-stage walk-through (synthetic data) shows agents that:

1. ingest the departure workbook in a Codespace and repair it into ten clean tables;
2. turn every constant typed into a cell into a registered assumption;
3. extract the arrival plan's assumptions from plans, checklists, emails and meetings;
4. pair the two sides and re-cut history by market, hours and language;
5. run a library of lessons from past migrations as deterministic tests;
6. turn every gap into a question for the arrival forecaster, with owner and due date;
7. record an alignment session as one signed assumption register;
8. check actuals against every agreed assumption after go-live, and add each miss to the library as a structured lesson.

Purple stages are human gates. The confidence ledger shows each claim's status and confidence as the agents work.

## Notes

All data is synthetic. Deep links: append `#stage=N` to open stage N with earlier stages complete.

## License

MIT
