---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Release notes

## Version 5.26

### New Features

* Solver updated to the Xpress Suite Optimization 8.14.
* Included the hydro unit inertia representation.
* Included the frequency control ancillary service (FCAS) representation.
* Included the representation of hydro operative average constraints (turbined / spilled / total outflow / storage / forebay / tailwater level).
* Included the forebay elevation x spillway rating curve outflow table with hourly changing factors.</Re
* Included the definition of hill curve chart for hydro units.
* Included the ability to assign different amounts (upward / downward) of secondary reserve in batteries.
* Included the ability to lead with negative market / bus energy prices for revenue maximization criteria.
* Included the ability to bid different amounts / prices (upward / downward) of secondary reserve for a group of plants.
* Included the infiltration x storage table
* Included the bypass valve representation.
* Included the possibility to define smoothing feature penalty.</Re
* Included the representation of daily forebay ramps.
* Included the control to enable / disable individual generation constraints.</Re
* Extended the automatic recovery tool for turbined / spilled initial conditions.
* Extended the convergence report to include the partial executions of the rolling horizon scheme.
* Extended the possibility to define multiple hydro unit generation forbidden zones per forebay level.
* Extended the possibility to define penalties for target storage constraints.
* Maximum number of target generation constraints extended to 50000.
* Maximum number of DC links extended to 5000.
* Hydro unit production modeling reformulated.
* Thermal combined cycle production modeling reformulated.
* Thermal fuel consumption modeling reformulated.
* New output results file: Average Elastic Demand Price.
* New output results file: Stage Resolution.
* New output results file: Hydro unit inertia.
* New output results file: Hydro unit synchronous condenser status.
* New output results file: Hydro unit synchronous condenser start-up / cost.
* New output results file: Total received outflow.
* New output results file: Hydro unit FCAS assignation (raise / lower).
* New output results file: Bypass valve flow.
* New output results file: Bypass valve flow (min / max) violation.
* New output results file: Hydro average limit violation.

### Corrections

* Corrected a bug in the general minimum total outflow penalty.
* Corrected a bug in the exclusive secondary reserves output.
* Corrected a bug in the energy price and profit output.
* Corrected a bug in the initial condition applied to cold ramp constraints of hydro plants / units.
* Corrected a bug in the sum of circuit flows constraint.
* Corrected a bug in the reading process of missing renewable generation data.
* Corrected a bug in the constant tailwater level representation.



### Support or Contact

Having trouble? Contact our support team via `sddp@psr-inc.com` and we’ll help you sort it out.

