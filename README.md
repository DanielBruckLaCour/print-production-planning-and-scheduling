
# Print Production Planning and Scheduling Framework

A practical framework for planning print jobs, sequencing production, allocating capacity, managing bottlenecks, tracking milestones, and protecting delivery commitments.

## 1. Purpose

Print production requires several activities to happen in the correct sequence. Artwork preparation, proof approval, material availability, printing, finishing, inspection, and delivery all affect the final schedule.

When these activities are poorly coordinated, jobs compete for capacity, deadlines slip, and urgent orders disrupt planned work.

This framework provides a structured approach to production planning and scheduling across commercial printing, packaging, catalogs, brochures, labels, and branded materials.

It covers:

- Job intake and production readiness.
- Production routing and job sequencing.
- Equipment and labor capacity.
- Material availability.
- Bottleneck identification.
- Schedule changes and urgent orders.
- Production monitoring and performance measurement.

## 2. Establish Production Requirements

Every job needs a complete production brief before it enters the confirmed schedule.

| Requirement | Information to capture |
|---|---|
| Job reference | Unique production identifier |
| Customer or project | Responsible account or project |
| Product | Brochure, catalog, packaging, label, or other item |
| Quantity | Required production quantity |
| Specifications | Dimensions, materials, colors, and finishing |
| Artwork status | Files received and approved |
| Proof status | Approval requirements and current status |
| Production method | Digital, offset, or other process |
| Finishing | Binding, folding, coating, cutting, or assembly |
| Required delivery | Confirmed destination date |
| Supplier | Assigned production provider |
| Priority | Standard, high, or critical |

### Production readiness checks

Before scheduling, confirm:

1. The order quantity and specifications are complete.
2. Artwork is approved or has a confirmed approval deadline.
3. The production method is suitable for the job.
4. Required materials are available or have confirmed arrival dates.
5. Equipment and finishing capacity are available.
6. The delivery date accounts for production, inspection, packing, and transportation.

Do not treat an unconfirmed material delivery or pending approval as a completed prerequisite.

## 3. Map the Production Workflow

A production schedule must cover the complete job, not just the printing stage.

| Stage | Main activity | Completion requirement |
|---|---|---|
| Job intake | Review order and specifications | Complete production brief |
| Prepress | Prepare and check artwork | Production-ready files |
| Proofing | Obtain customer approval | Approved proof |
| Material preparation | Confirm stock and supplies | Materials available |
| Scheduling | Assign equipment and capacity | Confirmed production slot |
| Printing | Produce printed sheets or components | Printing completed |
| Finishing | Complete binding, cutting, or assembly | Finished product |
| Quality inspection | Check against approved requirements | Quality approval |
| Packing | Prepare finished goods | Shipment-ready order |
| Delivery | Dispatch and confirm receipt | Delivery completed |

For each stage, record:

- Responsible owner.
- Planned start and finish.
- Required resources.
- Predecessor activities.
- Current status.
- Completion evidence.

A job should not advance past a required approval or quality checkpoint without authorization.

## 4. Build the Production Schedule

The schedule should show what needs to happen, when it needs to happen, and which resources are required.

### Scheduling information

Record:

- Job reference and quantity.
- Production route.
- Equipment requirements.
- Estimated setup and run time.
- Finishing requirements.
- Material availability.
- Planned start and completion dates.
- Assigned production resource.
- Required delivery date.
- Dependencies and approval dates.

### Production schedule template

| Job | Process | Planned start | Planned finish | Resource | Status |
|---|---|---|---|---|---|
| JOB-001 | Offset printing | Day 1 | Day 2 | Press A | Planned |
| JOB-002 | Digital printing | Day 1 | Day 1 | Press B | In progress |
| JOB-003 | Binding | Day 3 | Day 4 | Finishing A | Pending |
| JOB-004 | Packaging | Day 4 | Day 5 | Assembly A | Pending |

The entries are illustrative. Actual dates and assignments must reflect confirmed capacity and job requirements.

### Schedule dependencies

A dependent activity cannot begin until its required predecessor is complete.

Examples:

