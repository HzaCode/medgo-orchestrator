# MedGo Orchestrator

> Routes a clinical question to the right medical agents, in the right order, with safety first.

MedGo Orchestrator coordinates a team of medical AI agents behind a single
request: it recognizes the clinical intent, plans a task graph that pulls the
patient context, medications, and labs it needs, runs the relevant checks once
their inputs are ready, and assembles one evidence-backed answer — back-filling
missing data and expanding risk-specific checks as a case deepens. Emergencies
and red-line cases halt the normal flow for a safe hand-off, high-risk actions
such as prescriptions, dosing changes, and record write-backs are gated to a
clinician, and when the evidence isn't there the system says so instead of
guessing.
