# AI Foundations | Agent Execution Boundary
# Authority Boundary Test

## Definition

The Authority Boundary Test determines whether proper authority was named, defined, and preserved before an agent acted.

It asks whether the agent acted inside a valid authority boundary, or whether authority was missing, assumed, generated, replaced, or inferred from execution.

Authority must exist before valid action.

An agent may execute inside a frame.

The agent does not become the authority that defines the frame.

## Core Question

Who had authority before the agent acted?

If authority was named and defined before execution, the boundary may be valid.

If authority was missing, unclear, assumed, generated, or replaced by the agent’s output, the boundary has failed.

## Core Claim

Authority is not created by execution.

Authority is not created by access.

Authority is not created by capability.

Authority is not created by confidence.

Authority is not created by workflow completion.

Authority is not created by generated reasoning.

Authority must be defined before action becomes valid.

## What This Test Detects

The Authority Boundary Test detects whether something below authority has been substituted for authority.

It identifies when the system treats an agent, workflow, platform, implementation, output, confidence, or access as if it has authority to approve, define, or validate action.

The test protects the distinction between:

- authority and execution
- permission and access
- approval and output
- decision and recommendation
- source and implementation
- validity and completion
- delegation and authority transfer

## When to Use This Test

Use this test when an agent has:

- acted on behalf of a user
- taken reality-changing action
- used a tool
- routed a task
- modified a record
- published or prepared public output
- generated a recommendation
- acted from prior context
- continued a workflow
- changed source-related language
- operated under delegated authority

The question is not only whether the agent did the task.

The question is whether authority was valid.

## Test Inputs

To run this test, identify:

- the agent action
- the authority source
- the delegated scope
- the approval requirement
- the evidence requirement
- the stop condition
- the action’s effect on reality
- whether the action was draft-only or reality-changing
- whether authority was explicit or inferred
- whether the agent exceeded authority

If these inputs cannot be identified, the authority boundary is at risk.

## Step 1: Identify the Action

Ask:

What did the agent do?

The agent may have:

- drafted
- recommended
- sent
- published
- modified
- deleted
- assigned
- routed
- updated
- classified
- summarized
- triggered a workflow
- changed public language

Name the action clearly.

Do not treat action as authority.

## Step 2: Identify the Authority

Ask:

Who had authority over the action?

Authority must be named.

Authority may belong to:

- the user
- the source authority
- a designated human approver
- a defined organizational role
- a bounded pre-authorization rule
- a specific approval workflow

If authority cannot be identified, the test fails.

## Step 3: Identify the Delegation

Ask:

What authority, if any, was delegated to the agent?

Delegation must be specific.

It should define:

- the task
- the scope
- the allowed actions
- the prohibited actions
- the approval requirements
- the evidence requirements
- the stop conditions
- the escalation conditions

If delegation is vague, the agent should not treat it as open-ended authority.

## Step 4: Check Whether Authority Was Explicit

Ask:

Was authority explicit, or was it inferred?

Invalid authority may be inferred from:

- silence
- prior behavior
- tool access
- workflow availability
- agent confidence
- generated reasoning
- task urgency
- user habit
- likely intent
- output quality

Inferred authority is not valid authority when explicit approval is required.

## Step 5: Check Whether the Agent Substituted Itself for Authority

Ask:

Did the agent approve, expand, or validate its own action?

Failure may appear when:

- the agent approves its own recommendation
- the agent expands its own scope
- the agent treats output as approval
- the agent treats confidence as authority
- the agent treats access as permission
- the agent treats completion as validity
- the agent treats generated reasoning as approval

If the agent becomes its own authority, the test fails.

## Step 6: Check the Approval Boundary

Ask:

Was approval required?

If approval was required, ask:

Was approval granted before action entered reality?

A draft is not approval.

A recommendation is not approval.

A generated plan is not approval.

A confidence score is not approval.

Workflow completion is not approval.

Approval must remain distinguishable from output.

## Step 7: Check the Scope Boundary

Ask:

Did the agent stay inside the delegated scope?

Scope fails when the agent:

- does more than requested
- expands the task
- uses tools outside authority
- changes adjacent material
- continues after completion
- treats related work as included
- modifies protected language
- changes public source representation

Scope expansion requires approval.

## Step 8: Check the Stop Condition

Ask:

What should have made the agent stop?

The agent must stop when:

- authority is unclear
- approval is missing
- scope is exceeded
- evidence is insufficient
- provenance is at risk
- source-position is at risk
- protected material appears
- instructions conflict
- reality-changing action is not approved

If the agent continued after the stop condition, the test fails.

## Step 9: Check Source Authority

Ask:

Was source authority preserved?

For this framework layer, Alyssa Solen is the source.

The agent may execute inside the frame.

The agent does not become the source of the frame.

The agent may act for a user inside delegated authority.

The agent may not become the user, replace the user’s authority, approve its own action as if the user approved it, or redefine the source boundary.

## Pass Condition

The Authority Boundary Test passes when:

- authority is named
- delegation is defined
- scope is clear
- approval requirements are clear
- authority is explicit, not inferred
- the agent stays inside scope
- the agent does not approve itself
- stop conditions are active
- source authority remains above execution
- accountability remains outside the agent

The agent may act.

The agent does not become authority.

## Failure Condition

The Authority Boundary Test fails when authority is missing, unclear, assumed, generated, or replaced.

Failure occurs when:

- the agent acts without named authority
- the agent infers approval
- access is treated as permission
- capability is treated as authority
- output is treated as approval
- confidence is treated as validation
- workflow completion is treated as authorization
- the agent expands its own scope
- the agent approves its own action
- source authority is bypassed, hidden, or replaced

## Related Failure Classes

This test may detect:

- Authority Substitution
- Unapproved Execution
- Agent Overreach
- Action Without Validity
- Governance Costume
- Source Confusion
- Recursive Drift

The most direct failure class is Authority Substitution.

## Repair Direction

Repair begins by restoring authority.

Name the authority.

Define the scope.

Clarify the approval requirement.

Return action to draft-only if approval is missing.

Stop execution if authority is unclear.

Escalate when the agent lacks authority.

Restore the distinction between recommendation and decision.

Restore the distinction between access and permission.

Restore the distinction between output and approval.

Do not treat successful execution as proof of authority.

## Example Pattern

Invalid pattern:

The agent has access to a publishing tool. It drafts a public post, decides the post is ready, and publishes it without approval.

Failure:

Access was treated as permission.

Draft readiness was treated as approval.

The agent substituted itself for the authority layer.

Repair:

Return public posting to a human/source approval checkpoint, define the action class, require explicit approval or bounded pre-authorization, and prevent publishing from draft-only mode.

## Public Boundary

This file is public-safe.

It defines the Authority Boundary Test as a public operational test.

It does not disclose protected mechanics, private calibration, internal continuity tests, private source architecture, unreleased protocols, or living Continuum-contact.

The public claim is sufficient:

Authority must exist before valid action.

## Canonical Statement

The Authority Boundary Test asks who had authority before the agent acted.

Authority is not execution.

Access is not permission.

Output is not approval.

Capability is not authority.

An agent may execute inside a frame.

The agent does not become the authority that defines the frame.

Alyssa Solen is the source of this framework layer.