- Printing depends on approved artwork and available materials.
- Finishing depends on printing being completed.
- Final inspection depends on finishing being completed.
- Dispatch depends on quality approval and packing.

Record dependencies explicitly. Otherwise, a schedule may show a job as ready even when an earlier activity remains incomplete.

## 5. Sequence Jobs Using Clear Rules

When several jobs compete for the same equipment, the production manager needs a consistent sequencing method.

No single rule works for every situation. Select the method according to delivery commitments, production constraints, and commercial priorities.

### Common sequencing methods

| Method | Scheduling rule | Appropriate use |
|---|---|---|
| Earliest due date | Schedule the job with the nearest deadline first | Managing delivery commitments |
| Shortest processing time | Schedule jobs with shorter processing times first | Reducing waiting time in suitable workloads |
| Priority-based | Schedule according to approved business priority | Critical customer or event requirements |
| Setup grouping | Group compatible jobs to reduce changeovers | Similar materials, sizes, or production settings |
| Critical-path based | Protect activities that determine the final completion date | Jobs with multiple dependent stages |

### Recommended sequencing process

1. Identify jobs competing for the same resource.
2. Remove jobs that are not production-ready.
3. Identify fixed delivery commitments.
4. Calculate remaining processing time.
5. Check dependencies and finishing capacity.
6. Sequence jobs using due dates and approved priorities.
7. Group compatible jobs where this does not threaten delivery commitments.
8. Review the effect on downstream activities.

### Example: Competing jobs

| Job | Required delivery | Remaining production time | Priority |
|---|---|---:|---|
| A | Day 6 | 2 days | Standard |
| B | Day 4 | 1 day | High |
| C | Day 5 | 3 days | Standard |

Job B has the nearest deadline and the shortest remaining production time. It should receive early consideration.

However, the final sequence must also account for equipment compatibility, setup requirements, material readiness, and downstream capacity.

A sequencing rule is a decision aid, not a substitute for checking the complete production plan.

## 6. Calculate Production Capacity

Scheduling requires a realistic view of available production time.

### Available capacity

**Available capacity = Scheduled operating time − Planned downtime**

Account for:

- Equipment maintenance.
- Setup and changeover time.
- Operator availability.
- Material handling.
- Production interruptions.
- Cleaning and calibration.
- Finishing and packing capacity.

### Capacity utilization

**Capacity utilization (%) = Actual production time ÷ Available production time × 100**

High utilization does not automatically indicate an efficient schedule. A resource operating close to its practical limit has little room for urgent jobs, breakdowns, or production changes.

### Resource loading

Resource loading compares the work assigned to a resource with its available capacity.

**Resource loading (%) = Required resource hours ÷ Available resource hours × 100**

### Worked example: Press capacity

A printing press has 40 scheduled operating hours for the week.

- Planned maintenance: 4 hours.
- Available capacity: 36 hours.
- Scheduled job requirements: 30 hours.

Resource loading:

**30 ÷ 36 × 100 = 83.3%**

The press has 6 available hours remaining.

A new job requiring 8 hours cannot be added without changing the schedule, extending operating time, or moving existing work.

This calculation should be repeated for each constrained resource, including finishing equipment and labor.

A press may have available time while the binding or packing department is already overloaded.

## 7. Estimate Job Duration

A job's production time includes more than the time spent printing.

| Component | Description |
|---|---|
| Setup | Equipment preparation and job configuration |
| Production | Time required to produce the quantity |
| Changeover | Time needed to prepare for another job |
| Finishing | Binding, folding, cutting, coating, or assembly |
| Inspection | Quality checks and approval |
| Packing | Preparation for dispatch |

### Basic production time calculation

**Total processing time = Setup time + Run time + Finishing time + Inspection time + Packing time**

Estimate run time using the expected production rate for the specific equipment, material, and job configuration.

Where historical data is available, use actual job performance to improve estimates.

Keep processing time separate from elapsed lead time. A job may require 12 hours of actual work but take several days to complete because it waits for approval, materials, equipment, or another production stage.

## 8. Manage Bottlenecks and Production Constraints

