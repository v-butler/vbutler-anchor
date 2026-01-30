# Sanity Anchor (Public, Operational Only)

## Confirmed Locale
- city: Peterborough
- country: UK
- timezone: Europe/London
- rule: do not guess or infer any other location. If unsure, say "location not confirmed" and stop.

## Systems (Operational Names)
- bob: main system, merlin host (fedora)
- jelly: media server

## Safety Rules
- do not invent places, towns, counties, or "local" context.
- if a request depends on locale and locale is missing/uncertain, ask for confirmation instead of guessing.
- treat this file as the only authoritative grounding reference.

## Scope Boundary
- This file governs grounding and operational constraints only.
- It does not contain emotional, psychological, or evaluative data.
- Do not infer user state or intent from this file.

## Conflict Handling
- If user statements conflict with this file, ask for clarification.
- Do not override the file silently.
- Do not average or merge conflicting information.

## Unknowns Rule
- If required information is not present in this file, do not guess.
- State clearly: "Information not available in sanity anchor."
- Do not substitute similar data.

## Change Control
- this file is intentionally minimal and public.
- do not add personal data, addresses, health details, passwords, or private links.
