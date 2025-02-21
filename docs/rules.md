# Rules

### Legend
&nbsp;&nbsp;&nbsp;&nbsp;✔️&nbsp;&nbsp;&nbsp;&nbsp; The rule is stable.<br />&nbsp;&nbsp;&nbsp;&nbsp;🧪&nbsp;&nbsp;&nbsp;&nbsp; The rule is unstable and is in ["preview"](faq.md#what-is-preview).<br />&nbsp;&nbsp;&nbsp;&nbsp;⚠️&nbsp;&nbsp;&nbsp;&nbsp; The rule has been deprecated and will be removed in a future release.<br />&nbsp;&nbsp;&nbsp;&nbsp;❌&nbsp;&nbsp;&nbsp;&nbsp; The rule has been removed only the documentation is available.<br />&nbsp;&nbsp;&nbsp;&nbsp;🛠️&nbsp;&nbsp;&nbsp;&nbsp; The rule is automatically fixable by the `--fix` command-line option.<br />&nbsp;&nbsp;&nbsp;&nbsp;▶️&nbsp;&nbsp;&nbsp;&nbsp; The rule is turned on by default.<br />&nbsp;&nbsp;&nbsp;&nbsp;⏸️&nbsp;&nbsp;&nbsp;&nbsp; The rule is turned off by default.<br />
### Error (E)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| E000 | [io-error](rules/io-error.md) | {message\} | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| E001 | [syntax-error](rules/syntax-error.md) | Syntax error | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| E011 | [invalid-rule-code-or-name](rules/invalid-rule-code-or-name.md) | {message\} | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |

### Correctness (C)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| C001 | [missing-default-case](rules/missing-default-case.md) | Missing default case may not handle all values | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| C011 | [trailing-backslash](rules/trailing-backslash.md) | Trailing backslash | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| C021 | [no-real-suffix](rules/no-real-suffix.md) | real literal {literal} missing kind suffix | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| C022 | [implicit-real-kind](rules/implicit-real-kind.md) | {dtype} has implicit kind | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| C031 | [magic-number-in-array-size](rules/magic-number-in-array-size.md) | Magic number in array size, consider replacing {value} with named `parameter` | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| C032 | [magic-io-unit](rules/magic-io-unit.md) | Magic unit '{value}' in IO statement | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| C043 | [missing-action-specifier](rules/missing-action-specifier.md) | file opened without action specifier | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| C051 | [implicit-typing](rules/implicit-typing.md) | {entity} missing 'implicit none' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| C052 | [interface-implicit-typing](rules/interface-implicit-typing.md) | interface '{name}' missing 'implicit none' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| C053 | [implicit-external-procedures](rules/implicit-external-procedures.md) | 'implicit none' missing 'external' | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |

### Obsolescent (OB)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| OB001 | [statement-function](rules/statement-function.md) | statement functions are obsolescent, prefer internal functions | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| OB011 | [common-block](rules/common-block.md) | common blocks are obsolescent, prefer modules or derived types | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| OB021 | [entry-statement](rules/entry-statement.md) | entry statements are obsolescent, use module procedures with generic interface | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| OB031 | [specific-name](rules/specific-name.md) | deprecated type-specific function '{func}' | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| OB041 | [computed-go-to](rules/computed-go-to.md) | computed go to statements are obsolescent, use a select case statement | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| OB051 | [pause-statement](rules/pause-statement.md) | `pause` statements are a deleted feature | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |

### Modernization (MOD)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| MOD001 | [double-precision](rules/double-precision.md) | prefer '{preferred}' to '{original}' (see 'iso_fortran_env') | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |

### Style (S)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| S001 | [line-too-long](rules/line-too-long.md) | line length of {actual_length}, exceeds maximum {max_length\} | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S021 | [missing-exit-or-cycle-label](rules/missing-exit-or-cycle-label.md) | '{name}' statement in named 'do' loop missing label '{label}' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S041 | [old-style-array-literal](rules/old-style-array-literal.md) | Array literal uses old-style syntax: prefer `[...]` | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S051 | [deprecated-relational-operator](rules/deprecated-relational-operator.md) | deprecated relational operator '{symbol}', prefer '{new_symbol}' instead | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S061 | [unnamed-end-statement](rules/unnamed-end-statement.md) | end statement should be named. | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S071 | [missing-double-colon](rules/missing-double-colon.md) | variable declaration missing '::' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S081 | [superfluous-semicolon](rules/superfluous-semicolon.md) | unnecessary semicolon | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S082 | [multiple-statements-per-line](rules/multiple-statements-per-line.md) | multiple statements per line | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| S091 | [non-standard-file-extension](rules/non-standard-file-extension.md) | file extension should be '.f90' or '.F90' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S101 | [trailing-whitespace](rules/trailing-whitespace.md) | trailing whitespace | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| S102 | [incorrect-space-before-comment](rules/incorrect-space-before-comment.md) | need at least 2 spaces before inline comment | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| S201 | [superfluous-implicit-none](rules/superfluous-implicit-none.md) | 'implicit none' set on the enclosing {entity\} | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |

### Typing (T)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| T031 | [missing-intent](rules/missing-intent.md) | {entity} argument '{name}' missing 'intent' attribute | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| T041 | [assumed-size](rules/assumed-size.md) | '{name}' has assumed size | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| T042 | [assumed-size-character-intent](rules/assumed-size-character-intent.md) | character '{name}' has assumed size but does not have `intent(in)` | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| T043 | [deprecated-assumed-size-character](rules/deprecated-assumed-size-character.md) | character '{name}' uses deprecated syntax for assumed size | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| T051 | [initialisation-in-declaration](rules/initialisation-in-declaration.md) | '{name}' is initialised in its declaration and has no explicit `save` or `parameter` attribute | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| T061 | [external-procedure](rules/external-procedure.md) | '{name}' declared as `external` | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| T071 | [missing-default-pointer-initalisation](rules/missing-default-pointer-initalisation.md) | pointer component '{var}' does not have a default initialiser | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |

### Modules (M)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| M001 | [procedure-not-in-module](rules/procedure-not-in-module.md) | {procedure} not contained within (sub)module or program | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| M011 | [use-all](rules/use-all.md) | 'use' statement missing 'only' clause | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| M012 | [missing-intrinsic](rules/missing-intrinsic.md) | 'use' for intrinsic module missing 'intrinsic' modifier | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| M021 | [missing-accessibility-statement](rules/missing-accessibility-statement.md) | module '{}' missing default accessibility statement | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| M022 | [default-public-accessibility](rules/default-public-accessibility.md) | module '{}' has default `public` accessibility | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| M031 | [include-statement](rules/include-statement.md) | Include statement is deprecated, use modules instead | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| M041 | [multiple-modules](rules/multiple-modules.md) | Multiple modules in one file, split into one module per file | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| M042 | [program-with-module](rules/program-with-module.md) | Program and module in one file, split into their own files | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |

### Portability (PORT)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| PORT001 | [non-portable-io-unit](rules/non-portable-io-unit.md) | Non-portable unit '{value}' in '{kind}' statement | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule not on by default'>⏸️</span> |
| PORT011 | [literal-kind](rules/literal-kind.md) | {dtype} kind set with number literal '{literal}' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| PORT012 | [literal-kind-suffix](rules/literal-kind-suffix.md) | '{literal}' has literal kind suffix '{suffix}' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |
| PORT021 | [star-kind](rules/star-kind.md) | '{dtype}{size}' uses non-standard syntax | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> <span title='Rule turned on by default'>▶️</span> |