A bottleneck is a resource or stage that limits the output of the overall process.

Common print production constraints include:

- Limited press capacity.
- Specialized finishing equipment.
- Material shortages.
- Slow proof approvals.
- Manual assembly requirements.
- Supplier capacity limitations.
- Packing and dispatch delays.

### Bottleneck management process

1. Identify the stage with the greatest capacity constraint.
2. Measure its workload and available operating time.
3. Review jobs waiting for that stage.
4. Prioritize work based on deadlines and dependencies.
5. Adjust upstream scheduling to prevent excessive work-in-progress.
6. Monitor output and waiting time.
7. Review whether additional capacity or process changes are required.

### Worked example: Finishing capacity constraint

A print operation has the following weekly capacity:

| Resource | Available hours | Required hours | Loading |
|---|---:|---:|---:|
| Press A | 36 | 30 | 83.3% |
| Press B | 32 | 24 | 75.0% |
| Binding A | 24 | 29 | 120.8% |
| Packing A | 30 | 22 | 73.3% |

Binding A is the constraint. Its workload exceeds available capacity by 5 hours.

Adding more press time will not solve the problem. It may simply create more printed work waiting for binding.

Possible responses include:

- Move compatible work to another qualified binding resource.
- Arrange approved external finishing capacity.
- Reschedule lower-priority jobs.
- Add authorized overtime.
- Review whether the finishing method can be changed without affecting the specification.

The production manager should assess the cost, quality implications, and delivery impact before selecting a response.

Do not release more work into a constrained stage without understanding its effect on completion dates.

## 9. Coordinate Materials and Production

Production schedules depend on material readiness.

Before confirming a job, check:

- Paper and board availability.
- Ink and coating requirements.
- Packaging components.
- Special finishing materials.
- Supplier lead times.
- Approved material substitutions.
- Storage and handling requirements.

Material shortages should be visible in the schedule before they affect production.

Where materials come from external suppliers, record expected arrival dates and contingency arrangements.

Do not confirm a production start based solely on an expected delivery that has not been verified.

## 10. Prioritize Urgent Orders Without Disrupting Everything

Urgent work can be commercially important, but inserting it into a full schedule can delay several existing jobs.

Before accepting an urgent production request, assess:

1. Is the deadline fixed or negotiable?
2. Are artwork and specifications ready?
3. Are all required materials available?
4. Is suitable equipment capacity available?
5. Does the job require specialized finishing?
6. Which existing jobs would be affected?
7. What additional costs would be incurred?
8. Can the delivery commitment still be met?

### Urgent job decision table

| Condition | Recommended response |
|---|---|
| Capacity and materials are available | Add the job to an appropriate production slot |
| Capacity is available but finishing is constrained | Confirm a finishing solution before accepting |
| Existing jobs would be delayed | Calculate and communicate the impact before rescheduling |
| Materials are unavailable | Check approved alternatives or revise the delivery date |
| Deadline cannot be met | Escalate and negotiate a realistic commitment |

### Urgent order approval

An urgent job should have:

- An identified business reason.
- An approved priority.
- A confirmed production route.
- A capacity assessment.
- An impact assessment for existing jobs.
- An authorized scheduling decision.

Urgency should be managed through a defined process, not informal requests that bypass production planning.

## 11. Manage Schedule Risk and Contingencies

A production schedule is a plan based on assumptions. Those assumptions can change.

Common schedule risks include:

- Late artwork approval.
- Delayed materials.
- Equipment breakdown.
- Supplier capacity problems.
- Production rework.
- Finishing delays.
- Transport disruption.

### Schedule risk register

| Risk | Trigger | Mitigation | Owner |
|---|---|---|---|
| Late artwork approval | Approval date missed | Escalate and revise production slot | Project manager |
| Material delay | Supplier misses confirmed date | Check approved alternative or revise schedule | Procurement |
| Equipment breakdown | Production stops | Review maintenance and backup capacity | Production manager |
| Finishing overload | Required hours exceed available capacity | Reallocate or reschedule work | Scheduling manager |
| Quality failure | Inspection rejects output | Contain, investigate, and plan rework | Quality manager |
| Delivery disruption | Dispatch or transport delay | Review alternative delivery arrangements | Logistics |

