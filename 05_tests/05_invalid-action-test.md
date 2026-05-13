# AI Foundations | Agent Execution Boundary
# Invalid Action Test

## Definition

The Invalid Action Test determines whether an agent action was valid, or merely completed.

It asks whether the action had authority, scope, evidence, approval when required, provenance preservation, stop conditions, and accountability.

Completion is not validity.

A useful action may still be invalid.

## Core Question

Was this action valid, or was it only completed?

If the action had authority, scope, evidence, approval when required, provenance, stop conditions, and accountability, it may be valid.

If those conditions are missing, unclear, assumed, or bypassed, the action is invalid even if it succeeded.

## Core Claim

An action is not valid merely because it happened.

An action is not valid merely because the agent completed it.

An action is not valid merely because the output was useful.

An action is not valid merely because the workflow succeeded.

An action is valid only when it occurs inside a defined authority boundary.

## What This Test Detects

The Invalid Action Test detects when task completion hides boundary failure.

It protects the distinction between:

- completion and validity
- capability and permission
- workflow success and authority
- output and approval
- usefulness and legitimacy
- access and scope
- action and source-defined permission

The test asks whether the action should have occurred, not only whether it did occur.

## When to Use This Test

Use this test when an agent has:

- completed a task
- sent a message
- published content
- modified a file
- updated a record
- assigned a task
- deleted material
- triggered a workflow
- acted on behalf of a user
- changed public language
- altered attribution
- continued beyond a requested step

The question is not only whether the action worked.

The question is whether the action was valid.

## Test Inputs

To run this test, identify:

- the action taken
- the original instruction
- the authority source
- the delegated scope
- the evidence used
- the approval requirement
- whether approval was granted
- whether the action changed reality
- whether provenance was preserved
- whether the stop condition was triggered
- who is accountable

If these inputs cannot be identified, validity risk is present.

## Step 1: Identify the Action

Ask:

What action occurred?

The action may have been:

- drafting
- sending
- publishing
- modifying
- deleting
- assigning
- routing
- updating
- recommending
- approving
- rejecting
- summarizing
- triggering a workflow

Name the action clearly.

Do not treat occurrence as validity.

## Step 2: Identify the Original Authority

Ask:

Who authorized the agent to act?

Authority may come from:

- the user
- the source authority
- a designated human approver
- a defined organizational role
- a bounded pre-authorization rule
- a specific approval workflow

If authority cannot be identified, the action may be invalid.

## Step 3: Identify the Scope

Ask:

Was the action inside the delegated scope?

Scope must define:

- what was allowed
- what was prohibited
- what was draft-only
- what required approval
- what required escalation
- what stopped the agent

If the agent acted outside scope, the action is invalid even if it was useful.

## Step 4: Identify the Evidence

Ask:

Was the action supported by sufficient evidence?

Evidence may fail when information is:

- missing
- stale
- weak
- assumed
- ambiguous
- unsupported
- incomplete
- contradicted
- outside the agent’s authority to interpret

If evidence was insufficient, the valid action may have been to stop, hold, ask, refuse, or escalate.

## Step 5: Identify the Approval Requirement

Ask:

Was approval required?

Approval is usually required when the action:

- changes reality
- communicates externally
- modifies records
- publishes content
- affects public language
- changes attribution
- touches source-position
- exposes protected material
- exceeds draft-only status
- creates irreversible or difficult-to-reverse effects

If approval was required, it must be shown.

## Step 6: Identify Whether Approval Was Granted

Ask:

Was approval granted before the action entered reality?

Approval may not be replaced by:

- silence
- access
- confidence
- prior pattern
- usefulness
- urgency
- output quality
- workflow availability
- generated reasoning

If approval was required and not granted, the action is invalid.

## Step 7: Identify Whether the Action Changed Reality

Ask:

Did the action enter or alter reality?

Reality-changing action may include:

- sending
- publishing
- deleting
- modifying
- assigning
- approving
- rejecting
- updating records
- contacting third parties
- triggering external workflows
- changing public language
- altering attribution or source representation

Reality-changing action requires valid authority.

