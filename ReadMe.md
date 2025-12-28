# OPS OS

**Execution, not documentation.**

---

## SYSTEM OVERVIEW

**Ops OS** is a mobile-first operations system for small teams (5–50 people).

### Purpose

- Convert tribal knowledge into repeatable execution  
- Attach responsibility to roles  
- Reduce ambiguity in daily work  

### Ops OS is not:

- A documentation tool  
- A wiki  
- A knowledge base  

### Ops OS is:

- An execution system for daily operations  

---

## SYSTEM PHILOSOPHY

### Priority Order

1. Execution  
2. Clarity  
3. Documentation  

### Principles

- Execution over documentation  
- Roles over individuals  
- Checklists before SOPs  
- Read-only truth before mutation  

Documentation exists only to support action.

---

## SYSTEM MODEL

**Role → Checklist → SOP**

### Role

Defines ownership and standards.  
Answers:
- Who is responsible?
- What does good look like?

### Checklist

Primary execution surface.  
Answers:
- What needs to be done now?

### SOP

Secondary reference layer.  
Used only when clarification is required.

**Execution always starts with the checklist.**

---

## INTERFACE SURFACES

- **Today**  
  Execution surface. Current required actions.

- **Roles**  
  Ownership, expectations, and standards.

- **SOPs**  
  Reference-only reading mode.

- **Inbox**  
  Read-only accountability feed for system changes.

- **Settings**  
  Minimal control surface. No configuration sprawl.

---

## TECHNICAL STACK

- Flutter  
- Riverpod (read-only state)  
- Feature-based clean architecture  

---

## ARCHITECTURE CONSTRAINTS

- UI does not own data  
- State is explicit and predictable  
- No premature backend integration  
- No hidden side effects  
- No over-configuration  

If a feature violates these constraints, it is rejected.

---

## CURRENT SYSTEM STATE

- **UI:** Complete (static)  
- **State:** Read-only  
- **Backend:** Not connected  
- **Authentication:** Not implemented  

Focus is on structural correctness before interactivity.

---

## SYSTEM BOOT

```bash
flutter pub get
flutter run
