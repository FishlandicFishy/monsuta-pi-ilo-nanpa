# monsuta pi ilo nanpa | Program Monster

A working recreation of the **CASIO fx-50FH II** in the browser, based on <https://github.com/throwingogo-hub/fx-50fh-ii>.

**[Open the calculator →](https://fishlandicfishy.github.io/monsuta-pi-ilo-nanpa/)**

The calculator's behaviour was reconstructed from CASIO's published user's
guide for this calculator family, and the key layout was measured from
photographs of the unit.

## "Program Monster"?

The term "Program Monster", translated into toki pona as "monsuta pi ilo nanpa", refers to those who are overly reliant on calculator programs.

## Program Studio

The studio features seven general programs plus five complex-number solvers
(simultaneous, line-circle, a combined one, quadratic and two-curve).

The manual-copy source remains in [programs.md](programs.md).

A matching bilingual, print-ready edition is available as the [curated S5 Program Library PDF](output/pdf/fx-50fh-ii-s5-program-library.pdf).

## Features

The website includes six calculation modes:

| # | Mode | Description |
|---|---|---|
| 1 | **COMP** | Basic computation |
| 2 | **CMPLX** | Complex numbers (*a*+*bi* and *r*∠*θ*) |
| 3 | **BASE** | Base-*n* calculation (dec / hex / bin / oct) |
| 4 | **SD** | Single-variable statistics |
| 5 | **REG** | Paired-variable statistics, seven regression types |
| 6 | **PRGM** | Four program areas sharing 680 bytes |

## Keyboard

The physical keyboard is mapped:
* `Enter` is `EXE`
* `Backspace` is `DEL`
* `Escape` is `AC`
* arrow keys drive `REPLAY`
* `Space` and `Tab` latch `SHIFT` and `ALPHA`

## Known Issues
* Clicking on "Prog" while editing a program does nothing (should show same menu as P-CMD)
* Program commands are VERY wrong; correct order from left to right:
  * ? → : ◢
  * ⇒ = ≠
  * > < ≥ ≤
  * Goto Lbl
  * While WhileEnd
  * Next Break
  * For To Step
  * Else IfEnd
  * If Then
* Text is sometimes cut off
* Some variables are not distinguished from their plaintext variants
* Some variables (or characters) are expressed as two characters, even if they should be one
* Some glyphs do not correspond to the original Casio glyphs
* FMLA should start with "Formula No.?" with `-  -` (with two blanks in the middle)
* Formula names are wrong:
  * `01:QuadEquation`
  * `02:CosineTheorm`
  * (03 is correct)
  * `04:Normal_PD_Px`
  * `05:Normal_PD_Qx`
  * `06:Coulomb'sLaw`
  * `07:ConductResis`
  * `08:Magn_Force`
  * `09:R_T-VoltChng`
  * `10:Voltage_Gain`
  * `11:LRC_S-CirImp`
  * `12:LRC_P-CirImp`
  * `13:ElecOsciFreq`
  * (14 is correct)
  * `15:SimpPend_Cyc`
  * `16:SpngpendCyc`
  * (17 is correct)
  * `18:IdlGasStaEq`
  * `19:CentriForce`
  * `20:Elastic_Enr`
  * (21 is correct)
  * `22:Stadia_Ht`
  * `23:Stadia_Dist`
* Shift `,` should be `;`, not `:`
* SD -> S-VAR notation: first page should be (x with bar), sigma x, sx

## License

This repository is licensed under the [MIT license](LICENSE).

CASIO holds the copyright for all source photographs, and *fx-50FH II*, *SUPER-FX PLUS* and *CASIO* are CASIO's trademarks.

This project is unaffiliated with CASIO Computer Co., Ltd. and the Hong Kong Examinations and Assessment Authority, and is not endorsed by them.
