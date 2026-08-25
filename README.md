# single-port-continuum-robot-hysterectomy
This repo contains the homework for the medical robotics course.

# Restoring the Vaginal Route: A Single-Port Continuum Robot for Transvaginal Hysterectomy

Homework project for the Medical Robotics course, MSc in Robotics and Artificial Intelligence, Sapienza University of Rome.

## Overview

Vaginal hysterectomy is the recommended approach for benign uterine disease, but its use has dropped below 10-15% worldwide because the narrow, conical vaginal canal prevents rigid instruments from triangulating, causing clashing and poor dexterity. This report proposes a dedicated robotic platform to close that gap, rather than adapting existing abdominal systems to a route they were not designed for.

## Proposed solution

A single-port, tendon-driven continuum robotic system:

- An 18 mm flexible overtube carrying a stereoscopic camera and two guidance channels, inserted through the vaginal orifice
- Two tendon-driven continuum manipulators (7 DOF each, 14 total) that deploy an S-shaped trajectory once past the canal, recovering an internal triangulation angle of about 50 degrees
- Fiber Bragg Grating shape sensing along each manipulator for real-time shape reconstruction and an automatic motion halt on anomalous deflection
- A master-slave control interface at Level 1 autonomy (robot assistance only): the surgeon retains full control over all 14 DOF, with tremor filtering and fulcrum-effect inversion handled in software

## What the report covers

- Clinical need and quantified limitations of current manual and robotic approaches
- System architecture and control interface
- Feasibility analysis, separating problems solvable with mature commercial components from the two that require dedicated research (force interaction control, sterile torque transmission)
- Regulatory pathway (FDA 510(k), EU MDR), reimbursement, key risks and mitigations, and explicit scope limitations

Full report: [Licata_Viola_Vaginalhysterectomy.pdf](./Licata_Viola_Vaginalhysterectomy.pdf)

---
Generative AI tools were used to refine academic English phrasing, support literature screening, and generate the conceptual diagrams, as declared in the report.
