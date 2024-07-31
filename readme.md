Here is an inline equation: $ E = mc^2 $.

And a display equation:
$`
\frac{d}{dx} \left( \int_{0}^{x} f(u)\,du \right) = f(x)
`$


snippet mk "Math" wA
$${1}$`!p
if t[2] and t[2][0] not in [',', '.', '?', '-', ' ']:
    snip.rv = ' '
else:
    snip.rv = ''
`$2
endsnippet
