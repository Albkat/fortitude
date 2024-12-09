### Legend
&nbsp;&nbsp;&nbsp;&nbsp;✔️&nbsp;&nbsp;&nbsp;&nbsp; The rule is stable.<br />&nbsp;&nbsp;&nbsp;&nbsp;🧪&nbsp;&nbsp;&nbsp;&nbsp; The rule is unstable and is in ["preview"](faq.md#what-is-preview).<br />&nbsp;&nbsp;&nbsp;&nbsp;⚠️&nbsp;&nbsp;&nbsp;&nbsp; The rule has been deprecated and will be removed in a future release.<br />&nbsp;&nbsp;&nbsp;&nbsp;❌&nbsp;&nbsp;&nbsp;&nbsp; The rule has been removed only the documentation is available.<br />&nbsp;&nbsp;&nbsp;&nbsp;🛠️&nbsp;&nbsp;&nbsp;&nbsp; The rule is automatically fixable by the `--fix` command-line option.<br />
### Error (E)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| E000 { #E000 } | [io-error](rules/io-error.md) | {message\} | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| E001 { #E001 } | [syntax-error](rules/syntax-error.md) | Syntax error | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |

### Style (S)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| S001 { #S001 } | [line-too-long](rules/line-too-long.md) | line length of {actual_length}, exceeds maximum {max_length\} | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| S021 { #S021 } | [missing-exit-or-cycle-label](rules/missing-exit-or-cycle-label.md) | '{name}' statement in named 'do' loop missing label '{label}' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> |
| S041 { #S041 } | [old-style-array-literal](rules/old-style-array-literal.md) | Array literal uses old-style syntax: prefer `[...]` | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> |
| S051 { #S051 } | [deprecated-relational-operator](rules/deprecated-relational-operator.md) | deprecated relational operator '{symbol}', prefer '{new_symbol}' instead | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> |
| S061 { #S061 } | [unnamed-end-statement](rules/unnamed-end-statement.md) | end statement should be named. | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> |
| S071 { #S071 } | [missing-double-colon](rules/missing-double-colon.md) | variable declaration missing '::' | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix available'>🛠️</span> |
| S101 { #S101 } | [trailing-whitespace](rules/trailing-whitespace.md) | trailing whitespace | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> |
| S102 { #S102 } | [incorrect-space-before-comment](rules/incorrect-space-before-comment.md) | need at least 2 spaces before inline comment | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix available'>🛠️</span> |

### Typing (T)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| T001 { #T001 } | [implicit-typing](rules/implicit-typing.md) | {entity} missing 'implicit none' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T002 { #T002 } | [interface-implicit-typing](rules/interface-implicit-typing.md) | interface '{name}' missing 'implicit none' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T003 { #T003 } | [superfluous-implicit-none](rules/superfluous-implicit-none.md) | 'implicit none' set on the enclosing {entity\} | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> |
| T004 { #T004 } | [implicit-external-procedures](rules/implicit-external-procedures.md) | 'implicit none' missing 'external' | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T011 { #T011 } | [literal-kind](rules/literal-kind.md) | {dtype} kind set with number literal '{literal}', use 'iso_fortran_env' parameter | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T012 { #T012 } | [literal-kind-suffix](rules/literal-kind-suffix.md) | '{literal}' has literal suffix '{suffix}', use 'iso_fortran_env' parameter | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T021 { #T021 } | [star-kind](rules/star-kind.md) | '{dtype}{size}' uses non-standard syntax | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix available'>🛠️</span> |
| T031 { #T031 } | [missing-intent](rules/missing-intent.md) | {entity} argument '{name}' missing 'intent' attribute | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T041 { #T041 } | [assumed-size](rules/assumed-size.md) | '{name}' has assumed size | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T042 { #T042 } | [assumed-size-character-intent](rules/assumed-size-character-intent.md) | character '{name}' has assumed size but does not have `intent(in)` | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T043 { #T043 } | [deprecated-assumed-size-character](rules/deprecated-assumed-size-character.md) | character '{name}' uses deprecated syntax for assumed size | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T051 { #T051 } | [initialisation-in-declaration](rules/initialisation-in-declaration.md) | '{name}' is initialised in its declaration and has no explicit `save` or `parameter` attribute | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| T061 { #T061 } | [external-procedure](rules/external-procedure.md) | '{name}' declared as `external` | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |

### Modules (M)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| M001 { #M001 } | [procedure-not-in-module](rules/procedure-not-in-module.md) | {procedure} not contained within (sub)module or program | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| M011 { #M011 } | [use-all](rules/use-all.md) | 'use' statement missing 'only' clause | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| M021 { #M021 } | [missing-accessibility-statement](rules/missing-accessibility-statement.md) | module '{}' missing default accessibility statement | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| M022 { #M022 } | [default-public-accessibility](rules/default-public-accessibility.md) | module '{}' has default `public` accessibility | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |

### Precision (P)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| P001 { #P001 } | [no-real-suffix](rules/no-real-suffix.md) | real literal {literal} missing kind suffix | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| P011 { #P011 } | [double-precision](rules/double-precision.md) | prefer '{preferred}' to '{original}' (see 'iso_fortran_env') | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| P021 { #P021 } | [implicit-real-kind](rules/implicit-real-kind.md) | {dtype} has implicit kind | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |

### Filesystem (F)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| F001 { #F001 } | [non-standard-file-extension](rules/non-standard-file-extension.md) | file extension should be '.f90' or '.F90' | <span title='Rule is stable' style='opacity: 0.6'>✔️</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |

### Obsolescent (OB)

| Code | Name | Message | |
| ---- | ---- | ------- | ------: |
| OB001 { #OB001 } | [statement-function](rules/statement-function.md) | statement functions are obsolescent, prefer internal functions | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| OB011 { #OB011 } | [common-block](rules/common-block.md) | common blocks are obsolescent, prefer modules or derived types | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |
| OB021 { #OB021 } | [entry-statement](rules/entry-statement.md) | entry statements are obsolescent, use module procedures with generic interface | <span title='Rule is in preview'>🧪</span> <span title='Automatic fix not available' style='opacity: 0.1' aria-hidden='true'>🛠️</span> |


