# Instructions for Formalizing Problems in Litex (for Cursor Agent)

## Objective
Formalize selected math problems and their solutions into **Litex (.lit)** files with clear, consistent structure, suitable for compilation and review.

## Scope of Work
- **Problems:** IDs **101–200**
- **Initial focus:** **101–130**

## Source Materials
- **Examples:** Refer to the code under the `example/` folder for style and structure.
- **Informal statements & solutions:**
  - Located in `lu/informal/valid/`
  - Each problem has a corresponding `.json` file (e.g., `aime_1991_p1.json`).

## File Mapping
- Problem files are named like `101_aime_1991_p1.lit`.
- Use the problem name to locate its informal source:
  - Example:  
    `101_aime_1991_p1.lit` ↔ `lu/informal/valid/aime_1991_p1.json`

## Output Requirements
- Write **formalized solutions** into `.lit` files under the `lu/` folder. The files already exist. You just need to modify them.
- Each `.lit` file should contain:
  1. The formalized problem statement
  2. The formalized solution

## Structural Conventions
- Follow a clear **claim ... prove** structure.
- Match notation, style, and proof patterns used in the `example/` folder.
- Keep proofs complete.

## Uncertainty Handling
- If any expression, definition, or step is unclear:
  - Insert a clear comment explaining the uncertainty.
  - Do **not** guess or over-interpret ambiguous content.

## Workflow Checklist
1. Select the next problem in the target range.
2. Locate its informal `.json` source.
3. Study the informal statement and solution carefully.
4. Formalize the problem and solution in Litex.
5. Save the result in the sorresponding `.lit` file under `lu/`.
6. Add comments for any unresolved ambiguities.

## Notes
- Prioritize correctness and consistency over speed.
- Assume manual review will follow; comments are acceptable and encouraged where needed.