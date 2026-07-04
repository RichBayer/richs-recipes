# Rich's Recipes V2 Roadmap

## Purpose

Transform Rich's Recipes from a collection of recipes into a validated culinary knowledge base. Every cook should improve the documentation, recipes, techniques, and equipment guidance.

## Core Philosophy

BuilderOps for cooking:

- Architecture before implementation.
- Recipes are hypotheses until validated.
- Cook logs are evidence.
- Lessons Learned distill repeatable knowledge.
- Equipment is documented and evaluated.
- Every successful cook improves the next one.

## Target Repository Structure

recipes/
  bbq/
  appetizers/
  sides/
  desserts/
menus/
cook-logs/
  2026/
lessons-learned/
techniques/
equipment/
templates/
docs/

## Metadata Standard

Each recipe should eventually include:

- status (draft, tested, validated)
- validation_count
- last_validated
- equipment
- confidence
- source_cook
- prep_time
- cook_time
- serves

## Document Types

Recipes: current best-known process.

Cook Logs: exactly what happened.

Lessons Learned: distilled improvements across multiple cooks.

Equipment: maintenance history, upgrades, safety issues, calibration, replacement decisions.

Techniques: reusable knowledge such as bark development, wrapping, resting, trimming, knife skills, sauces, fire management.

Menus: complete holiday or event meal plans.

Templates: standardized starting points.

## Validation Workflow

Draft -> Tested -> Validated

Each successful cook increases confidence and validation count.

Recipes should change only when supported by evidence from cook logs.

## Migration Plan

Phase 1
- Create templates.
- Create equipment documentation.
- Create roadmap.

Phase 2
- Add metadata to existing recipes.
- Create techniques documents.
- Finish lessons-learned library.

Phase 3
- Move recipes into the new folder structure.
- Move cook logs into yearly folders.
- Update links.

Phase 4
- Build README and navigation.
- Add master recipe index.
- Add validated recipe list.

## Future Enhancements

- Shopping lists.
- Seasonal planning.
- Family favorites.
- Difficulty ratings.
- Recipe version history.
- QR codes linking printed recipes to cook logs.
- Equipment replacement history.
- Printable menu cards.

## Immediate Next Session

1. Complete repository migration.
2. Build techniques section.
3. Build equipment section.
4. Build top-level README.
5. Review existing recipes for metadata.

This document is the architectural guide for Rich's Recipes V2 and should be updated before major structural changes are made.