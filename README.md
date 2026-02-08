# Simple-Calculator

It will create a simple calculator.

## Plan to build a simple calculator

1. **Define requirements and scope**
   - Support addition, subtraction, multiplication, and division.
   - Decide whether this is CLI-only, web UI, or both.
   - Define error behavior (for example, division by zero and invalid input).

2. **Choose a tech stack and project structure**
   - Pick language/framework (for example, JavaScript with HTML/CSS for web).
   - Create folders for source code, styles, tests, and docs.
   - Add lint/format tooling.

3. **Build the calculation engine first**
   - Implement reusable math functions (`add`, `subtract`, `multiply`, `divide`).
   - Add input parsing and validation helpers.
   - Keep this logic independent from UI so it can be unit tested.

4. **Create the user interface**
   - Add display area for current input and result.
   - Add numeric keys, operation keys, clear/backspace, and equals.
   - Connect button clicks (and optional keyboard input) to calculator logic.

5. **Handle state and interaction flow**
   - Track current operand, previous operand, selected operator, and history.
   - Support chained operations (for example, `2 + 3 * 4` behavior as defined).
   - Reset state correctly after clear or completed expression.

6. **Test core behavior and edge cases**
   - Unit-test math helpers and parser.
   - Add interaction tests for UI behavior.
   - Verify edge cases: multiple decimals, large numbers, divide-by-zero, empty input.

7. **Polish and ship**
   - Improve UX (responsive layout, button states, accessible labels).
   - Add README usage instructions and examples.
   - Prepare deployment (if web app) and create a short backlog for future features (memory keys, scientific mode, history).
