# KNOTS Language

KNOTS (Knotted Object Text Structure) is a deterministic structural
specification for representing hierarchical data using threads and knots.

KNOTS is NOT a programming language.
It defines structure only.

---

## Core Concepts

- Multiple root threads per file
- Each thread is an independent parent
- Knots form a strict hierarchy
- Each knot has exactly one parent
- Infinite nesting allowed

---

## File Format

- `.knots` — plain text structural format

---

## Repository Layout

- `spec/`     → official language rules
- `docs/`     → explanations & models
- `examples/` → reference usage
- `src/`      → future parser/validator

---

## Status

- Structure rules: Stable
- Syntax rules: Draft

---

## License

MIT License
