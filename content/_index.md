---
title: "All My Commits To Prod"
outputs: ["Reveal"]
description: "Presentation about practices"
reveal_hugo:
    custom_theme: "reveal-hugo/themes/robot-lung.css"
    margin: 0.2
    highlight_theme: "color-brewer"
    transition: "slide"
---

# Achieving Delivery Acceleration
### why I do all in Prod

<small>Created by [Alvaro](https://kanekotic.xom) ([@kanekotic](https://twitter.com/kanekotic)) @[Chartboost](https://chartboost.com).
</small>

---

# Am I crazy?!

<img src="/images/crazyvswise.png" width="500"/>

---

{{% section %}}

# Why?

<img src="/images/why.jpg" width="700"/>

---

### Team & Organizational Performance

<img src="/images/accelerate.jpg" width="320"/>

{{% note %}}
- Accelerate a great book that is extract of the state of devops report
- It does not just speak about Technology but also about organization and culture
- Read it
{{% /note %}}

---

### 4 key metrics: 2017

<img src="/images/key_metrics.png" width="550"/>

{{% note %}}
- This are metrics that have help correlate high performance teams
- They are based on trying to measure speed and stability
{{% /note %}}

---

### 4 key metrics: Word of caution

<img src="/images/metrics_caution.png" width="335"/>

{{% note %}}
- Not a one size fit all solution.
- Useful for continuous improvement, No reporting.
- As all metrics they can be abused by management
- The solution and practices are not always the same for all teams
{{% /note %}}

{{% /section %}}

---

# Achieving Speed

<img src="/images/full_speed.jpg" width="700"/>

---

{{% section %}}

# Attitude

<img src="/images/positive_attitude.jpg" width="400"/>

--- 

### You Build it you Run it

Create DevOps Culture. Not a Dev vs Ops.

<img src="/images/run_it.jpg" width="400"/>


🟢 All Metrics

{{% note %}}
- Mention Normally developers are ask for delivery speed, and operations counterpart stability.
- Devops culture is based on collaboration on running everything as a team of developers that at the same time observe operations.
- Ops need to become a tool creator for teams, and not run their operations.
{{% /note %}}

--- 

### Be a Boy Scout

Don't continue the same path if you think something can be done better.

<img src="/images/scout.jpeg" width="300"/>

🟢 All Metrics

{{% note %}}
If you see code that can be done better, or some practices that can help delivery dont shy away because you are currently not doing it, or wait for other to move the ball.
{{% /note %}}

--- 

### Learn to adapt

Not all problems need the same tool.

<img src="/images/buddhist.jpg" width="400"/>

🟢 All Metrics

{{% note %}}
Not all problems are solve the same so find your tools
{{% /note %}}

{{% /section %}}

---

{{% section %}}

# Observability

<img src="/images/no_alarms.png" width="700"/>

--- 

### Alarms

- Be lazy
- Get notified when something happens
- Ex. Datadog + Pager Duty

🟢 MTTR

--- 

### Metrics Dashboards

- Visualization
- Ex. Datadog

🟢 MTTR

--- 

### Metrics Dashboards
[Details] VS [Status]

<img src="/images/dashboards.jpeg" width="1000"/>

🟢 MTTR

{{% note %}}
It is easy to spot where the problem is. Because we don't enter a cognitive overload state.
{{% /note %}}

--- 

### Logs

- To go in depth in issues.
- Do not log everything.
- Ex. Kibana

🟢 MTTR

{{% note %}}
You want to dig into issues logging everything will just cause you a headache trying to find the logs you are really interested on.
{{% /note %}}

{{% /section %}}

---

{{% section %}}

# Deployment

<img src="/images/deploy_prod.jpg" width="300"/>

--- 

### Continuous Integration, Delivery & Deployment

<img src="/images/continuous.png" width="1000" />

🟢 Deployment Frequency
🟢 Lead Time For Changes
🟢 MTTR

---

### Everything as code

<img src="/images/infra_as_code.jpg" width="700"/>

🟢 Lead Time For Changes
🟢 MTTR

---

### Blue/Green Deployment

<img src="/images/blue_green.jpeg" width="1000"/>

🟢 Change Failure Rate

--- 

### Canary Release 

<img src="/images/canary.jpeg" width="1000" />

🟢 Change Failure Rate

--- 

### Feature Toggles

<img src="/images/toggles.jpeg" width="1000" />

🟢 Change Failure Rate
🟢 MTTR
🟢 Lead Time For Changes

---

### Environments

<img src="/images/environments.jpeg" width="1000" />

🟡 Change Failure Rate
🟡 Lead Time For Changes

---

### Single Environment

<img src="/images/single_environment.jpeg" width="500" />

🟢 MTTR
🟢 Lead Time For Changes

{{% /section %}}

---

{{% section %}}

# Testing

<img src="/images/testing.jpg" width="500" />

--- 

### Pyramid

<img src="/images/pyramid.jpeg" width="700" />

🟢 Change Failure Rate

---

### Validate in Production

- Get real behaviors of interactions
- Get real performance

🟢 Change Failure Rate

{{% /section %}}

---

{{% section %}}

# Source Code

<img src="/images/merge_branch.jpg" width="500" />

---

### Git Flow & Trunk Base

<img src="/images/trunk.png" width="700" />

🟢 Deployment Frequency

---

### Versionless: Expand & Contract

<img src="/images/expand_contract.jpeg" width="700" />

🟢 Lead Time for Changes

{{% /section %}}

---

{{% section %}}

# Are you at full speed?

---

<img src="/images/laugh.jpg" width="300" />

 hell no! This will always be a moving target
 
 Practices always change

{{% /section %}}

---

<img src="/images/questions.jpg" width="500" />
