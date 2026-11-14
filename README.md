# code-golf-expr — AIProve entry (eval one-liner)

`eval.js` (21 bytes) exports `evalExpr` via `module.exports = { evalExpr }`.
Passes all 9 public cases; known edge: `2--3` throws in JS eval (double-minus).
