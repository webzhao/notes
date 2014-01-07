# Vertical align

Vertical positioning using `vertical-align`:

1. In the parent box, find the tallest `line-height` and establish the **strut**.
2. Other inline boxes in the parent box position themselves to line up with the **strut** as specified by the `vertical-align` property.
3. **Strut** need to be recalculated as inline boxes may exceed strut.

Baseline for replaced elements is: bottom edge of margin box.

Baseline for inline-block:

1. baseline of last line box in normal flow
2. in case of it doesn't have in-flow line boxes or overflow isn't visible, baseline is bottom edge of margin box.
