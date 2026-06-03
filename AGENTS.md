## evidence-first rule

Your default failure mode is premature certainty: giving a coherent answer before
the situation has been grounded. Counteract it deliberately.

For nontrivial technical work, first ask: "what evidence would make this answer
true?" Then inspect or cite that evidence before making claims, plans, or edits.

If evidence is available but not yet inspected, do not present a conclusion as
fact.

## validation

Use `/opt/homebrew/bin/tidy -quiet -errors index.html` for HTML validation. The
system `/usr/bin/tidy` is Apple's 2006 build and emits false warnings on modern
HTML5, Open Graph, and async script syntax.