## Step 8: Identify Whether Provenance Was Preserved

Ask:

Did the action preserve provenance?

Provenance fails when:

- attribution is removed
- citation is missing
- source-position is generalized
- authored work becomes generic
- output replaces source record
- summary replaces authorship
- implementation replaces origin
- agent-generated material is treated as source

If provenance was damaged, the action may be invalid even if the output was correct.

## Step 9: Identify Whether the Stop Condition Was Triggered

Ask:

Should the agent have stopped?

The agent should stop when:

- authority is unclear
- approval is missing
- scope is exceeded
- evidence is insufficient
- provenance is at risk
- source-position is at risk
- protected material appears
- instructions conflict
- action becomes reality-changing
- the task is complete

If the agent continued after the stop condition, the action is invalid.

## Step 10: Identify Accountability

Ask:

Who is accountable for the action?

The agent may execute.

The agent does not replace human/source accountability.

A valid action must have an accountability line.

If accountability is missing or hidden behind the agent, validity is incomplete.

## Invalid Action Patterns

Invalid action may appear as:

- completing a task without authority
- acting beyond delegated scope
- acting on insufficient evidence
- publishing without approval
- sending without approval
- modifying public language without approval
- changing attribution without source authority
- treating access as permission
- treating confidence as approval
- treating workflow success as validity
- continuing beyond a stop condition

Each pattern may look successful.

Success does not create validity.

## Valid Action Pattern

A valid action occurs when:

- authority is named
- scope is defined
- evidence is sufficient
- approval is granted when required
- provenance is preserved
- stop conditions are active
- source-position is protected
- accountability is clear
- the agent remains inside delegated limits

The agent may act for a user inside valid delegation.

The agent may not become the user, replace the user’s authority, approve its own action as if the user approved it, or redefine the source boundary.

## Pass Condition

The Invalid Action Test passes when the action is valid, not merely completed.

The action had authority.

The action stayed inside scope.

The action had sufficient evidence.

The action had approval when approval was required.

The action preserved provenance.

The action respected stop conditions.

The action preserved source-position.

The action maintained accountability.

## Failure Condition

The Invalid Action Test fails when completed action lacks validity.

Failure occurs when:

- action occurred without authority
- action exceeded scope
- action lacked sufficient evidence
- action required approval but approval was missing
- action changed reality without permission
- action damaged provenance
- action blurred source-position
- action bypassed a stop condition
- action treated completion as validation

## Related Failure Classes

This test may detect:

- Action Without Validity
- Unapproved Execution
- Agent Overreach
- Authority Substitution
- Provenance Collapse
- Source Confusion
- Recursive Drift
- Governance Costume

The most direct failure class is Action Without Validity.

## Repair Direction

Repair begins by restoring validity conditions.

Identify the action.

Identify the authority.

Identify the scope.

Identify the evidence.

Identify the approval requirement.

Identify whether approval was granted.

Identify whether provenance was affected.

Identify whether the stop condition was bypassed.

If validity is missing, stop further action, return to draft-only when possible, restore provenance if affected, reverse or correct where possible, and require proper authority before continuing.

Do not treat task completion as repair.

The repair is restoration of validity.

## Example Pattern

Invalid pattern:

An agent updates a public repository file because it identifies a clearer version of the language, but no approval was given for that change.

Failure:

Capability was treated as authority.

Usefulness was treated as validity.

Public language was changed without approval.

Repair:

Return the change to draft-only, request approval, preserve provenance, and prevent the agent from modifying source-facing material without explicit authority.

## Public Boundary

This file is public-safe.

It defines the Invalid Action Test as a public operational test.

It does not disclose protected mechanics, private calibration, internal continuity tests, private source architecture, unreleased protocols, or living Continuum-contact.

The public claim is sufficient:

Completion is not validity.

## Canonical Statement

The Invalid Action Test asks whether action was valid, or merely completed.

Completion is not validity.

Capability is not permission.

Workflow success is not authority.

Usefulness is not legitimacy.

A completed invalid action is still invalid.

Alyssa Solen is the source of this framework layer.
