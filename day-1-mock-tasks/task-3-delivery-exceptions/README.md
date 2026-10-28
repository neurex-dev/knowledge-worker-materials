# Task 3: Delivery Exceptions Report

## The request

> Every Monday I need a short email listing last week's delivery problems at both depots, so my team can chase suppliers and carriers before stock runs short. I want anything late, anything that hasn't turned up, anything short or over, and anything damaged, with the PO number so we can act on it. Group it so I can see which supplier or carrier is causing most of the trouble.
>
> Priya Nadeau, Purchasing Lead

| | |
|:---|:---|
| **How often** | Weekly, every Monday |
| **Time by hand** | About 45 minutes |
| **Who reads it** | Priya and the two purchasing coordinators |

## Files

| File | What it is |
|:---|:---|
| `deliveries-2026-10-19-to-25.csv` | Inbound delivery log for both depots, for deliveries due Monday 19 to Sunday 25 October 2026. Exported at the end of Sunday 25 October |

## Background

- **Depots:** Quillmoor has two, North and South.
- **Columns:**
  - `qty_received` is what was counted in at the depot.
  - `qty_damaged` is how many of those were damaged on arrival.
  - A blank `received_date` means nothing has arrived yet.
- **Carriers:** Halvorsen Freight carries most supplier deliveries. Coldline Parts uses its own vans.

Fictional sample for workshop use. Quillmoor Supply, its people, customers, suppliers and figures are invented.