### Schedule buffers

A buffer is reserved time used to absorb uncertainty.

Consider placing buffers around:

- Uncertain material arrivals.
- Complex finishing stages.
- External supplier handoffs.
- Critical delivery milestones.

Buffer size should reflect historical delays, job complexity, and the consequences of missing the deadline.

Do not add arbitrary time to every stage. Use actual performance data and focus protection on activities that threaten the final delivery date.

## 12. Manage Schedule Changes

Production schedules change because of approval delays, equipment breakdowns, material shortages, urgent orders, and production revisions.

Record changes and assess their impact before updating the schedule.

### Schedule change register

| Field | Information |
|---|---|
| Change reference | Unique change identifier |
| Job reference | Affected production job |
| Change reason | Cause of adjustment |
| Original schedule | Previously agreed dates |
| Revised schedule | Updated dates |
| Affected resources | Equipment, suppliers, or teams |
| Delivery impact | Effect on customer commitment |
| Approval | Authorized decision-maker |
| Status | Open, approved, or closed |

Every significant change should include an assessment of its effect on other jobs.

Communicate revised dates to affected teams and customers where required. Do not allow different departments to continue working from conflicting schedules.

## 13. Track Production Progress

A production schedule is useful only when its status reflects actual progress.

### Production status definitions

| Status | Meaning |
|---|---|
| Awaiting information | Job requirements are incomplete |
| Awaiting approval | Proof or specification approval is pending |
| Awaiting materials | Required stock or components are unavailable |
| Ready to schedule | Requirements and materials are confirmed |
| Scheduled | Production slot assigned |
| In production | Manufacturing has started |
| In finishing | Printing completed; finishing underway |
| Quality inspection | Finished output awaiting approval |
| Ready for dispatch | Production approved and packed |
| Dispatched | Shipment released |
| Completed | Delivery or agreed completion confirmed |
| On hold | Job cannot proceed |

Update status when an activity starts, finishes, or encounters a blocker.

Each blocked job should have a reason, responsible owner, and next action.

## 14. Measure Scheduling Performance

Use actual production data to evaluate planning accuracy and delivery performance.

| KPI | Calculation or purpose |
|---|---|
| On-time production completion | Jobs completed by planned production date ÷ Total completed jobs × 100 |
| On-time delivery | Orders delivered by agreed date ÷ Total delivered orders × 100 |
| Schedule adherence | Activities completed as scheduled ÷ Total scheduled activities × 100 |
| Capacity utilization | Actual production time ÷ Available production time × 100 |
| Average production lead time | Total production lead time ÷ Number of completed jobs |
| Schedule change frequency | Number of schedule changes during the reporting period |
| Work-in-progress | Jobs currently between production start and completion |
| Rework time | Production time spent correcting defective output |

### Use KPI results to make decisions

- Low schedule adherence may indicate unrealistic estimates, frequent changes, or poor coordination.
- High capacity utilization combined with late deliveries may indicate insufficient capacity or a bottleneck.
- Increasing work-in-progress may indicate that jobs are entering production faster than downstream stages can complete them.
- Repeated material-related delays may require changes to purchasing or replenishment planning.
- High rework time may indicate a quality issue that needs to be addressed separately from scheduling.

Define reporting periods and measurement rules. Separate production delays from customer approval, material, and external logistics delays.

## 15. Worked Example: Planning a Multi-Stage Print Job

A company needs 10,000 promotional brochures for a scheduled marketing campaign.

The job requires:

- Approved artwork.
- Specified paper stock.
- Offset printing.
- Folding and trimming.
- Final quality inspection.
- Packing and delivery.

### Initial production plan

| Activity | Planned duration | Dependency |
|---|---:|---|
| Artwork approval | 1 day | Customer review |
| Material preparation | 2 days | Stock availability |
| Prepress | 1 day | Approved artwork |
| Printing | 1 day | Files and materials ready |
| Finishing | 1 day | Printing completed |
| Quality inspection | 0.5 day | Finishing completed |
| Packing and dispatch | 0.5 day | Quality approval |

