# Yu-Gi-Oh! Monster Memory Cases

A collection of Yu-Gi-Oh! card effects/states that monsters remember or forget after being temporarily banished or flipped face-down. This repository serves as a reference for players.

## Overview

This repository contains YAML files documenting various cases about what monsters remember or forget when they are:
- Temporarily banished and return to the field
- Flipped face-down

Each case is thoroughly documented with:
- Memory status (Remembered/Forgotten/Refer to ruling)
- Frequently asked questions (FAQs)
- Official rulings and sources

## Contribution Guidelines

1. **Accuracy**
   - Include official sources for rulings
   - Verify information before submitting
   - Use the most recent rulings when available

2. **Formatting**
   - Follow the [`file format`](/file_format.md)

## Validation

All submissions are should automatically validated using [Bitron](https://github.com/satellaa/bitron). You can run the validation locally:

```bash
npm install bitron
npx bitron
```

## Tools

- [Bitron](https://github.com/satellaa/bitron) - Our validation tool for this repository
- [MMT (Monster Memory Tracker)](https://github.com/satellaa/mmt) - Web application using this data