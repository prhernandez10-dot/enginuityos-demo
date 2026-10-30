# EnginuityOS live demo

Live at https://prhernandez10-dot.github.io/enginuityos-demo/

`index.html` is the whole demo in one file. Open it in any browser; it needs no server, no account and no database.

## What is in it

Every walkthrough shows where you are: a chapter strip at the top (done, you are here, still to come), a line on each step saying how many steps remain and what comes next, and counts on each chapter in the step list.

The demo walks the aviation aftermarket value stream end to end, for two kinds of asset:

| Section | What it does |
|---|---|
| The value stream | The ten stages (demand, sourcing, procurement, receiving and quality, inventory, repair, sales, fulfilment, finance, execution) with every step of the three walkthroughs placed on them, and where the ERP is observed |
| Parts: demand to cash (32 steps, live) | Runs the real material and lot ledgers in the browser: a customer demand, a package of unserviceable parts, a purchase order with approval limits, receipt and quality hold, repair with alert tasks, quality acceptance, reservation and sale, supplying an MRO work order from a lot of consumables, the recovery review and the exposure view |
| Engine: lead to locked record (15 steps, recorded run) | Replays a run of the real governed deal workflow: evidence verified by a second person, compliance, two approvers, award, custody, settlement, title, the executed outcome with per-asset amounts (allocated or unallocated, never split automatically), plan vs. actual, record lock, audit export and replay |
| Daily ERP Data Center (17 steps, live) | Runs the real Data Center package: declare a synthetic source, map its export with second-person approval, upload, catch a mislabeled file, a duplicate and a key conflict, reconcile day 2 against day 1, publish atomically, check freshness and rebuild the import history |
| Your desk: everything open | Every open item from all three walkthroughs on one desk, as the platform's state stands right now: overdue tasks, decisions waiting, items waiting on someone else, and whose move it is. Filter by role, or set the scene with "A busy morning" |
| Glossary | Every industry term used in the walkthroughs explained in plain language; the same terms are dotted-underlined in each step, with a "words used in this step" box |
| Tamper test | Change any stored record and watch the real hash-chain check catch it |
| How this demo works | What is real, what differs from a server, how it fits an existing ERP, what is not shown |

All data is synthetic: placeholder ids (`PN-SYN-*`, `SYN-TRADER-01`), "Demo … (fictional)" party names, the platform's synthetic test policy and its seeded synthetic ERP generator.