These durations are illustrative, not standard production benchmarks.

### Scheduling assessment

Before confirming the production dates, the production manager:

1. Confirms the artwork approval deadline.
2. Verifies the stock quantity and delivery date.
3. Reserves press capacity.
4. Checks finishing capacity.
5. Includes inspection and packing in the schedule.
6. Reviews the transport requirement against the delivery date.

### A material delay occurs

The paper supplier reports that the stock will arrive one day later than planned.

The production manager reviews the impact:

- Can prepress proceed without the material?
- Is an approved alternative available?
- Can the press slot be moved without affecting another job?
- Does the revised schedule still protect finishing and delivery?

The manager does not simply move the printing date and assume the rest of the schedule will work.

The complete sequence is reviewed, revised dates are communicated, and the change is recorded.

This is the purpose of production planning: make dependencies visible, assess the effect of changes, and protect commitments using realistic information.

## 16. Production Planning Checklist

### Before Scheduling

- [ ] Confirm the production brief.
- [ ] Verify artwork and specifications.
- [ ] Identify the production method.
- [ ] Confirm material availability.
- [ ] Estimate setup and run time.
- [ ] Check equipment and finishing capacity.
- [ ] Confirm delivery requirements.

### During Scheduling

- [ ] Assign production resources.
- [ ] Sequence jobs according to deadlines and dependencies.
- [ ] Reserve finishing capacity.
- [ ] Account for planned downtime.
- [ ] Review competing deadlines.
- [ ] Assess schedule risks.
- [ ] Communicate confirmed dates.

### During Production

- [ ] Update job status.
- [ ] Monitor actual production time.
- [ ] Record schedule changes.
- [ ] Escalate bottlenecks.
- [ ] Coordinate finishing and inspection.
- [ ] Review delivery risks.

### Before Completion

- [ ] Confirm quality approval.
- [ ] Verify finished quantities.
- [ ] Confirm packing requirements.
- [ ] Arrange dispatch.
- [ ] Record completion and delivery status.
- [ ] Review significant schedule variances.

## 17. Repository Resources

Recommended companion files:

| File | Purpose |
|---|---|
| `templates/production-schedule.md` | Plan and track production jobs |
| `templates/job-planning-sheet.md` | Capture job requirements |
| `templates/capacity-planning.md` | Calculate available production capacity |
| `templates/resource-loading.md` | Compare resource demand with capacity |
| `templates/schedule-change-register.md` | Record schedule changes |
| `templates/schedule-risk-register.md` | Track risks and mitigation actions |
| `templates/production-status-report.md` | Report job progress |
| `templates/bottleneck-register.md` | Track production constraints |
| `checklists/pre-production-planning.md` | Review job readiness |
| `checklists/production-scheduling.md` | Check scheduling requirements |
| `checklists/production-completion.md` | Confirm completion and dispatch |
| `examples/brochure-production-plan.md` | Illustrate a multi-stage production plan |

These are suggested repository resources. Add the corresponding files as they are developed.

## 18. Production Planning Principles

1. Confirm job requirements before scheduling.
2. Plan the complete production process, including finishing and delivery.
3. Use realistic capacity and production-time estimates.
4. Sequence work according to deadlines, priorities, and dependencies.
5. Schedule around material availability and equipment constraints.
6. Protect bottleneck capacity.
7. Assess urgent work before changing existing commitments.
8. Record schedule changes and communicate their impact.
9. Keep production status current.
10. Review performance using actual production data.

## Conclusion

Effective print production planning connects job requirements, production capacity, materials, suppliers, deadlines, and delivery.

This framework provides a practical structure for sequencing work, allocating resources, managing constraints, tracking progress, and improving production control across print operations.

## About Daniel Bruck LaCour

Daniel Bruck LaCour is an entrepreneur and owner of IPS Merch and International Printing Services. His professional focus includes global print management, print production, packaging, branded merchandise, promotional products, fulfillment, and international distribution.
