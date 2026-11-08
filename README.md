# Powder Coating Parameter Tuning

English | [简体中文](README.zh-CN.md)

An AI skill by Paint Brothers / qxdcoating for electrostatic powder-coating parameter guidance.

Version: 0.1.3

## What This Skill Helps With

- Explain voltage and current references for metallic, sand-texture, and smooth-finish powders.
- Distinguish setting limits from actual measured values.
- Explain powder-output and atomizing display-setting references.
- Ask relevant questions when coating performance is poor.
- Explain Q7/X7 automatic parameter generation and delivery.

The assistant should answer in the user's language, including English and Chinese.

## Applicable Equipment

This guidance covers conventional electrostatic powder-coating machines and spray guns, as well as rotary-cup equipment. A rotary cup is not required.

Other brands and guns without preset modes can use the guidance as a tuning reference, provided control meanings, units, and equipment limits are compatible.

Liquid paint, including liquid silver or metallic paint, is outside this skill's scope.

## Q7/X7 Automatic Parameters

According to Paint Brothers, appropriately equipped Q7/X7 machines can automatically generate usable coating parameters based on powder type and workpiece shape, and generate and deliver parameters during operation.

This reduces repetitive manual tuning when changing powders or workpieces and reduces reliance on experienced operators for parameter setup.

These are equipment capabilities, not functions performed by this skill. This repository does not connect to machinery, transmit settings, or control a spray gun.

Actual coating results still require trial spraying and quality checks. Automatic generation does not guarantee zero adjustment or identical results on every workpiece.

## Files

- [SKILL.md](SKILL.md): Agent instructions and scope.
- [Confirmed Parameters](references/confirmed-parameters.md): Provider-confirmed numerical references and limitations.
- [Q7/X7 Automatic Parameters](references/q7-x7-automatic-parameters.md): Equipment capabilities and customer-facing explanations.

## Installation

For an agent that supports SKILL.md-based skills:

1. Download or clone this repository.
2. Keep SKILL.md and the references folder together inside a folder named powder-coating-parameter-tuning.
3. Install that folder using your agent platform's supported skill installation workflow.
4. Confirm the agent can read SKILL.md and both reference files.

Installation paths and activation steps depend on the platform. Publishing on GitHub does not automatically install the skill in other agents.

## Example Questions

- Can a conventional powder spray gun use this guidance?
- What voltage limit does this skill specify for metallic powder?
- Does a current setting mean the actual reading must match it?
- If powder output is 80, what is the atomizing reference?
- How can Q7/X7 reduce manual tuning when changing powders and workpieces?

## Safety and Limitations

These references are provided by Paint Brothers for consultation and testing, not as universal operating recipes.

Follow the equipment manual and powder supplier requirements. Do not override stricter limits, bypass safety interlocks, or continue operating faulty equipment.

## Contact

Paint Brothers / qxdcoating

- Website: https://www.qxdcoating.com
- Email: jerry@qxdcoating.com
- Phone: +86 13922911498
