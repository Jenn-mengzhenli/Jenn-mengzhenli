# Feishu Enterprise Lookup Bot (OpenClaw POC)

## Overview

This project explores a Feishu-based workflow for requesting company information lookups and reviewing the results. It uses OpenClaw for the local proof of concept.

## POC evidence

A Feishu conversation shows the OpenClaw bot returning a `[LOCAL-POC]` completion notice for an enterprise lookup task. This confirms that a task-level POC ran through Feishu. The notice alone does not verify every step in the workflow below.

## Documented workflow

The project specification describes a workflow that would:

1. Receive a company name through Feishu.
2. Check the company through Qichacha and Tianyancha in separate sessions.
3. Organize selected registration, shareholder, personnel, litigation, enforcement, and negative-information fields.
4. Compare the two results and flag differences for human review.
5. Prepare a report and retain screenshots of source pages.

These are documented design requirements; they should not be read as confirmation that every step was implemented or validated.

## Scope

This page records the project and its current POC evidence. The implementation source was not located in the local project folders, so this page does not include source code. No account credentials, company lookup results, or Feishu screenshots are published here.
