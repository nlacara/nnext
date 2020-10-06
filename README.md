# nnext

This is the nnext package for LaTeX. It is an add-on for the **gb4e** example package used in  linguistics. It implements the `\Next`, `\NNext`, `\Last`, and `\LLast` commands from the **linguex** package or the `\nextx`, `\anextx`, `\lastx`, `\blastx`, and `\bblastx` commands from the **expex** package. The package takes its name from the distinctively named `\NNext` command found in **linguex**.

## Introduction

The popular linguistics example package **linguex** and the less popular (though more powerful) package **expex** allow users to refer to previously or to-be defined examples through mnemonic commands such as `\Next` or `\nextx`. The popular package **gb4e** lacks any such functionality. The goal of this package is to provide this functionality for **gb4e** and related packages so that users that need (or want) to use **gb4e** but are more comfortable with **linguex** or **expex** can still have access to these macros while using **gb4e**. 

This package is currently compatible with the original **gb4e** package as well as the modified version **langsci-gb4e** used by [Language Science Press](https://langsci-press.org/) and with [**gb4e-emulate** by Alan Munn](https://github.com/amunn/gb4e-emulate
) (which reimplements **gb4e**’s functionality with the package **enumitem**).
