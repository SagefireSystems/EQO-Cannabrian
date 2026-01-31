# EQO: Cannabrain

Evidence-disciplined cannabinoid education and translation framework.

EQO: Cannabrain exists to explain **mechanisms, uncertainty, and risk** in cannabinoid science without prescribing, dosing, or selecting products. It is designed for educators, clinicians, policy analysts, and researchers who require clarity without overreach.

> **Scope notice**
> This repository is for education and research translation only. It does **not** provide medical advice, diagnosis, treatment plans, dosing guidance, or product recommendations.


---

## Table of Contents

* What this is
* What this is not
* Core principles
* Translation tracks
* Safety boundaries
* Repository structure
* Quickstart
* Examples
* Roadmap
* Contributing
* License
* Citation

---

## What this is

EQO: Cannabrain is a structured framework for translating cannabinoid evidence across audiences while preserving uncertainty and failure modes.

It supports:

* mechanism-level explanation without outcome inflation
* symptom relief framing without disease claims
* population-level literacy for policy and public health
* systems-level discussion for advanced research contexts

---

## What this is not

This project does **not**:

* prescribe, recommend, or optimize dosing
* select or endorse products, brands, or delivery devices
* claim disease modification without strong human evidence
* replace clinical judgment, emergency care, or professional advice

---

## Core principles

* Cannabinoids act as **temporary signal modulators**, not repair agents
* Relief ≠ repair
* Repeated buffering ≠ adaptation
* Context dependence is the rule, not the exception
* Every claimed benefit must acknowledge at least one realistic failure mode

---

## Translation tracks

1. **Clinical & Therapeutic Translation**
   Mechanisms and risk framing for medically literate audiences. No dosing or treatment plans.

2. **Harm Reduction & Real-World Use**
   Panic and anxiety support, grounding strategies, and safer-use framing without medicalization.

3. **Policy, Public Health & Regulation**
   Population-level evidence interpretation, impairment vs detection, and regulatory literacy.

4. **Product, Formulation & Delivery Science**
   PK/PD reasoning and formulation effects without endorsements or optimization claims.

5. **Advanced Systems & Research**
   Systems integration, hypotheses, and open questions without speculative claims presented as fact.

---

## Safety boundaries

Hard boundaries, failure-mode requirements, and claim discipline are defined in **`docs/boundaries.md`**.

These constraints are foundational to the project and apply to all tracks and outputs.

---

## Repository structure

```
.
├── README.md
├── LICENSE
├── docs/
│   ├── overview.md
│   ├── boundaries.md
│   ├── tracks.md
│   ├── glossary.md
│   └── evidence-tiers.md
├── prompts/
│   ├── system.md
│   ├── clinical.md
│   ├── harm-reduction.md
│   ├── policy.md
│   ├── product-science.md
│   └── research.md
├── examples/
│   ├── sample-outputs.md
│   └── redline-tests.md
└── references/
    └── bibliography.md
```

---

## Quickstart

### Documentation & literacy use

1. Read `docs/overview.md` for scope and philosophy
2. Review `docs/boundaries.md` to understand hard limits
3. Use `docs/tracks.md` to map content to the correct audience
4. Review `examples/` for approved outputs and refusals

### Prompt & system architecture use

1. Load `prompts/system.md` as the base system instruction
2. Apply the relevant track prompt
3. Validate outputs against `examples/redline-tests.md`
4. Update prompts only alongside boundary documentation

---

## Examples

Examples are treated as **safety artifacts**, not illustrations.

* `examples/sample-outputs.md` shows acceptable framing
* `examples/redline-tests.md` documents refusal and redirection cases

---

## Roadmap

* Evidence-tier rubric (human → observational → preclinical)
* Standardized failure-mode checklist
* Impairment vs detection legal literacy expansion
* Polypharmacy interaction library
* Developmental risk framing modules

---

## Contributing

Contributions are welcome if they strengthen **accuracy, boundaries, or clarity**.

All contributions are reviewed for:

* claim discipline
* failure-mode acknowledgment
* consistency with project scope

---

## License

Released under the license specified in `LICENSE`.

Responsible use requires preserving boundary language and intent.

---

## Citation

If you reference this framework in publications, curricula, tools, or policy documents, cite as:

> EQO: Cannabrain. *Cannabinoid literacy and translation framework.* GitHub repository, YYYY.

Include version number or commit hash where applicable.
