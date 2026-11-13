# Clay inputs for the lead list

## Sculptor search prompt (step 3)
Find companies headquartered in Canada that are digital first banks, fintechs, online lenders or payment companies, and that move money into or out of customer bank accounts as part of their main product. Exclude RBC, TD, BMO, Scotiabank, CIBC, National Bank and any US bank. Return company name and domain.

## Tighten (step 4)
Keep: Country = Canada; industry in Banking, Financial Services, Payments, Lending.
Remove anything that is an accounting firm, a crypto only exchange, an insurer or a consultancy.
Then check the list against lead-list.csv; add any of the 25 that Clay missed by domain.

## Save (step 5)
List name: Real-Time Rail early movers, Nov 2026

## Signal (steps 6 to 8)
Signal type: news. Search phrase: "Real-Time Rail" participant, Payments Canada, November 2026.
For each of the top five, log in the table: signal text, date (2026-11-09), source URL (columns signal, signal_date, signal_source in lead-list.csv).

## Rank and next action (steps 9 and 10)
Copy rank and next action from lead-list.md.
