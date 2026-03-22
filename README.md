<!-- 🚨🚨 DON'T EDIT THIS FILE DIRECTLY. Edit `data/tools.yml` instead. 🚨🚨 -->

 <a href="https://analysis-tools.dev/">
   <img alt="Analysis Tools Website" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/redesign.svg" />
 </a>

This repository lists **static analysis tools** for all programming languages, build tools, config files and more. The focus is on tools which improve code quality such as linters and formatters.
The official website, 🌎 [analysis-tools.dev](analysis-tools.dev/) is based on this repository and adds rankings, user comments, and additional resources like videos for each tool.

[![Website](https://img.shields.io/badge/Website-Online-2B5BAE)](https://analysis-tools.dev)
![CI](https://github.com/correia-jpv/fucking-static-analysis/workflows/CI/badge.svg)
[![Links](https://github.com/correia-jpv/fucking-static-analysis/actions/workflows/links.yml/badge.svg)](https://github.com/correia-jpv/fucking-static-analysis/actions/workflows/links.yml)

## Sponsors

This project would not be possible without the generous support of our sponsors.

<table>
   <tr>
      <td>
         <a href="https://www.pixee.ai/">
            <picture >
               <source width="200px" media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/pixee-light.png">
               <img width="200px" alt="Pixee" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/pixee-dark.png">
            </picture>
         </a>
      </td>
      <td>
         <a href="https://coderabbit.ai">
            <img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/code-rabbit.svg" />
         </a>
      </td>
      <td>
         <a href="https://semgrep.dev/">
            <img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/semgrep.svg" />
         </a>
      </td>
      <td>
         <a href="https://offensive360.com/">
            <img width="200px" src="https://raw.githubusercontent.com/analysis-tools-dev/assets/master/static/sponsors/offensive360.png" />
         </a>
      </td>
   </tr>
</table>

If you also want to support this project, head over to our <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Github sponsors page](https://github.com/sponsors/analysis-tools-dev)).

## Meaning of Symbols:

- :copyright: stands for proprietary software. All other tools are Open Source.
- :information_source: indicates that the community does not recommend to use this tool for new projects anymore. The icon links to the discussion issue.
- :warning: means that this tool was not updated for more than 1 year, or the repo was archived.

Pull requests are very welcome!  
Also check out the sister project, <b><code>&nbsp;&nbsp;1078⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [awesome-dynamic-analysis](https://github.com/mre/awesome-dynamic-analysis)).

## Table of Contents

#### [Programming Languages](#programming-languages-1)


- [ABAP](#abap)
- [Ada](#ada)
- [Assembly](#asm)
- [Awk](#awk)
- [C](#c)
- [C#](#csharp)
- [C++](#cpp)
- [Clojure](#clojure)
- [CoffeeScript](#coffeescript)
- [ColdFusion](#coldfusion)
- [Crystal](#crystal)
- [Dart](#dart)
- [Delphi](#delphi)
- [Dlang](#dlang)
- [Elixir](#elixir)
- [Elm](#elm)
- [Erlang](#erlang)
- [F#](#fsharp)
- [Fortran](#fortran)
- [Go](#go)
- [Groovy](#groovy)
- [Haskell](#haskell)
- [Haxe](#haxe)
- [Java](#java)
- [JavaScript](#javascript)
- [Julia](#julia)
- [Kotlin](#kotlin)
- [Lua](#lua)
- [MATLAB](#matlab)
- [Nim](#nim)
- [Ocaml](#ocaml)
- [PHP](#php)
- [PL/SQL](#plsql)
- [Perl](#perl)
- [Python](#python)
- [R](#r)
- [Rego](#rego)
- [Ruby](#ruby)
- [Rust](#rust)
- [SQL](#sql)
- [Scala](#scala)
- [Shell](#shell)
- [Swift](#swift)
- [Tcl](#tcl)
- [TypeScript](#typescript)
- [Verilog/SystemVerilog](#verilog)
- [Vim Script](#vim-script)
- [WebAssembly](#wasm)

#### [Multiple Languages](#multiple-languages-1)

#### [Other](#other-1)
<details>
 <summary>Show Other</summary>

- [.env](#dotenv)
- [Ansible](#ansible)
- [Archive](#archive)
- [Azure Resource Manager](#arm)
- [Binaries](#binary)
- [Build tools](#buildtool)
- [CSS/SASS/SCSS](#css)
- [Config Files](#configfile)
- [Configuration Management](#configmanagement)
- [Containers](#container)
- [Continuous Integration](#ci)
- [Deno](#deno)
- [Dockerfile](#dockerfile)
- [Embedded](#embedded)
- [Embedded Ruby (a.k.a. ERB, eRuby)](#erb)
- [Gherkin](#gherkin)
- [HTML](#html)
- [JSON](#json)
- [Kubernetes](#kubernetes)
- [LaTeX](#latex)
- [Laravel](#laravel)
- [Makefiles](#make)
- [Markdown](#markdown)
- [Metalinter](#meta)
- [Mobile](#mobile)
- [Nix](#nix)
- [Node.js](#nodejs)
- [Packages](#package)
- [Prometheus](#prometheus)
- [Protocol Buffers](#protobuf)
- [Puppet](#puppet)
- [Rails](#rails)
- [Security/SAST](#security)
- [Smart Contracts](#smart-contracts)
- [Support](#support)
- [Template-Languages](#template)
- [Terraform](#terraform)
- [Translation](#translation)
- [Vue.js](#vue)
- [Writing](#writing)
- [YAML](#yaml)
- [git](#git)
</details>

---

## Programming Languages

<a name="abap" />
<h2>ABAP</h2>


- 🌎 [abaplint](abaplint.org) — Linter for ABAP, written in TypeScript.

- 🌎 [abapOpenChecks](docs.abapopenchecks.org) — Enhances the SAP Code Inspector with new and customizable checks.


<a name="ada" />
<h2>Ada</h2>


- 🌎 [Polyspace for Ada](www.mathworks.com/products/polyspace-ada.html) :copyright: — Provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in source code.

- 🌎 [SPARK](www.adacore.com/about-spark) :copyright: — Static analysis and formal verification toolset for Ada.


<a name="asm" />
<h2>Assembly</h2>


- **STOKE** :warning: — A programming-language agnostic stochastic optimizer for the x86_64 instruction set. It uses random search to explore the extremely high-dimensional space of all possible program transformations.


<a name="awk" />
<h2>Awk</h2>


- 🌎 [gawk --lint](www.gnu.org/software/gawk/manual/html_node/Options.html) — Warns about constructs that are dubious or nonportable to other awk implementations.


<a name="c" />
<h2>C</h2>


- 🌎 [Astrée](www.absint.com/astree/index.htm) :copyright: — Astrée automatically proves the absence of runtime errors and invalid con­current behavior in C/C++ applications. It is sound for floating-point computations, very fast, and exceptionally precise. The analyzer also checks for MISRA/CERT/CWE/Adaptive Autosar coding rules and supports qualification for ISO 26262, DO-178C level A, and other safety standards. Jenkins and Eclipse plugins are available.

- [CBMC](http://www.cprover.org/cbmc) — Bounded model-checker for C programs, user-defined assertions, standard assertions, several coverage metric analyses.

- 🌎 [clang-tidy](clang.llvm.org/extra/clang-tidy) — Clang-based C++ linter tool with the (limited) ability to fix issues, too.

- <b><code>&nbsp;&nbsp;&nbsp;728⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [clazy](https://github.com/KDE/clazy)) — Qt-oriented static code analyzer based on the Clang framework. clazy is a compiler plugin which allows clang to understand Qt semantics. You get more than 50 Qt related compiler warnings, ranging from unneeded memory allocations to misusage of API, including fix-its for automatic refactoring.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [CMetrics](https://github.com/MetricsGrimoire/CMetrics)) — Measures size and complexity for C files.

- 🌎 [CPAchecker](cpachecker.sosy-lab.org) — A tool for configurable software verification of C programs.  The name CPAchecker was chosen to reflect that the tool is based on the CPA concepts and is used for checking software programs.

- 🌎 [cppcheck](cppcheck.sourceforge.io) — Static analysis of C/C++ code.

- 🌎 [CppDepend](www.cppdepend.com) :copyright: — Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.

- <b><code>&nbsp;&nbsp;1803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [cpplint](https://github.com/cpplint/cpplint)) — Automated C++ checker that follows Google's style guide.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [cqmetrics](https://github.com/dspinellis/cqmetrics)) — Quality metrics for C code.

- 🌎 [CScout](www.spinellis.gr/cscout) — Complexity and quality metrics for C and C preprocessor code.

- **ENRE-cpp** :warning: — ENRE (ENtity Relationship Extractor) is a tool for extraction of code entity dependencies or relationships from source code. ENRE-cpp is a ENtity Relationship Extractor for C/C++ based on @eclipse/CDT. (Under development)

- [ESBMC](http://esbmc.org) — ESBMC is an open source, permissively licensed, context-bounded model checker based on satisfiability modulo theories for the verification of single- and multi-threaded C/C++ programs.

- **flawfinder** :warning: — Finds possible security weaknesses.

- **flint++** :warning: — Cross-platform, zero-dependency port of flint, a lint program for C++ developed and used at Facebook.

- 🌎 [Frama-C](www.frama-c.com) — A sound and extensible static analyzer for C code.

- 🌎 [GCC](gcc.gnu.org/onlinedocs/gcc/Static-Analyzer-Options.html) — The GCC compiler has static analysis capabilities since version 10. This option is only available if GCC was configured with analyzer support enabled.  It can also output its diagnostics to a JSON file in the SARIF format (from v13).

- 🌎 [Goblint](goblint.in.tum.de) — A static analyzer for the analysis of multi-threaded C programs. Its primary focus is the  detection of data races, but it also reports other runtime errors, such as buffer overflows and null-pointer dereferences.

- 🌎 [Helix QAC](www.perforce.com/products/helix-qac) :copyright: — Enterprise-grade static analysis for embedded software. Supports MISRA, CERT, and AUTOSAR coding standards.

- <b><code>&nbsp;&nbsp;3123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;218🍴</code></b> [IKOS](https://github.com/nasa-sw-vnv/ikos)) — A sound static analyzer for C/C++ code based on LLVM.

- [KLEE](http://klee.github.io/) — A dynamic symbolic execution engine built on top of the LLVM compiler infrastructure.  It can auto-generate test cases for programs such that the test cases exercise as much of the program as possible.

- 🌎 [LDRA](ldra.com) :copyright: — A tool suite including static analysis (TBVISION) to various standards including MISRA C & C++, JSF++ AV, CWE, CERT C, CERT C++ & Custom Rules.

- **MATE** :warning: — A suite of tools for interactive program analysis with a focus on hunting for bugs in C and C++ code. MATE unifies application-specific and low-level vulnerability analysis using code property graphs (CPGs), enabling the discovery of highly application-specific vulnerabilities that depend on both implementation details and the high-level semantics of target C/C++ programs.

- 🌎 [PC-lint](pclintplus.com/) :copyright: — Static analysis for C/C++. Runs natively under Windows/Linux/MacOS. Analyzes code for virtually any platform, supporting C11/C18 and C++17.

- 🌎 [Phasar](phasar.org) — A LLVM-based static analysis framework which comes with a taint and type state analysis.

- 🌎 [Polyspace Bug Finder](www.mathworks.com/products/polyspace-bug-finder.html) :copyright: — Identifies run-time errors, concurrency issues, security vulnerabilities, and other defects in C and C++ embedded software.

- 🌎 [Polyspace Code Prover](www.mathworks.com/products/polyspace-code-prover.html) :copyright: — Provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in C and C++ source code.

- 🌎 [scan-build](clang-analyzer.llvm.org/scan-build.html) — Frontend to drive the Clang Static Analyzer built into Clang via a regular build.

- [splint](http://splint.org) — Annotation-assisted static program checker.

- 🌎 [SVF](svf-tools.github.io/SVF) — A static tool that enables scalable and precise interprocedural dependence analysis for C and C++ programs.

- 🌎 [TrustInSoft Analyzer](trust-in-soft.com) :copyright: — Exhaustive detection of coding errors and their associated security vulnerabilities. This encompasses a sound undefined behavior detection (buffer overflows, out-of-bounds array accesses, null-pointer dereferences, use-after-free, divide-by-zeros, uninitialized memory accesses, signed overflows, invalid pointer arithmetic, etc.), data flow and control flow verification as well as full functional verification of formal specifications. All versions of C up to C18 and C++ up to C++20 are supported. TrustInSoft Analyzer will acquire ISO 26262 qualification in Q2'2023 (TCL3). A MISRA C checker is also bundled.

- **vera++** :warning: — Vera++ is a programmable tool for verification, analysis and transformation of C++ source code.


<a name="csharp" />
<h2>C#</h2>


- [.NET Analyzers](https://github.com/DotNetAnalyzers) — An organization for the development of analyzers (diagnostics and code fixes) using the .NET Compiler Platform.

- <b><code>&nbsp;&nbsp;1229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [ArchUnitNET](https://github.com/TNG/ArchUnitNET)) — A C# architecture test library to specify and assert architecture rules in C# for automated testing.

- 🌎 [code-cracker](code-cracker.github.io) — An analyzer library for C# and VB that uses Roslyn to produce refactorings, code analysis, and other niceties.

- **CSharpEssentials** :warning: — C# Essentials is a collection of Roslyn diagnostic analyzers, code fixes and refactorings that make it easy to work with C# 6 language features.

- [Designite](http://www.designite-tools.com) :copyright: — Designite supports detection of various architecture, design, and implementation smells, computation of various code quality metrics, and trend analysis.

- 🌎 [Gendarme](www.mono-project.com/docs/tools+libraries/tools/gendarme) — Gendarme inspects programs and libraries that contain code in ECMA CIL format (Mono and .NET).

- **Infer#** :warning: — InferSharp (also referred to as Infer#) is an interprocedural and  scalable static code analyzer for C#. Via the capabilities of Facebook's Infer,  this tool detects null pointer dereferences and resource leaks.

- <b><code>&nbsp;&nbsp;1101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Meziantou.Analyzer](https://github.com/meziantou/Meziantou.Analyzer)) — A Roslyn analyzer to enforce some good practices in C# in terms of design, usage, security, performance, and style.

- [NDepend](http://www.ndepend.com) :copyright: — Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.

- 🌎 [Puma Scan](pumasecurity.io) — Puma Scan provides real time secure code analysis for common vulnerabilities (XSS, SQLi, CSRF, LDAPi, crypto, deserialization, etc.) as development teams write code in Visual Studio.

- <b><code>&nbsp;&nbsp;3394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [Roslynator](https://github.com/JosefPihrt/Roslynator)) — A collection of 190+ analyzers and 190+ refactorings for C#, powered by Roslyn.

- <b><code>&nbsp;&nbsp;&nbsp;897⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [SonarAnalyzer.CSharp](https://github.com/SonarSource/sonar-dotnet)) — These Roslyn analyzers allow you to produce Clean Code that is safe, reliable, and maintainable by helping you find and correct bugs, vulnerabilities, and code smells in your codebase.

- **VSDiagnostics** :warning: — A collection of static analyzers based on Roslyn that integrates with VS.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Wintellect.Analyzers](https://github.com/Wintellect/Wintellect.Analyzers)) — .NET Compiler Platform ("Roslyn") diagnostic analyzers and code fixes.


<a name="cpp" />
<h2>C++</h2>


- 🌎 [Astrée](www.absint.com/astree/index.htm) :copyright: — Astrée automatically proves the absence of runtime errors and invalid con­current behavior in C/C++ applications. It is sound for floating-point computations, very fast, and exceptionally precise. The analyzer also checks for MISRA/CERT/CWE/Adaptive Autosar coding rules and supports qualification for ISO 26262, DO-178C level A, and other safety standards. Jenkins and Eclipse plugins are available.

- [CBMC](http://www.cprover.org/cbmc) — Bounded model-checker for C programs, user-defined assertions, standard assertions, several coverage metric analyses.

- 🌎 [clang-tidy](clang.llvm.org/extra/clang-tidy) — Clang-based C++ linter tool with the (limited) ability to fix issues, too.

- <b><code>&nbsp;&nbsp;&nbsp;728⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;98🍴</code></b> [clazy](https://github.com/KDE/clazy)) — Qt-oriented static code analyzer based on the Clang framework. clazy is a compiler plugin which allows clang to understand Qt semantics. You get more than 50 Qt related compiler warnings, ranging from unneeded memory allocations to misusage of API, including fix-its for automatic refactoring.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [CMetrics](https://github.com/MetricsGrimoire/CMetrics)) — Measures size and complexity for C files.

- 🌎 [cppcheck](cppcheck.sourceforge.io) — Static analysis of C/C++ code.

- 🌎 [CppDepend](www.cppdepend.com) :copyright: — Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.

- <b><code>&nbsp;&nbsp;1803⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [cpplint](https://github.com/cpplint/cpplint)) — Automated C++ checker that follows Google's style guide.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [cqmetrics](https://github.com/dspinellis/cqmetrics)) — Quality metrics for C code.

- 🌎 [CScout](www.spinellis.gr/cscout) — Complexity and quality metrics for C and C preprocessor code.

- **ENRE-cpp** :warning: — ENRE (ENtity Relationship Extractor) is a tool for extraction of code entity dependencies or relationships from source code. ENRE-cpp is a ENtity Relationship Extractor for C/C++ based on @eclipse/CDT. (Under development)

- [ESBMC](http://esbmc.org) — ESBMC is an open source, permissively licensed, context-bounded model checker based on satisfiability modulo theories for the verification of single- and multi-threaded C/C++ programs.

- **flawfinder** :warning: — Finds possible security weaknesses.

- **flint++** :warning: — Cross-platform, zero-dependency port of flint, a lint program for C++ developed and used at Facebook.

- 🌎 [GCC](gcc.gnu.org/onlinedocs/gcc/Static-Analyzer-Options.html) — The GCC compiler has static analysis capabilities since version 10. This option is only available if GCC was configured with analyzer support enabled.  It can also output its diagnostics to a JSON file in the SARIF format (from v13).

- 🌎 [Helix QAC](www.perforce.com/products/helix-qac) :copyright: — Enterprise-grade static analysis for embedded software. Supports MISRA, CERT, and AUTOSAR coding standards.

- <b><code>&nbsp;&nbsp;3123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;218🍴</code></b> [IKOS](https://github.com/nasa-sw-vnv/ikos)) — A sound static analyzer for C/C++ code based on LLVM.

- [KLEE](http://klee.github.io/) — A dynamic symbolic execution engine built on top of the LLVM compiler infrastructure.  It can auto-generate test cases for programs such that the test cases exercise as much of the program as possible.

- 🌎 [LDRA](ldra.com) :copyright: — A tool suite including static analysis (TBVISION) to various standards including MISRA C & C++, JSF++ AV, CWE, CERT C, CERT C++ & Custom Rules.

- **MATE** :warning: — A suite of tools for interactive program analysis with a focus on hunting for bugs in C and C++ code. MATE unifies application-specific and low-level vulnerability analysis using code property graphs (CPGs), enabling the discovery of highly application-specific vulnerabilities that depend on both implementation details and the high-level semantics of target C/C++ programs.

- 🌎 [PC-lint](pclintplus.com/) :copyright: — Static analysis for C/C++. Runs natively under Windows/Linux/MacOS. Analyzes code for virtually any platform, supporting C11/C18 and C++17.

- 🌎 [Phasar](phasar.org) — A LLVM-based static analysis framework which comes with a taint and type state analysis.

- 🌎 [Polyspace Bug Finder](www.mathworks.com/products/polyspace-bug-finder.html) :copyright: — Identifies run-time errors, concurrency issues, security vulnerabilities, and other defects in C and C++ embedded software.

- 🌎 [Polyspace Code Prover](www.mathworks.com/products/polyspace-code-prover.html) :copyright: — Provide code verification that proves the absence of overflow, divide-by-zero, out-of-bounds array access, and certain other run-time errors in C and C++ source code.

- 🌎 [scan-build](clang-analyzer.llvm.org/scan-build.html) — Frontend to drive the Clang Static Analyzer built into Clang via a regular build.

- [splint](http://splint.org) — Annotation-assisted static program checker.

- 🌎 [SVF](svf-tools.github.io/SVF) — A static tool that enables scalable and precise interprocedural dependence analysis for C and C++ programs.

- 🌎 [TrustInSoft Analyzer](trust-in-soft.com) :copyright: — Exhaustive detection of coding errors and their associated security vulnerabilities. This encompasses a sound undefined behavior detection (buffer overflows, out-of-bounds array accesses, null-pointer dereferences, use-after-free, divide-by-zeros, uninitialized memory accesses, signed overflows, invalid pointer arithmetic, etc.), data flow and control flow verification as well as full functional verification of formal specifications. All versions of C up to C18 and C++ up to C++20 are supported. TrustInSoft Analyzer will acquire ISO 26262 qualification in Q2'2023 (TCL3). A MISRA C checker is also bundled.

- **vera++** :warning: — Vera++ is a programmable tool for verification, analysis and transformation of C++ source code.


<a name="clojure" />
<h2>Clojure</h2>


- <b><code>&nbsp;&nbsp;1826⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;298🍴</code></b> [clj-kondo](https://github.com/borkdude/clj-kondo)) — A linter for Clojure code that sparks joy. It informs you about potential errors while you are typing.


<a name="coffeescript" />
<h2>CoffeeScript</h2>


- **coffeelint** :warning: — A style checker that helps keep CoffeeScript code clean and consistent.


<a name="coldfusion" />
<h2>ColdFusion</h2>


- 🌎 [Fixinator](fixinator.app) :copyright: — Static security code analysis for ColdFusion or CFML code. Designed to work within a CI pipeline or from the developers terminal.


<a name="crystal" />
<h2>Crystal</h2>


- 🌎 [ameba](crystal-ameba.github.io) — A static code analysis tool for Crystal.

- 🌎 [crystal](crystal-lang.org) — The Crystal compiler has built-in linting functionality.


<a name="dart" />
<h2>Dart</h2>


- **Dart Code Metrics** :warning: — Additional linter for Dart. Reports code metrics, checks for anti-patterns and provides additional rules for Dart analyzer.

- 🌎 [effective_dart](pub.dev/packages/effective_dart) — Linter rules corresponding to the guidelines in Effective Dart

- **lint** :warning: — An opinionated, community-driven set of lint rules for Dart and Flutter projects. Like pedantic but stricter

- **Linter for dart** :warning: — Style linter for Dart.


<a name="delphi" />
<h2>Delphi</h2>


- <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [DelphiLint](https://github.com/integrated-application-development/delphilint)) — A Delphi IDE package providing on-the-fly code analysis and linting, powered by SonarDelphi.

- 🌎 [Fix Insight](www.tmssoftware.com/site/fixinsight.asp) :copyright: — A free IDE Plugin for static code analysis. A _Pro_ edition includes a command line tool for automation purposes.

- 🌎 [Pascal Analyzer](peganza.com/products_pal.html) :copyright: — A static code analysis tool with numerous reports. A free _Lite_ version is available with limited reporting.

- 🌎 [Pascal Expert](peganza.com/products_pex.html) :copyright: — IDE plugin for code analysis. Includes a subset of Pascal Analyzer reporting capabilities and is available for Delphi versions 2007 and later.

- <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [SonarDelphi](https://github.com/integrated-application-development/sonar-delphi)) — Delphi static analyzer for the SonarQube code quality platform.


<a name="dlang" />
<h2>Dlang</h2>


- <b><code>&nbsp;&nbsp;&nbsp;251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83🍴</code></b> [D-scanner](https://github.com/dlang-community/D-Scanner)) — D-Scanner is a tool for analyzing D source code.


<a name="elixir" />
<h2>Elixir</h2>


- <b><code>&nbsp;&nbsp;5147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;439🍴</code></b> [credo](https://github.com/rrrene/credo)) — A static code analysis tool with a focus on code consistency and teaching.

- <b><code>&nbsp;&nbsp;1786⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [dialyxir](https://github.com/jeremyjh/dialyxir)) — Mix tasks to simplify use of Dialyzer in Elixir projects.

- <b><code>&nbsp;&nbsp;1775⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;118🍴</code></b> [sobelow](https://github.com/nccgroup/sobelow)) — Security-focused static analysis for the Phoenix Framework.


<a name="elm" />
<h2>Elm</h2>


- **elm-analyse** :warning: — A tool that allows you to analyse your Elm code, identify deficiencies and apply best practices.

- 🌎 [elm-review](package.elm-lang.org/packages/jfmengels/elm-review/latest) — Analyzes whole Elm projects, with a focus on shareable and custom rules written in Elm that add guarantees the Elm compiler doesn't give you.


<a name="erlang" />
<h2>Erlang</h2>


- 🌎 [dialyzer](www.erlang.org/doc/man/dialyzer.html) — The DIALYZER, a DIscrepancy AnaLYZer for ERlang programs. Dialyzer is a static analysis tool that identifies software discrepancies,  such as definite type errors, code that has become dead or unreachable  because of programming error, and unnecessary tests,  in single Erlang modules or entire (sets of) applications.
Dialyzer starts its analysis from either debug-compiled BEAM bytecode  or from Erlang source code. The file and line number of a discrepancy  is reported along with an indication of what the discrepancy is about.  Dialyzer bases its analysis on the concept of success typings,  which allows for sound warnings (no false positives).

- <b><code>&nbsp;&nbsp;&nbsp;429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [elvis](https://github.com/inaka/elvis)) — Erlang Style Reviewer.

- **Primitive Erlang Security Tool (PEST)** :warning: — A tool to do a basic scan of Erlang source code and report any function calls that may cause Erlang source code to be insecure.


<a name="fsharp" />
<h2>F#</h2>


- 🌎 [fantomas](fsprojects.github.io/fantomas/) — F# source code formatter.

- <b><code>&nbsp;&nbsp;&nbsp;319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [FSharpLint](https://github.com/fsprojects/FSharpLint)) — Lint tool for F#.

- 🌎 [ionide-analyzers](ionide.io/ionide-analyzers/) — A collection of F# analyzers, built with the FSharp.Analyzers.SDK.


<a name="fortran" />
<h2>Fortran</h2>


- 🌎 [Fortitude](fortitude.readthedocs.io) — Fortran linter, inspired by (and built on) Ruff, and based on community best practices. Supports latest Fortran (2023) standard.

- 🌎 [fprettify](pypi.python.org/pypi/fprettify) — Auto-formatter for modern fortran source code, written in Python.
Fprettify is a tool that provides consistent whitespace, indentation, and delimiter alignment in code, including the ability to change letter case and handle preprocessor directives, all while preserving revision history and tested for editor integration.

- **i-Code CNES for Fortran** :warning: — An open source static code analysis tool for Fortran 77, Fortran 90 and Shell.


<a name="go" />
<h2>Go</h2>


- 🌎 [aligncheck](gitlab.com/opennota/check) — Find inefficiently packed structs.

- <b><code>&nbsp;&nbsp;&nbsp;324⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [bodyclose](https://github.com/timakin/bodyclose)) — Checks whether HTTP response body is closed.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [deadcode](https://github.com/tsenart/deadcode)) — Finds unused code.

- **dingo-hunter** :warning: — Static analyser for finding deadlocks in Go.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [dogsled](https://github.com/alexkohler/dogsled)) — Finds assignments/declarations with too many blank identifiers.

- <b><code>&nbsp;&nbsp;&nbsp;366⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [dupl](https://github.com/mibk/dupl)) — Reports potentially duplicated code.

- <b><code>&nbsp;&nbsp;2474⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [errcheck](https://github.com/kisielk/errcheck)) — Check that error return values are used.

- <b><code>&nbsp;&nbsp;&nbsp;381⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [errwrap](https://github.com/fatih/errwrap)) — Wrap and fix Go errors with the new %w verb directive.  This tool analyzes fmt.Errorf() calls and reports calls that contain a verb directive that  is different than the new %w verb directive introduced in Go v1.13.  It's also capable of rewriting calls to use the new %w wrap verb directive.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [flen](https://github.com/lafolle/flen)) — Get info on length of functions in a Go package.

- **Go Meta Linter** :warning: — Concurrently run Go lint tools and normalise their output. Use `golangci-lint` for new projects.

- 🌎 [go tool vet --shadow](golang.org/cmd/vet#hdr-Shadowed_variables) — Reports variables that may have been unintentionally shadowed.

- 🌎 [go vet](golang.org/cmd/vet) — Examines Go source code and reports suspicious.

- **go-consistent** :warning: — Analyzer that helps you to make your Go programs more consistent.

- <b><code>&nbsp;&nbsp;2036⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [go-critic](https://github.com/go-critic/go-critic)) — Go source code linter that maintains checks which are currently not implemented in other linters.

- 🌎 [go/ast](golang.org/pkg/go/ast) — Package ast declares the types used to represent syntax trees for Go packages.

- **goast** :warning: — Go AST (Abstract Syntax Tree) based static analysis tool with Rego.

- **gochecknoglobals** :warning: — Checks that no globals are present.

- <b><code>&nbsp;&nbsp;&nbsp;315⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [goconst](https://github.com/jgautheron/goconst)) — Finds repeated strings that could be replaced by a constant.

- <b><code>&nbsp;&nbsp;1549⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [gocyclo](https://github.com/fzipp/gocyclo)) — Calculate cyclomatic complexities of functions in Go source code.

- 🌎 [gofmt -s](golang.org/cmd/gofmt) — Checks if the code is properly formatted and could not be further simplified.

- <b><code>&nbsp;&nbsp;3890⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;125🍴</code></b> [gofumpt](https://github.com/mvdan/gofumpt)) — Enforce a stricter format than `gofmt`, while being backwards-compatible.  That is, `gofumpt` is happy with a subset of the formats that `gofmt` is happy with.
The tool is a fork of `gofmt` as of Go 1.19, and requires Go 1.18 or later.  It can be used as a drop-in replacement to format your Go code, and running gofmt  after gofumpt should produce no changes.
`gofumpt` will never add rules which disagree with `gofmt` formatting. So we extend `gofmt` rather than compete with it.

- 🌎 [goimports](pkg.go.dev/golang.org/x/tools/cmd/goimports) — Checks missing or unreferenced package imports.

- <b><code>&nbsp;&nbsp;2166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [gokart](https://github.com/praetorian-inc/gokart)) — Golang security analysis with a focus on minimizing false positives. It is capable of tracing the source of variables and function arguments  to determine whether input sources are safe.

- 🌎 [GolangCI-Lint](golangci-lint.run) — Alternative to `Go Meta Linter`: GolangCI-Lint is a linters aggregator.

- <b><code>&nbsp;&nbsp;3969⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;478🍴</code></b> [golint](https://github.com/golang/lint)) — Prints out coding style mistakes in Go source code.

- <b><code>&nbsp;&nbsp;3130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter)) — Concurrently runs many linters and normalises their output to a report.

- <b><code>&nbsp;&nbsp;&nbsp;477⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [goroutine-inspect](https://github.com/linuxerwang/goroutine-inspect)) — An interactive tool to analyze Golang goroutine dump.

- 🌎 [gosec (gas)](securego.io) — Inspects source code for security problems by scanning the Go AST.

- 🌎 [gotype](pkg.go.dev/golang.org/x/tools/cmd/gotype) — Syntactic and semantic analysis similar to the Go compiler.

- 🌎 [govulncheck](go.dev/blog/vuln) — Govulncheck reports known vulnerabilities that affect Go code.  It uses static analysis of source code or a binary's symbol table to narrow down reports to only those that could affect the application.
By default, govulncheck makes requests to the Go vulnerability database at https://vuln.go.dev. Requests to the vulnerability database contain only module paths, not code or other properties of your program.

- <b><code>&nbsp;&nbsp;&nbsp;456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [ineffassign](https://github.com/gordonklaus/ineffassign)) — Detect ineffectual assignments in Go code.

- **interfacer** :warning: — Suggest narrower interfaces that can be used.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [lll](https://github.com/walle/lll)) — Report long lines.

- **maligned** :warning: — Detect structs that would take less memory if their fields were sorted.

- <b><code>&nbsp;&nbsp;1397⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [misspell](https://github.com/client9/misspell)) — Finds commonly misspelled English words.

- <b><code>&nbsp;&nbsp;&nbsp;132⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [nakedret](https://github.com/alexkohler/nakedret)) — Finds naked returns.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [nargs](https://github.com/alexkohler/nargs)) — Finds unused arguments in function declarations.

- 🌎 [OSV-Scanner](osv.dev/) — Vulnerability scanner written in Go which uses the data provided by OSV.dev. Developed by Google to scan dependencies across multiple languages and package managers for known vulnerabilities. Supports container scanning, license scanning, and guided remediation. Works with lockfiles, SBOMs, and container images to identify security issues.

- <b><code>&nbsp;&nbsp;&nbsp;664⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [prealloc](https://github.com/alexkohler/prealloc)) — Finds slice declarations that could potentially be preallocated.

- <b><code>&nbsp;&nbsp;9155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [Reviewdog](https://github.com/haya14busa/reviewdog)) — A tool for posting review comments from any linter in any code hosting service.

- 🌎 [revive](revive.run) — Fast, configurable, extensible, flexible, and beautiful linter for Go. Drop-in replacement of golint.

- **safesql** :warning: — Static analysis tool for Golang that protects against SQL injections.

- **shisho** :warning: — A lightweight static code analyzer designed for developers and security teams. It allows you to analyze and transform source code with an intuitive DSL similar to sed, but for code.

- 🌎 [staticcheck](staticcheck.io) — Go static analysis that specialises in finding bugs, simplifying code and improving performance.

- 🌎 [structcheck](gitlab.com/opennota/check) — Find unused struct fields.

- <b><code>&nbsp;&nbsp;&nbsp;834⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [structslop](https://github.com/orijtech/structslop)) — Static analyzer for Go that recommends struct field rearrangements to provide for maximum space/allocation efficiency

- 🌎 [test](pkg.go.dev/testing) — Show location of test failures from the stdlib testing module.

- **unconvert** :warning: — Detect redundant type conversions.

- <b><code>&nbsp;&nbsp;&nbsp;568⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [unparam](https://github.com/mvdan/unparam)) — Find unused function parameters.

- 🌎 [varcheck](gitlab.com/opennota/check) — Find unused global variables and constants.

- <b><code>&nbsp;&nbsp;&nbsp;346⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [wsl](https://github.com/bombsimon/wsl)) — Enforces empty lines at the right places.


<a name="groovy" />
<h2>Groovy</h2>


- 🌎 [CodeNarc](codenarc.github.io/CodeNarc) — A static analysis tool for Groovy source code, enabling monitoring and enforcement of many coding standards and best practices.


<a name="haskell" />
<h2>Haskell</h2>


- **brittany** :warning: — Haskell source code formatter

- <b><code>&nbsp;&nbsp;1583⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;207🍴</code></b> [HLint](https://github.com/ndmitchell/hlint)) — HLint is a tool for suggesting possible improvements to Haskell code.

- 🌎 [Liquid Haskell](ucsd-progsys.github.io/liquidhaskell-blog/) — Liquid Haskell is a refinement type checker for Haskell programs.

- 🌎 [Stan](kowainik.github.io/projects/stan) — Stan is a command-line tool for analysing Haskell projects and outputting discovered vulnerabilities in a helpful way with possible solutions for detected problems.

- <b><code>&nbsp;&nbsp;&nbsp;184⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Weeder](https://github.com/ocharles/weeder)) — A tool for detecting dead exports or package imports in Haskell code.


<a name="haxe" />
<h2>Haxe</h2>


- 🌎 [Haxe Checkstyle](haxecheckstyle.github.io/docs/haxe-checkstyle/home.html) — A static analysis tool to help developers write Haxe code that adheres to a coding standard.


<a name="java" />
<h2>Java</h2>


- 🌎 [Checker Framework](checkerframework.org) — Pluggable type-checking for Java.  This is not just a bug-finder, but a verification tool that gives a guarantee of correctness.  It comes with 27 pre-built type systems, and it enables users to define their own type system; the manual lists over 30 user-contributed type systems.

- 🌎 [checkstyle](checkstyle.org) — Checking Java source code for adherence to a Code Standard or set of validation rules (best practices).

- <b><code>&nbsp;&nbsp;&nbsp;448⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [ck](https://github.com/mauricioaniche/ck)) — Calculates Chidamber and Kemerer object-oriented metrics by processing the source Java files.

- [ckjm](http://www.spinellis.gr/sw/ckjm) — Calculates Chidamber and Kemerer object-oriented metrics by processing the bytecode of compiled Java files.

- **CogniCrypt** :warning: — Checks Java source and byte code for incorrect uses of cryptographic APIs.

- <b><code>&nbsp;&nbsp;1134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;436🍴</code></b> [Dataflow Framework](https://github.com/typetools/checker-framework)) — An industrial-strength dataflow framework for Java. The Dataflow Framework is used in the Checker Framework, Google’s Error Prone, Uber’s NullAway, Meta’s Nullsafe, and in other contexts. It is distributed with the Checker Framework.

- [DesigniteJava](http://www.designite-tools.com/designitejava) :copyright: — DesigniteJava supports detection of various architecture, design, and implementation smells along with computation of various code quality metrics.

- 🌎 [Diffblue](www.diffblue.com/) :copyright: — Diffblue is a software company that provides AI-powered code analysis and testing solutions for software development teams.
Its technology helps developers automate testing, find bugs, and reduce manual labor in their software development processes. The company's main product, Diffblue Cover, uses AI to generate and run unit tests for Java code, helping to catch errors and improve code quality.

- 🌎 [Doop](plast-lab.github.io/doop-pldi15-tutorial/) — Doop is a declarative framework for static analysis of Java/Android programs, centered on pointer analysis algorithms. Doop provides a large variety of analyses and also the surrounding scaffolding to run an analysis end-to-end (fact generation, processing, statistics, etc.).

- **ENRE-java** :warning: — ENRE (ENtity Relationship Extractor) is a tool for extraction of code entity dependencies or relationships from source code. ENRE-java is a ENtity Relationship Extractor for Java projects based on @Eclipse JDT/parser.

- 🌎 [Error Prone](errorprone.info) — Catch common Java mistakes as compile-time errors.

- [fb-contrib](http://fb-contrib.sourceforge.net) — A plugin for FindBugs with additional bug detectors.

- <b><code>&nbsp;&nbsp;&nbsp;361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [forbidden-apis](https://github.com/policeman-tools/forbidden-apis)) — Detects and forbids invocations of specific method/class/field (like reading from a text stream without a charset). Maven/Gradle/Ant compatible.

- <b><code>&nbsp;&nbsp;6096⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;916🍴</code></b> [google-java-format](https://github.com/google/google-java-format)) — Reformats Java source code to comply with Google Java Style

- **HuntBugs** :warning: — Bytecode static analyzer tool based on Procyon Compiler Tools aimed to supersede FindBugs.

- 🌎 [IntelliJ IDEA](www.jetbrains.com/idea) :copyright: — Comes bundled with a lot of inspections for Java and Kotlin and includes tools for refactoring, formatting and more.

- 🌎 [JArchitect](www.jarchitect.com) :copyright: — Measure, query and visualize your code and avoid unexpected issues, technical debt and complexity.

- 🌎 [JBMC](www.cprover.org/jbmc) — Bounded model-checker for Java (bytecode), verifies user-defined assertions, standard assertions, several coverage metric analyses.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [JLiSA](https://github.com/lisa-analyzer/jlisa)) — An abstract interpretation-based static analyzer for Java build upon the <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [LiSA](https://github.com/lisa-analyzer/lisa)) framekwork.

- 🌎 [Mariana Trench](mariana-tren.ch/) — Our security focused static analysis tool for Android and Java applications. Mariana Trench analyzes Dalvik bytecode and is built to run fast on large codebases (10s of millions of lines of code). It can find vulnerabilities as code changes, before it ever lands in your repository.

- <b><code>&nbsp;&nbsp;4023⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;331🍴</code></b> [NullAway](https://github.com/uber/NullAway)) — Type-based null-pointer checker with low build-time overhead; an [Error Prone](http://errorprone.info/) plugin.

- **OWASP Dependency Check** :warning: — Checks dependencies for known, publicly disclosed, vulnerabilities.

- 🌎 [qulice](www.qulice.com) — Combines a few (pre-configured) static analysis tools (checkstyle, PMD, Findbugs, ...).

- <b><code>&nbsp;&nbsp;&nbsp;522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst)) — Identifies and prioritizes God Classes and Highly Coupled classes in Java codebases you should refactor first.

- 🌎 [Soot](soot-oss.github.io/soot) — A framework for analyzing and transforming Java and Android applications.

- 🌎 [Spoon](spoon.gforge.inria.fr) — Spoon is a metaprogramming library to analyze and transform Java source code (incl Java 9, 10, 11, 12, 13, 14). It parses source files to build a well-designed AST with powerful analysis and transformation API. Can be integrated in Maven and Gradle.

- 🌎 [SpotBugs](spotbugs.github.io) — SpotBugs is FindBugs' successor. A tool for static analysis to look for bugs in Java code.

- **steady** :warning: — Analyses your Java applications for open-source dependencies with known vulnerabilities, using both static analysis and testing to determine code context and usage for greater accuracy.

- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Violations Lib](https://github.com/tomasbjerre/violations-lib)) — Java library for parsing report files from static code analysis. Used by a bunch of Jenkins, Maven and Gradle plugins.


<a name="javascript" />
<h2>JavaScript</h2>


- **aether** :warning: — Lint, analyze, normalize, transform, sandbox, run, step through, and visualize user JavaScript, in node or the browser.

- 🌎 [Closure Compiler](developers.google.com/closure/compiler) — A compiler tool to increase efficiency, reduce size, and provide code warnings in JavaScript files.

- **ClosureLinter** :warning: — Ensures that all of your project's JavaScript code follows the guidelines in the Google JavaScript Style Guide. It can also automatically fix many common errors.

- **complexity-report** :warning: — Software complexity analysis for JavaScript projects.

- 🌎 [DeepScan](deepscan.io) :copyright: — An analyzer for JavaScript which targets runtime errors and quality issues rather than coding conventions.

- **es6-plato** :warning: — Visualize JavaScript (ES6) source complexity.

- <b><code>&nbsp;&nbsp;&nbsp;271⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [escomplex](https://github.com/jared-stilwell/escomplex)) — Software complexity analysis of JavaScript-family abstract syntax trees.

- **Esprima** :warning: — ECMAScript parsing infrastructure for multipurpose analysis.

- 🌎 [flow](flow.org) — A static type checker for JavaScript.

- **hegel** :warning: — A static type checker for JavaScript with a bias on type inference and strong type systems.

- 🌎 [jshint](jshint.com/about) [:information_source:](<https://github.com/correia-jpv/fucking-static-analysis/issues/223>) — Detect errors and potential problems in JavaScript code and enforce your team's coding conventions.

- <b><code>&nbsp;&nbsp;3668⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;474🍴</code></b> [JSLint](https://github.com/douglascrockford/JSLint)) [:information_source:](<https://github.com/correia-jpv/fucking-static-analysis/issues/223>) — The JavaScript Code Quality Tool.

- **JSPrime** :warning: — Static security analysis tool.

- **NodeJSScan** :warning: — A static security code scanner for Node.js applications powered by libsast and semgrep that builds on the njsscan cli tool. It features a UI with various dashboards about an application's security status.

- **plato** :warning: — Visualize JavaScript source complexity.

- <b><code>&nbsp;&nbsp;&nbsp;436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer)) — A static analysis framework for Web Components.

- 🌎 [retire.js](retirejs.github.io/retire.js) — Scanner detecting the use of JavaScript libraries with known vulnerabilities.

- **RSLint** :warning: — A (WIP) JavaScript linter written in Rust designed to be as fast as possible, customizable, and easy to use.

- [standard](http://standardjs.com) — An npm module that checks for Javascript Styleguide issues.

- 🌎 [tern](ternjs.net) — A JavaScript code analyzer for deep, cross-editor language support.

- **TypL** :warning: — With TypL, you just write completely standard JS, and the tool figures out your types via powerful inferencing.

- <b><code>&nbsp;&nbsp;7964⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;305🍴</code></b> [xo](https://github.com/xojs/xo)) — Opinionated but configurable ESLint wrapper with lots of goodies included. Enforces strict and readable code.

- **yardstick** :warning: — Javascript code metrics.


<a name="julia" />
<h2>Julia</h2>


- <b><code>&nbsp;&nbsp;&nbsp;856⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [JET](https://github.com/aviatesk/JET.jl)) — Static type inference system to detect bugs and type instabilities.

- <b><code>&nbsp;&nbsp;&nbsp;159⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [StaticLint](https://github.com/julia-vscode/StaticLint.jl)) — Static Code Analysis for Julia


<a name="kotlin" />
<h2>Kotlin</h2>


- 🌎 [detekt](detekt.github.io/detekt) — Static code analysis for Kotlin code.

- **diktat** :warning: — Strict coding standard for Kotlin and a linter that detects and auto-fixes code smells.

- 🌎 [ktfmt](facebook.github.io/ktfmt/) — A program that reformats Kotlin source code to comply with the common community standard for Kotlin code conventions.
A ktfmt IntelliJ plugin is available from the plugin repository. To install it, go to your IDE's settings and select the Plugins category. Click the Marketplace tab, search for the ktfmt plugin, and click the Install button.

- 🌎 [ktlint](ktlint.github.io) — An anti-bikeshedding Kotlin linter with built-in formatter.


<a name="lua" />
<h2>Lua</h2>


- <b><code>&nbsp;&nbsp;&nbsp;442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [luacheck](https://github.com/lunarmodules/luacheck)) — A tool for linting and static analysis of Lua code.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [lualint](https://github.com/philips/lualint)) — lualint performs luac-based static analysis of global variable usage in Lua source code.

- **Luanalysis** :warning: — An IDE for statically typed Lua development.


<a name="matlab" />
<h2>MATLAB</h2>


- **MISS_HIT** :warning: — MISS_HIT is a free, open-source code quality toolset for MATLAB, Simulink, and Octave. It includes MH Style (style checker and formatter), MH Metrics (complexity metrics), MH Lint (static analysis), MH Trace (requirements traceability), and MH Copyright (copyright management). Designed to work standalone without requiring MATLAB/Octave installation.

- 🌎 [mlint](www.mathworks.com/help/matlab/ref/mlint.html) :copyright: — Check MATLAB code files for possible problems.


<a name="nim" />
<h2>Nim</h2>


- 🌎 [DrNim](nim-lang.org/docs/drnim.html) — DrNim combines the Nim frontend with the Z3 proof engine in order to allow verify / validate software written in Nim.

- **nimfmt** :warning: — Nim code formatter / linter / style checker


<a name="ocaml" />
<h2>Ocaml</h2>


- <b><code>&nbsp;&nbsp;&nbsp;236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Sys](https://github.com/PLSysSec/sys)) — A static/symbolic Tool for finding bugs in (browser) code. It uses the LLVM AST to find bugs like uninitialized memory access.

- <b><code>&nbsp;&nbsp;&nbsp;481⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [VeriFast](https://github.com/verifast/verifast)) — A tool for modular formal verification of correctness properties of single-threaded and multithreaded  C and Java programs annotated with preconditions and postconditions written in separation logic.  To express rich specifications, the programmer can define inductive datatypes,  primitive recursive pure functions over these datatypes, and abstract separation logic predicates.


<a name="php" />
<h2>PHP</h2>


- 🌎 [CakeFuzzer](zigrin.com/tools/cake-fuzzer/) — Web application security testing tool for CakePHP-based web applications. CakeFuzzer employs a predefined set of attacks that are randomly modified before execution. Leveraging its deep understanding of the Cake PHP framework, Cake Fuzzer launches attacks on all potential application entry points.

- <b><code>&nbsp;&nbsp;1379⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [churn-php](https://github.com/bmitch/churn-php)) — Helps discover good candidates for refactoring.

- <b><code>&nbsp;&nbsp;&nbsp;604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [composer-dependency-analyser](https://github.com/shipmonk-rnd/composer-dependency-analyser)) — Fast detection of composer dependency issues.

* 💪 Powerful: Detects unused, shadow and misplaced composer dependencies
* ⚡ Performant: Scans 15 000 files in 2s!
* ⚙️ Configurable: Fine-grained ignores via PHP config
* 🕸️ Lightweight: No composer dependencies
* 🍰 Easy-to-use: No config needed for first try
* ✨ Compatible: PHP >= 7.2


- <b><code>&nbsp;&nbsp;&nbsp;534⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [dephpend](https://github.com/mihaeu/dephpend)) — Dependency analysis tool.

- <b><code>&nbsp;&nbsp;&nbsp;391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [deprecation-detector](https://github.com/sensiolabs-de/deprecation-detector)) — Finds usages of deprecated (Symfony) code.

- <b><code>&nbsp;&nbsp;2909⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [deptrac](https://github.com/sensiolabs-de/deptrac)) — Enforce rules for dependencies between software layers.

- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [DesignPatternDetector](https://github.com/Halleck45/DesignPatternDetector)) — Detection of design patterns in PHP code.

- 🌎 [EasyCodingStandard](www.tomasvotruba.com/blog/2017/05/03/combine-power-of-php-code-sniffer-and-php-cs-fixer-in-3-lines) — Combine <b><code>&nbsp;10789⭐</code></b> <b><code>&nbsp;&nbsp;1457🍴</code></b> [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)) and <b><code>&nbsp;13476⭐</code></b> <b><code>&nbsp;&nbsp;1631🍴</code></b> [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)).

- **Enlightn** :warning: — A static and dynamic analysis tool for Laravel applications that provides recommendations to improve the performance, security and code reliability of Laravel apps. Contains 120 automated checks.

- 🌎 [exakat](www.exakat.io) — An automated code reviewing engine for PHP.

- <b><code>&nbsp;&nbsp;4278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;445🍴</code></b> [GrumPHP](https://github.com/phpro/grumphp)) — Checks code on every commit.

- <b><code>&nbsp;&nbsp;6335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;490🍴</code></b> [larastan](https://github.com/larastan/larastan)) — Adds static analysis to Laravel improving developer productivity and code quality. It is a wrapper around PHPStan.

- 🌎 [mago](mago.carthage.software) — Mago is a complete toolchain for PHP, written in Rust, designed from the ground up for maximum performance.
- ✨ A blazing-fast formatter that automatically formats your code according to PER-CS, ending style debates forever. - 🔎 An intelligent linter that catches stylistic issues, inconsistencies, and code smells before they become problems. - 🔬 A powerful static analyzer that finds type errors and logical bugs in your code without you ever having to run it. - 🛡️ A robust architectural guard that enforces dependency rules and structural conventions.

- **Mondrian** :warning: — A set of static analysis and refactoring tools which use graph theory.

- <b><code>&nbsp;&nbsp;&nbsp;350⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [parallel-lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint)) — This tool checks syntax of PHP files faster than serial check with a fancier output.

- <b><code>&nbsp;&nbsp;&nbsp;380⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Parse](https://github.com/psecio/parse)) — A Static Security Scanner.

- 🌎 [pdepend](pdepend.org) — Calculates software metrics like cyclomatic complexity for PHP code.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [phan](https://github.com/phan/phan/wiki)) — A modern static analyzer from etsy.

- <b><code>&nbsp;&nbsp;1246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [PHP Architecture Tester](https://github.com/carlosas/phpat)) — Easy to use architecture testing tool for PHP.

- <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [PHP Assumptions](https://github.com/rskuipers/php-assumptions)) — Checks for weak assumptions.

- 🌎 [PHP Coding Standards Fixer](cs.symfony.com) — Fixes your code according to standards like PSR-1, PSR-2, and the Symfony standard.

- <b><code>&nbsp;&nbsp;5586⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;295🍴</code></b> [PHP Insights](https://github.com/nunomaduro/phpinsights)) — Instant PHP quality checks from your console. Analysis of code quality and coding style as well as overview of code architecture and its complexity.

- 🌎 [Php Inspections (EA Extended)](plugins.jetbrains.com/plugin/7622-php-inspections-ea-extended-) — A Static Code Analyzer for PHP.

- 🌎 [PHP Refactoring Browser](qafoolabs.github.io/php-refactoring-browser) — Refactoring helper.

- <b><code>&nbsp;&nbsp;&nbsp;434⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker)) — Suggests a next version according to semantic versioning.

- <b><code>&nbsp;17429⭐</code></b> <b><code>&nbsp;&nbsp;1121🍴</code></b> [PHP-Parser](https://github.com/nikic/PHP-Parser)) — A PHP parser written in PHP.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [php-speller](https://github.com/mekras/php-speller)) — PHP spell check library.

- **PHP-Token-Reflection** :warning: — Library emulating the PHP internal reflection.

- **php7cc** :warning: — PHP 7 Compatibility Checker.

- **php7mar** :warning: — Assist developers in porting their code quickly to PHP 7.

- **PHP_CodeSniffer** :warning: — Detects violations of a defined set of coding standards.

- <b><code>&nbsp;&nbsp;&nbsp;884⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [PHPArkitect](https://github.com/phparkitect/arkitect)) — PHPArkitect helps you to keep your PHP codebase coherent and solid, by permitting to add some architectural constraint check to your workflow. You can express the constraint that you want to enforce, in simple and readable PHP code.

- **phpca** :warning: — Finds usage of non-built-in extensions.

- **phpcpd** :warning: — Copy/Paste Detector for PHP code.

- **phpdcd** :warning: — Dead Code Detector (DCD) for PHP code.

- **PhpDependencyAnalysis** :warning: — Builds a dependency graph for a project.

- **PhpDeprecationDetector** :warning: — Analyzer of PHP code to search issues with deprecated functionality in newer interpreter versions.  It finds removed objects (functions, variables, constants and ini-directives),  deprecated functions functionality, and usage of forbidden names or tricks (e.g. reserved identifiers in newer versions).

- **phpdoc-to-typehint** :warning: — Add scalar type hints and return types to existing PHP projects using PHPDoc annotations.

- 🌎 [phpDocumentor](www.phpdoc.org) — Analyzes PHP source code to generate documentation.

- <b><code>&nbsp;&nbsp;2349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [phploc](https://github.com/sebastianbergmann/phploc)) — A tool for quickly measuring the size and analyzing the structure of a PHP project.

- 🌎 [PHPMD](phpmd.org) — Finds possible bugs in your code.

- [PhpMetrics](http://www.phpmetrics.org) — Calculates and visualizes various code quality metrics.

- <b><code>&nbsp;&nbsp;&nbsp;580⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [phpmnd](https://github.com/povils/phpmnd)) — Helps to detect magic numbers.

- 🌎 [PHPQA](edgedesigncz.github.io/phpqa) — A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).

- <b><code>&nbsp;&nbsp;1304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [phpqa - jakzal](https://github.com/jakzal/phpqa)) — Many tools for PHP static analysis in one container.

- <b><code>&nbsp;&nbsp;&nbsp;325⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [phpqa - jmolivas](https://github.com/jmolivas/phpqa)) — PHPQA all-in-one Analyzer CLI tool.

- **phpsa** :warning: — Static analysis tool for PHP.

- 🌎 [PHPStan](phpstan.org) — PHP Static Analysis Tool - discover bugs in your code without running it!

- <b><code>&nbsp;&nbsp;&nbsp;360⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Progpilot](https://github.com/designsecurity/progpilot)) — A static analysis tool for security purposes.

- 🌎 [Psalm](psalm.dev) — Static analysis tool for finding type errors in PHP applications.

- **Qafoo Quality Analyzer** :warning: — Visualizes metrics and source code.

- 🌎 [rector](getrector.org) — Instant Upgrades and Automated Refactoring of any PHP 5.3+ code. It upgrades your code for PHP 7.4, 8.0 and beyond. Rector promises a low false-positive rate because it looks for narrowly defined AST (abstract syntax tree) patterns.  The main use-case are tackling technical debt in your legacy code and removing dead code. Rector provides a set of special rules for Symfony, Doctrine, PHPUnit, and many more.

- <b><code>&nbsp;&nbsp;&nbsp;126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Reflection](https://github.com/phpDocumentor/Reflection)) — Reflection library to do Static Analysis for PHP Projects

- 🌎 [Symfony Insight](insight.symfony.com/) :copyright: — Detect security risks, find bugs and provide actionable metrics for PHP projects.

- <b><code>&nbsp;&nbsp;&nbsp;169⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Tuli](https://github.com/ircmaxell/Tuli)) — A static analysis engine.

- <b><code>&nbsp;&nbsp;&nbsp;118⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [twig-lint](https://github.com/asm89/twig-lint)) — twig-lint is a lint tool for your twig files.

- 🌎 [WAP](securityonline.info/owasp-wap-web-application-protection-project) — Tool to detect and correct input validation vulnerabilities in PHP (4.0 or higher) web applications and predicts false positives by combining static analysis and data mining.


<a name="plsql" />
<h2>PL/SQL</h2>


- 🌎 [ZPA](zpa.felipebz.com) — An open source parser and code analyzer for PL/SQL and Oracle SQL code.


<a name="perl" />
<h2>Perl</h2>


- 🌎 [Perl::Analyzer](technix.github.io/Perl-Analyzer/) — Perl-Analyzer is a set of programs and modules that allow users to analyze and visualize Perl  codebases by providing information about namespaces and their relations, dependencies,  inheritance, and methods implemented, inherited, and redefined in packages,  as well as calls to methods from parent packages via SUPER. 

- 🌎 [Perl::Critic](metacpan.org/pod/Perl::Critic) — Critique Perl source code for best-practices.

- 🌎 [perltidy](perltidy.sourceforge.net/) — Perltidy is a Perl script which indents and reformats Perl scripts to make them easier to read. 
The formatting can be controlled with command line parameters. The default parameter settings approximately follow the suggestions in the Perl Style Guide. 
Besides reformatting scripts, Perltidy can be a great help in tracking down errors with missing or extra braces, parentheses, and square brackets because it is very good at localizing errors.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [zarn](https://github.com/htrgouvea/zarn)) — A lightweight static security analysis tool for modern Perl Apps


<a name="python" />
<h2>Python</h2>


- <b><code>&nbsp;&nbsp;&nbsp;952⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [autoflake](https://github.com/PyCQA/autoflake)) — Autoflake removes unused imports and unused variables from Python code.

- 🌎 [autopep8](pypi.org/project/autopep8/) — A tool that automatically formats Python code to conform to the PEP 8 style guide.
It uses the pycodestyle utility to determine what parts of the code needs to be formatted.

- 🌎 [bandit](bandit.readthedocs.io/en/latest) — A tool to find common security issues in Python code.

- <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [bellybutton](https://github.com/hchasestevens/bellybutton)) — A linting engine supporting custom project-specific rules.

- 🌎 [Black](black.readthedocs.io/en/stable) — The uncompromising Python code formatter.

- 🌎 [Bowler](pybowler.io/) — Safe code refactoring for modern Python.  Bowler is a refactoring tool for manipulating Python at the syntax tree level.  It enables safe, large scale code modifications while guaranteeing that the  resulting code compiles and runs. It provides both a simple command line interface  and a fluent API in Python for generating complex code modifications in code.

- **ciocheck** :warning: — Linter, formatter and test suite helper. As a linter, it is a wrapper around `pep8`, `pydocstyle`, `flake8`, and `pylint`.

- 🌎 [Code Pathfinder](codepathfinder.dev) — An open-source security suite aiming to combine structural code analysis with  AI-powered vulnerability detection. Built for advanced structural search, derive  insights, find vulnerabilities in code.

- **cohesion** :warning: — A tool for measuring Python class cohesion.

- 🌎 [deal](deal.readthedocs.io/) — Design by contract for Python. Write bug-free code.  By adding a few decorators to your code, you get for free tests, static analysis, formal verification, and much more.

- <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Dlint](https://github.com/dlint-py/dlint)) — A tool for ensuring Python code is secure.

- <b><code>&nbsp;&nbsp;&nbsp;127⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Dodgy](https://github.com/landscapeio/dodgy)) — Dodgy is a very basic tool to run against your codebase to search for "dodgy" looking values. It is a series of simple regular expressions designed to detect things such as accidental SCM diff checkins, or passwords or secret keys hard coded into files.

- **ENRE-py** :warning: — ENRE (ENtity Relationship Extractor) is a tool for extraction of code entity dependencies or relationships from source code. ENRE-py is a ENtity Relationship Extractor for Python based on Python Language Services of The Standard Library.

- 🌎 [fixit](pypi.org/project/fixit) — A framework for creating lint rules and corresponding auto-fixes for source code.

- <b><code>&nbsp;&nbsp;3771⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;341🍴</code></b> [flake8](https://github.com/PyCQA/flake8)) — A wrapper around `pyflakes`, `pycodestyle` and `mccabe`.

- 🌎 [flakeheaven](pypi.org/project/flakeheaven/) — flakeheaven is a python linter built around flake8 to enable inheritable and complex toml configuration.

- 🌎 [Griffe](mkdocstrings.github.io/griffe/) — Signatures for entire Python programs. Extract the structure, the frame, the skeleton of your project, to generate API documentation or find breaking changes in your API.

- **InspectorTiger** :warning: — IT, Inspector Tiger, is a modern python code review tool / framework. It comes with bunch of pre-defined handlers which warns you about improvements and possible bugs. Beside these handlers, you can write your own or use community ones.

- 🌎 [jedi](jedi.readthedocs.io/en/latest) — Autocompletion/static analysis library for Python.

- <b><code>&nbsp;&nbsp;&nbsp;185⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [linty fresh](https://github.com/lyft/linty_fresh)) — Parse lint errors and report them to Github as comments on a pull request.

- 🌎 [mbake](pypi.org/project/mbake/) — mbake is a Makefile formatter and linter. It only took 50 years!

- **mccabe** :warning: — Check McCabe complexity.

- **multilint** :warning: — A wrapper around `flake8`, `isort` and `modernize`.

- [mypy](http://www.mypy-lang.org) — A static type checker that aims to combine the benefits of duck typing and static typing, frequently used with <b><code>&nbsp;&nbsp;4996⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [MonkeyType](https://github.com/Instagram/MonkeyType)).

- <b><code>&nbsp;&nbsp;1217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [pip-audit](https://github.com/pypa/pip-audit)) — Tool for scanning Python packages for known vulnerabilities. Developed by the Python Packaging Authority (PyPA) and supported by Trail of Bits and Google. Scans Python environments and requirements files to identify vulnerable packages and suggests remediation. Supports GitHub Actions, pre-commit hooks, and multiple vulnerability service integrations.

- <b><code>&nbsp;&nbsp;2073⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [prospector](https://github.com/PyCQA/prospector)) — A wrapper around `pylint`, `pep8`, `mccabe` and others.

- **py-find-injection** :warning: — Find SQL injection vulnerabilities in Python code.

- 🌎 [pyanalyze](pyanalyze.readthedocs.io/en/latest/) — A tool for programmatically detecting common mistakes in Python code, such as references to undefined variables and type errors. It can be extended to add additional rules and perform checks specific to particular functions.

- 🌎 [pycodestyle](pycodestyle.pycqa.org/en/latest) — (Formerly `pep8`) Check Python code against some of the style conventions in PEP 8.

- **pydocstyle** :warning: — Check compliance with Python docstring conventions.

- 🌎 [pyflakes](pypi.org/project/pyflakes) — Check Python source files for errors.

- [pylint](http://pylint.pycqa.org/en/latest) — Looks for programming errors, helps enforcing a coding standard and sniffs for some code smells. It additionally includes `pyreverse` (an UML diagram generator) and `symilar` (a similarities checker).

- 🌎 [pylyzers](mtshiba.github.io/pylyzer/) — A static code analyzer / language server for Python, written in Rust, focused on type checking and readable output.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Pyra](https://github.com/spangea/Pyra)) — Pyra is a high-level linter static analyzer for data science applications written in Python, that helps developers identify potential issues in their data science code written in Python, as an extension of <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Lyra](https://github.com/caterinaurban/Lyra)).

- **pyre-check** :warning: — A fast, scalable type checker for large Python codebases. Pyre-check has been superseded by Pyrefly, its next iteration.

- 🌎 [pyrefly](pyrefly.org/) — A fast, incremental type checker and language server for Python, providing IDE features like code navigation, semantic highlighting, and code completion.

- <b><code>&nbsp;15330⭐</code></b> <b><code>&nbsp;&nbsp;1780🍴</code></b> [pyright](https://github.com/Microsoft/pyright)) — Static type checker for Python, created to address gaps in existing tools like mypy.

- <b><code>&nbsp;&nbsp;&nbsp;232⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [pyroma](https://github.com/regebro/pyroma)) — Rate how well a Python project complies with the best practices of the Python packaging ecosystem, and list issues that could be improved.

- 🌎 [Pysa](pyre-check.org/docs/pysa-basics.html) — A tool based on Facebook's pyre-check to identify potential security issues in Python code identified with taint analysis.

- **PyT - Python Taint** :warning: — A static analysis tool for detecting security vulnerabilities in Python web applications.

- 🌎 [pytype](google.github.io/pytype) — A static type analyzer for Python code.

- 🌎 [pyupgrade](pypi.org/project/pyupgrade-docs/) — A tool (and pre-commit hook) to automatically upgrade syntax for newer versions of the language.

- **QuantifiedCode** :warning: — Automated code review & repair. It helps you to keep track of issues and metrics in your software projects, and can be easily extended to support new types of analyses.

- **radon** :warning: — A Python tool that computes various metrics from the source code.

- <b><code>&nbsp;&nbsp;2529⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56🍴</code></b> [refurb](https://github.com/dosisod/refurb)) — A tool for refurbishing and modernizing Python codebases. Refurb is heavily inspired by clippy, the built-in linter for Rust.

- 🌎 [ruff](astral.sh/ruff) — Fast Python linter, written in Rust. 10-100x faster than existing linters. Compatible with Python 3.10. Supports file watcher.

- 🌎 [Safety](safetycli.com/) — Python dependency vulnerability scanner designed to enhance software supply chain security by detecting packages with known vulnerabilities. Checks Python dependencies against a database of known security vulnerabilities and provides detailed reports. Supports CI/CD integration and multiple output formats.

- 🌎 [ty](docs.astral.sh/ty/) — An extremely fast Python type checker written in Rust.

- 🌎 [unimport](unimport.hakancelik.dev) — A linter, formatter for finding and removing unused import statements.

- <b><code>&nbsp;&nbsp;4388⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [vulture](https://github.com/jendrikseipp/vulture)) — Find unused classes, functions and variables in Python code.

- 🌎 [wemake-python-styleguide](wemake-python-styleguide.rtfd.io/) — The strictest and most opinionated python linter ever.

- <b><code>&nbsp;&nbsp;1274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [wily](https://github.com/tonybaloney/wily)) — A command-line tool for archiving, exploring and graphing the complexity of Python source code.

- **xenon** :warning: — Monitor code complexity using <b><code>&nbsp;&nbsp;1950⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [`radon`](https://github.com/rubik/radon)).

- **yapf** :warning: — A formatter for Python files created by Google
YAPF follows a distinctive methodology, originating from the 'clang-format' tool created by Daniel Jasper. Essentially, the program reframes the code to the most suitable formatting that abides by the style guide, even if the original code already follows the style guide. This concept is similar to the Go programming language's 'gofmt' tool, which aims to put an end to debates about formatting by having the entire codebase of a project pass through YAPF whenever changes are made, thereby maintaining a consistent style throughout the project and eliminating the need to argue about style in every code review.


<a name="r" />
<h2>R</h2>


- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [CodeDepends](https://github.com/duncantl/CodeDepends)) — Static Code Analysis for R.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [cyclocomp](https://github.com/MangoTheCat/cyclocomp)) — Quantifies the cyclomatic complexity of R functions / expressions.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [flowR](https://github.com/flowr-analysis/flowr)) — A <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [program slicer](https://github.com/flowr-analysis/flowr/wiki/Terminology#program-slice)) and 🌎 [dataflow analyzer](en.wikipedia.org/wiki/Data-flow_analysis) for the 🌎 [R](www.r-project.org/) programming language. Its slicer allows you to reduce a complicated program just to the parts related for a specific task (e.g., the generation of a single or collection of plots, a significance test, ...). The dataflow analysis provides you with a detailed view on the semantics of the R code which can greatly improve other analyses. To use _flowR_, check out the 🌎 [Visual Studio Code extension](marketplace.visualstudio.com/items?itemName=code-inspect.vscode-flowr), the <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [RStudio Addin](https://github.com/flowr-analysis/rstudio-addin-flowr)), the 🌎 [Docker image](hub.docker.com/r/eagleoutice/flowr), or the <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [R package](https://github.com/flowr-analysis/flowr-r-adapter)).

- 🌎 [goodpractice](docs.ropensci.org/goodpractice/) — Analyses the source code for R packages and provides best-practice recommendations.

- <b><code>&nbsp;&nbsp;1270⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;198🍴</code></b> [lintr](https://github.com/jimhester/lintr)) — Static Code Analysis for R.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [R Language Server](https://github.com/REditorSupport/languageserver/)) — Provides code completion, refactoring, folding, diagnostics (with lintr), and more for R.

- 🌎 [rco](jcrodriguez1989.github.io/rco/) — Performance optimizer for R code (with GUI).

- 🌎 [styler](styler.r-lib.org) — Formatting of R source code files and pretty-printing of R code.


<a name="rego" />
<h2>Rego</h2>


- <b><code>&nbsp;&nbsp;&nbsp;368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Regal](https://github.com/styrainc/regal)) — Regal is a linter for the policy language Rego. Regal aims to catch bugs and mistakes in policy code, while at the same time helping people learn the language, best practices and idiomatic constructs.


<a name="ruby" />
<h2>Ruby</h2>


- <b><code>&nbsp;&nbsp;1911⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Active Record Doctor](https://github.com/gregnavis/active_record_doctor)) — Identify database issues before they hit production.

- 🌎 [brakeman](brakemanscanner.org) — A static analysis security vulnerability scanner for Ruby on Rails applications.

- <b><code>&nbsp;&nbsp;7310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;452🍴</code></b> [Bullet](https://github.com/flyerhzm/bullet)) — Help to kill N+1 queries and unused eager loading.

- <b><code>&nbsp;&nbsp;2742⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;243🍴</code></b> [bundler-audit](https://github.com/rubysec/bundler-audit)) — Audit Gemfile.lock for gems with security vulnerabilities reported in <b><code>&nbsp;&nbsp;1055⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;229🍴</code></b> [Ruby Advisory Database](https://github.com/rubysec/ruby-advisory-db)).

- **cane** :warning: — Code quality threshold checking as part of your build.

- **Churn** :warning: — A Project to give the churn file, class, and method for a project for a given checkin. Over time the tool adds up the history of churns to give the number of times a file, class, or method is changing during the life of a project.

- <b><code>&nbsp;&nbsp;1170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [DatabaseConsistency](https://github.com/djezzzl/database_consistency)) — The tool to avoid various issues due to inconsistencies and inefficiencies between a database schema and application models.

- <b><code>&nbsp;&nbsp;&nbsp;748⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [dawnscanner](https://github.com/thesp0nge/dawnscanner)) — A static analysis security scanner for ruby written web applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.

- <b><code>&nbsp;&nbsp;&nbsp;742⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [ERB Lint](https://github.com/Shopify/erb-lint)) — Lint your ERB or HTML files

- <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [ERB::Formatter](https://github.com/nebulab/erb-formatter)) — Format ERB files with speed and precision.

- <b><code>&nbsp;&nbsp;1822⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [Fasterer](https://github.com/DamirSvrtan/fasterer)) — Common Ruby idioms checker.

- 🌎 [flay](ruby.sadi.st/Flay.html) — Flay analyzes code for structural similarities.

- 🌎 [flog](ruby.sadi.st/Flog.html) — Flog reports the most tortured code in an easy to read pain report. The higher the score, the more pain the code is in.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Fukuzatsu](https://github.com/CoralineAda/fukuzatsu)) — A tool for measuring code complexity in Ruby class files. Its analysis generates scores based on cyclomatic complexity algorithms with no added "opinions".

- <b><code>&nbsp;&nbsp;&nbsp;371⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)) — A normaliser/beautifier for HTML that also understands embedded Ruby. Ideal for tidying up Rails templates.

- **laser** :warning: — Static analysis and style linter for Ruby code.

- **MetricFu** :warning: — MetricFu is a set of tools to provide reports that show which parts of your code might need extra work.

- <b><code>&nbsp;&nbsp;&nbsp;436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [pelusa](https://github.com/codegram/pelusa)) — Static analysis Lint-type tool to improve your OO Ruby code.

- **quality** :warning: — Runs quality checks on your code using community tools, and makes sure your numbers don't get any worse over time.

- **Querly** :warning: — Pattern Based Checking Tool for Ruby.

- **Railroader** :warning: — An open source static analysis security vulnerability scanner for Ruby on Rails applications.

- 🌎 [rails_best_practices](rails-bestpractices.com) — A code metric tool for Rails projects

- <b><code>&nbsp;&nbsp;4124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;282🍴</code></b> [reek](https://github.com/troessner/reek)) — Code smell detector for Ruby.

- <b><code>&nbsp;&nbsp;&nbsp;277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [Roodi](https://github.com/roodi/roodi)) — Roodi stands for Ruby Object Oriented Design Inferometer. It parses your Ruby code and warns you about design issues you have based on the checks that it has configured.

- 🌎 [RuboCop](docs.rubocop.org/rubocop) — A Ruby static code analyzer, based on the community Ruby style guide.

- <b><code>&nbsp;&nbsp;&nbsp;644⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Rubrowser](https://github.com/blazeeboy/rubrowser)) — Ruby classes interactive dependency graph generator.

- **ruby-lint** :warning: — Static code analysis for Ruby.

- <b><code>&nbsp;&nbsp;3477⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [rubycritic](https://github.com/whitesmith/rubycritic)) — A Ruby code quality reporter.

- <b><code>&nbsp;&nbsp;&nbsp;933⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [rufo](https://github.com/ruby-formatter/rufo)) — An opinionated ruby formatter, intended to be used via the command line as a text-editor plugin, to autoformat files on save or on demand.

- **Saikuro** :warning: — A Ruby cyclomatic complexity analyzer.

- **SandiMeter** :warning: — Static analysis tool for checking Ruby code for Sandi Metz' rules.

- <b><code>&nbsp;&nbsp;&nbsp;543⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Skunk](https://github.com/fastruby/skunk)) — A SkunkScore Calculator for Ruby Code -- Find the most complicated code without test coverage!

- 🌎 [Sorbet](sorbet.org) — A fast, powerful type checker designed for Ruby.

- <b><code>&nbsp;&nbsp;2890⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;230🍴</code></b> [Standard Ruby](https://github.com/testdouble/standard)) — Ruby Style Guide, with linter & automatic code fixer

- <b><code>&nbsp;&nbsp;1480⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Steep](https://github.com/soutaro/steep)) — Gradual Typing for Ruby.

- <b><code>&nbsp;&nbsp;&nbsp;904⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Traceroute](https://github.com/amatsuda/traceroute)) — A Rake task gem that helps you find the unused routes and controller actions for your Rails 3+ app.


<a name="rust" />
<h2>Rust</h2>


- 🌎 [C2Rust](c2rust.com) — C2Rust helps you migrate C99-compliant code to Rust. The translator (or transpiler) produces unsafe Rust code that closely mirrors the input C code.

- <b><code>&nbsp;&nbsp;2085⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [cargo udeps](https://github.com/est31/cargo-udeps)) — Find unused dependencies in Cargo.toml. It either prints out a "unused crates" line listing the crates,  or it prints out a line saying that no crates were unused.

- 🌎 [cargo-audit](rustsec.org) — Audit Cargo.lock for crates with security vulnerabilities reported to the <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [RustSec Advisory Database](https://github.com/RustSec/advisory-db/)).

- **cargo-bloat** :warning: — Find out what takes most of the space in your executable. supports ELF (Linux, BSD), Mach-O (macOS) and PE (Windows) binaries.

- <b><code>&nbsp;&nbsp;&nbsp;111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [cargo-breaking](https://github.com/iomentum/cargo-breaking)) — cargo-breaking compares a crate's public API between two different branches, shows what changed, and suggests the next version according to semver.

- <b><code>&nbsp;&nbsp;&nbsp;650⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [cargo-call-stack](https://github.com/japaric/cargo-call-stack)) — Whole program static stack analysis The tool produces the full call graph of a program as a dot file.

- 🌎 [cargo-deny](embarkstudios.github.io/cargo-deny) — A cargo plugin for linting your dependencies. It can be used either as a command line too, a Rust crate, or a Github action for CI. It checks for valid license information, duplicate crates, security vulnerabilities, and more.

- <b><code>&nbsp;&nbsp;3051⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [cargo-expand](https://github.com/dtolnay/cargo-expand)) — Cargo subcommand to show result of macro expansion  and #[derive] expansion applied to the current crate.  This is a wrapper around a more verbose compiler command.

- <b><code>&nbsp;&nbsp;1568⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [cargo-geiger](https://github.com/geiger-rs/cargo-geiger)) — A cargo plugin for analysing the usage of unsafe Rust code Provides statistical output to aid security auditing

- **cargo-inspect** :warning: — Inspect Rust code without syntactic sugar to see what the compiler does behind the curtains.

- 🌎 [cargo-semver-checks](crates.io/crates/cargo-semver-checks) — Scan your Rust crate releases for semver violations. It can be used either directly via the CLI, as a GitHub Action in CI,  or via release managers like `release-plz`. It found semver violations in  🌎 [more than 1 in 6 of the top 1000 most-downloaded crates](predr.ag/blog/semver-violations-are-common-better-tooling-is-the-answer/) on crates.io.

- <b><code>&nbsp;&nbsp;&nbsp;930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [cargo-show-asm](https://github.com/pacak/cargo-show-asm)) — cargo subcommand showing the assembly, LLVM-IR and MIR generated for Rust code

- <b><code>&nbsp;&nbsp;&nbsp;358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [cargo-spellcheck](https://github.com/drahnr/cargo-spellcheck)) — Checks all your documentation for spelling and grammar mistakes  with hunspell (ready) and languagetool (preview)

- **cargo-unused-features** :warning: — Find potential unused enabled feature flags and prune them. You can generate a simple HTML report from the json to make it easier to inspect results.
It removes a feature of a dependency and then compiles the project to see if it still compiles. If it does, the feature flag can possibly be removed, but it can be a false-positive.

- 🌎 [clippy](rust-lang.github.io/rust-clippy) — A code linter to catch common mistakes and improve your Rust code.

- 🌎 [diff.rs](diff.rs) — Web application (WASM) to render a diff between Rust crate versions.

- 🌎 [dylint](www.trailofbits.com/post/write-rust-lints-without-forking-clippy) — A tool for running Rust lints from dynamic libraries. Dylint makes it easy for developers to maintain their own personal lint collections.

- **electrolysis** :warning: — A tool for formally verifying Rust programs by transpiling them into definitions in the Lean theorem prover.

- **herbie** :warning: — Adds warnings or errors to your crate when using a numerically unstable floating point expression.

- <b><code>&nbsp;&nbsp;2989⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [kani](https://github.com/model-checking/kani)) — The Kani Rust Verifier is a bit-precise model checker for Rust. 
Kani is particularly useful for verifying unsafe code blocks in Rust, 
where the "unsafe superpowers" are unchecked by the compiler.
Kani verifies:

* Memory safety (e.g., null pointer dereferences)
* User-specified assertions (i.e., assert!(...))
* The absence of panics (e.g., unwrap() on None values)
* The absence of some types of unexpected behavior (e.g., arithmetic overflows)


- **linter-rust** :warning: — Linting your Rust-files in Atom, using rustc and cargo.

- <b><code>&nbsp;&nbsp;&nbsp;588⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [lockbud](https://github.com/BurtonQin/lockbud)) — Statically detects Rust deadlocks bugs. It currently detects two common kinds of deadlock bugs: doublelock and locks in conflicting order. It will print bugs in JSON format together with the source code location and an explanation of each bug.

- **MIRAI** :warning: — And abstract interpreter operating on Rust's mid-level intermediate language, and providing warnings based on taint analysis.

- **prae** :warning: — Provides a convenient macro that allows you to generate type wrappers  that promise to always uphold arbitrary invariants that you specified. 

- **Prusti** :warning: — A static verifier for Rust, based on the Viper verification infrastructure. By default Prusti verifies absence of panics by proving that statements such as unreachable!() and panic!() are unreachable.

- **Rudra** :warning: — Rust Memory Safety & Undefined Behavior Detection. It is capable of analyzing single Rust packages as well as all the packages on crates.io.

- **Rust Language Server** :warning: — Supports functionality such as 'goto definition', symbol search, reformatting, and code completion, and enables renaming and refactorings.

- 🌎 [rust-analyzer](rust-analyzer.github.io) — Supports functionality such as 'goto definition', type inference, symbol search, reformatting, and code completion, and enables renaming and refactorings.

- <b><code>&nbsp;&nbsp;&nbsp;814⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [rust-audit](https://github.com/Shnatsel/rust-audit)) — Audit Rust binaries for known bugs or security vulnerabilities. This works by embedding data about the dependency tree (Cargo.lock) in JSON format into a dedicated linker section of the compiled executable.

- <b><code>&nbsp;&nbsp;&nbsp;853⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [rustfix](https://github.com/rust-lang/rustfix)) — Read and apply the suggestions made by rustc (and third-party lints, like those offered by clippy).

- <b><code>&nbsp;&nbsp;6781⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;996🍴</code></b> [rustfmt](https://github.com/rust-lang/rustfmt)) — A tool for formatting Rust code according to style guidelines.

- <b><code>&nbsp;&nbsp;2827⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [RustViz](https://github.com/rustviz/rustviz)) — RustViz is a tool that generates visualizations  from simple Rust programs to assist users in better  understanding the Rust Lifetime and Borrowing mechanism. It generates SVG files with graphical indicators that integrate  with mdbook to render visualizations of data-flow in Rust programs.

- 🌎 [TangleGuard](tangleguard.com/) :copyright: — Helps you understand and maintain a scalable software architecture. To do so, it generates a interactive, nested dependency graph out of the source code. You can choose the level of details and get the portion of your codebase that matters to you.

- **warnalyzer** :warning: — Show unused code from multi-crate Rust projects


<a name="sql" />
<h2>SQL</h2>


- <b><code>&nbsp;&nbsp;&nbsp;179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [dbcritic](https://github.com/channable/dbcritic)) — dbcritic finds problems in a database schema, such as a missing primary key constraint in a table.

- 🌎 [holistic](holistic.dev/) — More than 1,300 rules to analyze SQL queries. Takes an SQL schema definition and the query source code to generate improvement recommendations. Detects code smells, unused indexes, unused tables, views, materialized views, and more.

- <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [pgspot](https://github.com/timescale/pgspot)) — Spot vulnerabilities in postgres extension scripts. Finds unsafe search_path usage and unsafe object creation in PostgreSQL extension scripts or any other PostgreSQL SQL code.

- <b><code>&nbsp;&nbsp;&nbsp;274⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [sleek](https://github.com/nrempel/sleek)) — Sleek is a CLI tool for formatting SQL.  It helps you maintain a consistent style across your SQL code, enhancing readability and productivity. The heavy lifting is done by the sqlformat crate.

- **sqlcheck** :warning: — Automatically identify anti-patterns in SQL queries.

- 🌎 [SQLFluff](www.sqlfluff.com/) — Multiple dialect SQL linter and formatter.

- <b><code>&nbsp;&nbsp;&nbsp;437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [sqlint](https://github.com/purcell/sqlint)) — Simple SQL linter.

- 🌎 [squawk](squawkhq.com) — Linter for PostgreSQL, focused on migrations. Prevents unexpected downtime caused by database migrations and encourages best practices around Postgres schemas and SQL.

- **tsqllint** :warning: — T-SQL-specific linter.

- **TSqlRules** :warning: — TSQL Static Code Analysis Rules for SQL Server.

- 🌎 [Visual Expert](www.visual-expert.com) :copyright: — Code analysis for PowerBuilder, Oracle, and SQL Server Explores, analyzes, and documents Code 


<a name="scala" />
<h2>Scala</h2>


- **linter** :warning: — Linter is a Scala static analysis compiler plugin which adds compile-time checks for various possible bugs, inefficiencies, and style problems.

- [Scalastyle](http://www.scalastyle.org) — Scalastyle examines your Scala code and indicates potential problems with it.

- <b><code>&nbsp;&nbsp;&nbsp;554⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [scapegoat](https://github.com/sksamuel/scapegoat)) — Scala compiler plugin for static code analysis.

- 🌎 [WartRemover](www.wartremover.org) — A flexible Scala code linting tool.


<a name="shell" />
<h2>Shell</h2>


- <b><code>&nbsp;&nbsp;&nbsp;394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [bashate](https://github.com/openstack/bashate)) — Code style enforcement for bash programs. The output format aims to follow pycodestyle (pep8) default output format.

- **i-Code CNES for Shell** :warning: — An open source static code analysis tool for Shell and Fortran (77 and 90).

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [kmdr](https://github.com/ediardo/kmdr-cli)) — CLI tool for learning commands from your terminal. kmdr delivers a break down of commands with every attribute explained.

- 🌎 [sh](pkg.go.dev/mvdan.cc/sh/v3) — A shell parser, formatter, and interpreter with bash support; includes shfmt

- 🌎 [shellcheck](www.shellcheck.net) — ShellCheck, a static analysis tool that gives warnings and suggestions for bash/sh shell scripts.

- <b><code>&nbsp;&nbsp;4762⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;134🍴</code></b> [shellharden](https://github.com/anordal/shellharden)) — A syntax highlighter and a tool to semi-automate the rewriting of scripts to ShellCheck conformance, mainly focused on quoting.


<a name="swift" />
<h2>Swift</h2>


- <b><code>&nbsp;&nbsp;8740⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;685🍴</code></b> [SwiftFormat](https://github.com/nicklockwood/SwiftFormat)) — A library and command-line formatting tool for reformatting Swift code.

- 🌎 [SwiftLint](realm.github.io/SwiftLint) — A tool to enforce Swift style and conventions.

- **Tailor** :warning: — A static analysis and lint tool for source code written in Apple's Swift programming language.


<a name="tcl" />
<h2>Tcl</h2>


- [Frink](http://catless.ncl.ac.uk/Programs/Frink) — A Tcl formatting and static check program (can prettify the program, minimise, obfuscate or just sanity check it).

- 🌎 [Nagelfar](sourceforge.net/projects/nagelfar) — A static syntax checker for Tcl.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [tclchecker](https://github.com/ActiveState/tdk/blob/master/docs/3.0/TDK_3.0_Checker.txt)) — A static syntax analysis module (as part of <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [TDK](https://github.com/ActiveState/tdk))).


<a name="typescript" />
<h2>TypeScript</h2>


- <b><code>&nbsp;&nbsp;1779⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;260🍴</code></b> [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme)) — Linter for Angular projects

- **Codelyzer** :warning: — A set of tslint rules for static code analysis of Angular 2 TypeScript projects.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [ENRE-ts](https://github.com/xjtu-enre/ENRE-ts)) — ENRE (ENtity Relationship Extractor) is a tool for extraction of code entity dependencies or relationships from source code. ENRE-ts is a ENtity Relationship Extractor for ECMAScript and TypeScript based on @babel/parser.

- 🌎 [fta](ftaproject.dev/) — Rust-based static analysis for TypeScript projects

- **stc** :warning: — Speedy TypeScript type checker written in Rust

- **tslint** :warning: — TSLint has been deprecated as of 2019. Please see <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [this issue](https://github.com/palantir/tslint/issues/4534)) for more details. `typescript-eslint` is now your best option for linting TypeScript.
TSLint is an extensible static analysis tool that checks TypeScript code for readability, maintainability,  and functionality errors. It is widely supported across modern editors & build systems and can be customized  with your own lint rules, configurations, and formatters.

- 🌎 [tslint-clean-code](www.npmjs.com/package/tslint-clean-code) — A set of TSLint rules inspired by the Clean Code handbook.

- **tslint-microsoft-contrib** :warning: — A set of tslint rules for static code analysis of TypeScript projects maintained by Microsoft.

- <b><code>&nbsp;&nbsp;&nbsp;284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [TypeScript Call Graph](https://github.com/whyboris/TypeScript-Call-Graph)) — CLI to generate an interactive graph of functions and calls from your TypeScript files

- <b><code>&nbsp;16162⭐</code></b> <b><code>&nbsp;&nbsp;2893🍴</code></b> [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint)) — TypeScript language extension for eslint.

- 🌎 [zod](zod.dev) — TypeScript-first schema validation with static type inference. The goal is to eliminate duplicative type declarations. With Zod, you declare a validator once and Zod will automatically infer the static TypeScript type. It is easy to compose simpler types into complex data structures.


<a name="verilog" />
<h2>Verilog/SystemVerilog</h2>


- **Icarus Verilog** :warning: — A Verilog simulation and synthesis tool that operates by compiling source code written in IEEE-1364 Verilog into some target format

- <b><code>&nbsp;&nbsp;&nbsp;566⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [svls](https://github.com/dalance/svls)) — A Language Server Protocol implementation for Verilog and SystemVerilog, including lint capabilities.

- **verible-linter-action** :warning: — Automatic SystemVerilog linting in github actions with the help of Verible Used to lint Verilog and SystemVerilog source files and comment erroneous lines  of code in Pull Requests automatically.

- 🌎 [Verilator](www.veripool.org/verilator) — A tool which converts Verilog to a cycle-accurate behavioral model in C++ or SystemC. Performs lint code-quality checks.

- <b><code>&nbsp;&nbsp;&nbsp;358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [vscode-verilog-hdl-support](https://github.com/mshr-h/vscode-verilog-hdl-support)) — Verilog HDL/SystemVerilog/Bluespec SystemVerilog support for VS Code. Provides syntax highlighting and Linting support from Icarus Verilog, Vivado Logical Simulation, Modelsim and Verilator


<a name="vim-script" />
<h2>Vim Script</h2>


- **vint** :warning: — Fast and Highly Extensible Vim script Language Lint implemented by Python.


<a name="wasm" />
<h2>WebAssembly</h2>


- <b><code>&nbsp;&nbsp;1427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Twiggy](https://github.com/rustwasm/twiggy)) — Analyzes a binary's call graph to profile code size. The goal is to slim down wasm binary size.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [wasm-language-tools](https://github.com/g-plane/wasm-language-tools)) — WebAssembly Language Tools aims to provide and improve the editing experience of WebAssembly Text Format. It also provides an out-of-the-box formatter (a.k.a. pretty printer) for WebAssembly Text Format.


## Multiple languages


- <b><code>&nbsp;13979⭐</code></b> <b><code>&nbsp;&nbsp;1482🍴</code></b> [ale](https://github.com/w0rp/ale)) — Asynchronous Lint Engine for Vim and NeoVim with support for many languages.

- 🌎 [Android Studio](developer.android.com/studio) — Based on IntelliJ IDEA, and comes bundled with tools for Android including Android Lint.

- 🌎 [AppChecker](npo-echelon.ru/en/solutions/appchecker.php) :copyright: — Static analysis for C/C++/C#, PHP and Java.

- 🌎 [Application Inspector](www.ptsecurity.com/ww-en/products/ai) :copyright: — Commercial Static Code Analysis which generates exploits to verify vulnerabilities.

- <b><code>&nbsp;&nbsp;4387⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;366🍴</code></b> [ApplicationInspector](https://github.com/microsoft/ApplicationInspector)) — Creates reports of over 400 rule patterns for feature detection (e.g. the use of cryptography or version control in apps).

- 🌎 [ArchUnit](www.archunit.org) — Unit test your Java or Kotlin architecture.

- 🌎 [ast-grep](ast-grep.github.io/) — ast-grep is a powerful tool designed for managing code at scale using Abstract Syntax Trees (AST). Think of it as a hybrid of grep, eslint, and codemod, with the ability to search, lint, and rewrite code based on its structure rather than plain text.
It supports multiple languages and is designed to be extensible, allowing you to register custom languages.

- **Atom-Beautify** :warning: — Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom editor.

- 🌎 [autocorrect](huacnlee.github.io/autocorrect) — A linter and formatter to help you to improve copywriting, correct spaces, words, punctuations between CJK (Chinese, Japanese, Korean).

- 🌎 [Axivion Bauhaus Suite](www.axivion.com/en/products-services-9#products_bauhaussuite) :copyright: — Tracks down error-prone code locations, style violations, cloned or dead code, cyclic dependencies and more for C/C++, C#/.NET, Java and Ada 83/Ada 95.

- <b><code>&nbsp;&nbsp;2600⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [Bearer](https://github.com/bearer/bearer)) — Open-Source static code analysis tool to discover,  filter and prioritize security risks and vulnerabilities  leading to sensitive data exposures (PII, PHI, PD).  Highly configurable and easily extensible,  built for security and engineering teams.

- 🌎 [Better Code Hub](bettercodehub.com) :copyright: — Better Code Hub checks your GitHub codebase against 10 engineering guidelines devised by the authority in software quality, Software Improvement Group.

- **Betterscan CE** :warning: — Checks your code and infra (various Git repositories supported, cloud stacks, CLI, Web Interface platform, integrationss available) for security and quality issues. Code Scanning/SAST/Linting using many tools/Scanners deduplicated with One Report (AI optional).

- 🌎 [biome](biomejs.dev) — A toolchain for web projects, aimed to provide functionalities to maintain them. Biome formats and lints code in a fraction of a second. It is the successor to Rome. It is designed to eventually replace Biome is designed to eventually replace Babel, ESLint, webpack, Prettier, Jest, and others.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [BlockWatch](https://github.com/mennanov/blockwatch)) — A language-agnostic linter that keeps code, documentation, and configuration in sync and enforces strict formatting and validation rules.

- **BugProve** :warning: :copyright: — BugProve is a firmware analysis platform featuring both static and dynamic analysis techniques to discover memory corruptions, command injections and other classes or common weaknesses in binary code. It also detects vulnerable dependencies, weak cryptographic parameters, misconfigurations, and more.

- <b><code>&nbsp;&nbsp;&nbsp;327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [callGraph](https://github.com/koknat/callGraph)) — Statically generates a call graph image and displays it on screen.

- 🌎 [CAST Highlight](www.castsoftware.com/products/highlight) :copyright: — Commercial Static Code Analysis which runs locally, but uploads the results to its cloud for presentation.

- 🌎 [Checkmarx CxSAST](www.checkmarx.com/products/static-application-security-testing) :copyright: — Commercial Static Code Analysis which doesn't require pre-compilation.

- <b><code>&nbsp;&nbsp;2968⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;301🍴</code></b> [ClassGraph](https://github.com/classgraph/classgraph)) — A classpath and module path scanner for querying or visualizing class metadata or class relatedness.

- 🌎 [Clayton](www.getclayton.com/) :copyright: — AI-powered code reviews for Salesforce. Secure your developments, enforce best practice and control your technical debt in real-time.

- **coala** :warning: — Language independent framework for creating code analysis - supports over 60 languages by default.

- 🌎 [Cobra](spinroot.com/cobra) :copyright: — Structural source code analyzer by NASA's Jet Propulsion Laboratory.

- 🌎 [Codacy](www.codacy.com) :copyright: — Code Analysis to ship Better Code, Faster.

- 🌎 [Code Intelligence](www.code-intelligence.com) :copyright: — CI/CD-agnostic DevSecOps platform which combines industry-leading fuzzing engines for finding bugs and visualizing code coverage

- 🌎 [Code-Graph-RAG](code-graph-rag.com) — Builds knowledge graphs from multi-language codebases using Tree-sitter AST parsing and stores them in Memgraph. Supports 11 programming languages with a unified graph schema and enables natural language querying and editing of code structure and relationships. Functions as an MCP server for AI assistant integration.

- 🌎 [Codeac](www.codeac.io/?ref=awesome-static-analysis) :copyright: — Automated code review tool integrates with GitHub, Bitbucket and GitLab (even self-hosted). Available for JavaScript, TypeScript, Python, Ruby, Go, PHP, Java, Docker, and more. (open-source free)

- 🌎 [codeburner](groupon.github.io/codeburner) — Provides a unified interface to sort and act on the issues it finds.

- 🌎 [codechecker](codechecker.readthedocs.io/en/latest) — A defect database and viewer extension for the Clang Static Analyzer with web GUI.

- 🌎 [CodeFactor](codefactor.io) :copyright: — Automated Code Analysis for repos on GitHub or BitBucket.

- 🌎 [CodeFlow](www.getcodeflow.com) :copyright: — Automated code analysis tool to deal with technical depth. Integrates with Bitbucket and Gitlab. (free for Open Source Projects)

- 🌎 [Codemodder](codemodder.io/) — Codemodder is a pluggable framework for building expressive codemods. Use Codemodder when you need more than a linter or code formatting tool. Use it to fix non-trivial security issues and other code quality problems.

- <b><code>&nbsp;&nbsp;9370⭐</code></b> <b><code>&nbsp;&nbsp;1940🍴</code></b> [codeql](https://github.com/github/codeql)) — Deep code analysis - semantic queries and dataflow for several languages with VSCode plugin support.

- 🌎 [CodeQue](codeque.co) — Ecosystem for structural matching JavaScript and TypeScript code. Offers search tool that understands code structure. Available as CLI tool and Visual Studio Code extension. It helps to search code faster and more accurately making you workflow more effective. Soon it will offer ESLint plugin to create your own rules in minutes to help with assuring codebase quality.

- 🌎 [CodeRush](www.devexpress.com/products/coderush) :copyright: — Code creation, debugging, navigation, refactoring, analysis and visualization tools that use the Roslyn engine in Visual Studio 2015 and up.

- 🌎 [CodeScan](www.codescan.io/) :copyright: — Code Quality and Security for Salesforce Developers. Made exclusively for the Salesforce platform, CodeScan’s code analysis solutions provide you with total visibility into your code health.

- 🌎 [CodeScene](codescene.com) :copyright: — CodeScene is a quality visualization tool for software. Prioritize technical debt, detect delivery risks, and measure organizational aspects. Fully automated.

- 🌎 [CodeSee](www.codesee.io/) :copyright: — CodeSee is mapping and automating your app's services, directories, file dependencies, and code changes. It's like Google Map, but for code.t

- 🌎 [CodeSonar from GrammaTech](codesecure.com/our-products/codesonar/) :copyright: — Advanced, whole program, deep path, static analysis of C, C++, Java and C# with easy-to-understand explanations and code and path visualization.

- 🌎 [Codety](www.codety.io) :copyright: — Codety Scanner is a comprehensive source code scanner that embeds 5000+ static code analysis rules, which aim to detect code issues for 20+ programming languages and IaC tools.

- 🌎 [Codiga](www.codiga.io) :copyright: — Automated Code Reviews and Technical Debt management platform that supports 12+ languages.

- 🌎 [Corgea](corgea.com/) :copyright: — Corgea is an AI-powered SAST scanner that helps developers find and fix insecure code.  It finds business logic flaws, broken authentication, API vulnerabilities, and more with little false positives. Additionally, it automatically writes security fixes for them to approve.  Corgea integrates with GitHub, GitLab, Azure DevOps, IDEs and CLI. It is free to try it.

- **Corrode** :warning: — Semi-automatic translation from C to Rust. Could reveal bugs in the original implementation by showing Rust compiler warnings and errors. Superseded by C2Rust.

- 🌎 [Coverity](www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: — Synopsys Coverity supports 20 languages and over 70 frameworks including Ruby on rails, Scala, PHP, Python, JavaScript, TypeScript, Java, Fortran, C, C++, C#, VB.NET.

- 🌎 [cpp-linter-action](cpp-linter.github.io/cpp-linter-action/) — A Github Action for linting C/C++ code integrating clang-tidy and clang-format to collect feedback provided in the form of thread comments and/or annotations.

- **cqc** :warning: — Check your code quality for js, jsx, vue, css, less, scss, sass and styl files.

- **DeepCode** :warning: :copyright: — DeepCode was acquired by Snyk is now Snyk Code.

- 🌎 [DeepSource](deepsource.com) :copyright: — In-depth static analysis to find issues in verticals of bug risks, security, anti-patterns, performance, documentation and style. Native integrations with GitHub, GitLab and Bitbucket. Less than 5% false positives.

- 🌎 [deleaker](www.deleaker.com/) :copyright: — Deleaker is a memory leak detection tool for C++, .NET, and Delphi, integrating with Visual Studio, Qt Creator, and RAD Studio or running as a standalone application. It helps developers find and fix memory, GDI, and handle leaks efficiently.

- <b><code>&nbsp;&nbsp;&nbsp;247⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [Depends](https://github.com/multilang-depends/depends)) — Analyses the comprehensive dependencies of code elements for Java, C/C++, Ruby.

- 🌎 [DerScanner](derscanner.com/) :copyright: — Multi-language Static Application Security Testing (SAST) platform that detects critical vulnerabilities, including hardcoded secrets, weak cryptography, backdoors, SQL injections, insecure configurations, etc.

- <b><code>&nbsp;&nbsp;&nbsp;976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;123🍴</code></b> [DevSkim](https://github.com/microsoft/devskim)) — Regex-based static analysis tool for Visual Studio, VS Code, and Sublime Text - C/C++, C#, PHP, ASP, Python, Ruby, Java, and others.

- <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [diesel-guard](https://github.com/ayarotsky/diesel-guard)) — Linter for dangerous Postgres migration patterns in Diesel and SQLx. Prevents downtime caused by unsafe schema changes.

- <b><code>&nbsp;&nbsp;1944⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;171🍴</code></b> [dotnet-format](https://github.com/dotnet/format)) — A code formatter for .NET. Preferences will be read from an `.editorconfig` file, if present, otherwise a default set of preferences will be used. At this time dotnet-format is able to format C# and Visual Basic projects with a subset of supported `.editorconfig` options.

- 🌎 [Embold](embold.io) :copyright: — Intelligent software analytics platform that identifies design issues, code issues, duplication and metrics. Supports Java, C, C++, C#, JavaScript, TypeScript, Python, Go, Kotlin and more.

- **emerge** :warning: — Emerge is a source code and dependency visualizer that can be used to gather insights about source code structure, metrics, dependencies and complexity of software projects. After scanning the source code of a project it provides you an interactive web interface to explore and analyze your project by using graph structures.

- 🌎 [Enforster AI](enforster.ai/) :copyright: — Enforster AI performs Contextual Code Security SAST, leveraging LLMs and artificial intelligence to reduce  and enrich the detection of Logic Flaws, Secrets, Data leaks, Supply chain and technical vulnerabilities. 

- <b><code>&nbsp;27224⭐</code></b> <b><code>&nbsp;&nbsp;4947🍴</code></b> [ESLint](https://github.com/eslint/eslint)) — An extensible linter for JS, following the ECMAScript standard.

- 🌎 [ezno](kaleidawave.github.io/posts/introducing-ezno/) — A JavaScript compiler and TypeScript checker written in Rust with a focus on static analysis and runtime performance. Ezno's type checker is built from scratch.  The checker is fully compatible with TypeScript type annotations and can work without any type annotations at all.

- 🌎 [Find Security Bugs](find-sec-bugs.github.io) — The SpotBugs plugin for security audits of Java web applications and Android applications. (Also work with Kotlin, Groovy and Scala projects)

- 🌎 [Fortify](www.microfocus.com/en-us/cyberres/application-security/static-code-analyzer) :copyright: — A commercial static analysis platform that supports the scanning of C/C++, C#, VB.NET, VB6, ABAP/BSP, ActionScript, Apex, ASP.NET, Classic ASP, VB Script, Cobol, ColdFusion, HTML, Java, JS, JSP, MXML/Flex, Objective-C, PHP, PL/SQL, T-SQL, Python (2.6, 2.7), Ruby (1.9.3), Swift, Scala, VB, and XML.

- 🌎 [Freeplane Code Explorer](docs.freeplane.org/user-documentation/Code_Explorer.html) — The Code Explorer mode in Freeplane is designed for analyzing the structure and dependencies  of code compiled to JVM class files.  It also allows displaying ArchUnit test results directly in Freeplane,  if Freeplane is running and ArchUnit detects rule violations during the tests.


- 🌎 [Goodcheck](sider.github.io/goodcheck) — Regexp based customizable linter.

- **goone** :warning: — Finds N+1 queries (SQL calls in a for loop) in go code

- [graudit](http://www.justanotherhacker.com) — Grep rough audit - source code auditing tool.

- 🌎 [HCL AppScan Source](www.hcltechsw.com/products/appscan) :copyright: — Commercial Static Code Analysis.

- **Hopper** :warning: — A static analysis tool written in scala for languages that run on JVM.

- 🌎 [Hound CI](houndci.com) — Comments on style violations in GitHub pull requests. Supports Coffeescript, Go, HAML, JavaScript, Ruby, SCSS and Swift.

- **imhotep** :warning: — Comment on commits coming into your repository and check for syntactic errors and general lint warnings.

- **include-gardener** :warning: — A multi-language static analyzer for C/C++/Obj-C/Python/Ruby to create a graph (in dot or graphml format) which shows all `#include` relations of a given set of files.

- 🌎 [Infer](fbinfer.com) — A static analyzer for Java, C and Objective-C

- 🌎 [Joern](joern.io) — Joern is a platform for analyzing source code, bytecode, and binary executables. It generates code property graphs (CPGs), a graph representation of code for cross-language code analysis. Code property graphs are stored in a custom graph database. This allows code to be mined using search queries formulated in a Scala-based domain-specific query language. Joern is developed with the goal of providing a useful tool for vulnerability discovery and research in static program analysis.

- 🌎 [jQAssistant](jqassistant.org/) — jQAssistant is a plugin based software analytics platform which allows scanning code structures and metadata from repositories into a Neo4j graph database.  The gathered data can be used for ad-hoc exploration using queries, visualization or defining rules for continuous architecture validation.

- 🌎 [keploy](keploy.io/) — Keploy is an open-source testing platform that helps developers automate and streamline their testing process. It provides API, and integration testing agents, generating tests, mocks/stubs for APIs that actually work. Additionally, Keploy offers an AI-powered Unit Testing Agent that generates stable, useful unit tests directly in your GitHub PRs and in VSCode, helping catch errors and improve code quality.

- 🌎 [Kiuwan](www.kiuwan.com/code-security-sast) :copyright: — Identify and remediate cyber threats in a blazingly fast, collaborative environment, with seamless integration in your SDLC. Python, C\C++, Java, C#, PHP and more.

- 🌎 [Klocwork](www.perforce.com/products/klocwork) :copyright: — Quality and Security Static analysis for C/C++, Java and C#.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [LangLint](https://github.com/HzaCode/Langlint)) — Automated translation platform for code comments and docstrings across 20+ file types. Eliminates language barriers in international software collaboration. Supports 100+ language pairs with syntax protection. Integrates into CI/CD pipelines like Ruff. 10-20x faster with concurrent processing.

- 🌎 [LGTM](lgtm.com/) :copyright: — Find security vulnerabilities, variants, and critical code quality issues using CodeQL queries over source code. Automatic PR code review; free for open source. Formerly semmle. It supports public Git repositories hosted on Bitbucket Cloud, GitHub.com, GitLab.com.

- <b><code>&nbsp;&nbsp;2294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;289🍴</code></b> [lizard](https://github.com/terryyin/lizard)) — Lizard is an extensible Cyclomatic Complexity Analyzer for many programming languages  including C/C++ (doesn't require all the header files or Java imports).  It also does copy-paste detection (code clone detection/code duplicate detection) and many other forms of static code analysis. Counts lines of code without comments, CCN (cyclomatic complexity number), token count of functions, parameter count of functions.

- 🌎 [Mega-Linter](megalinter.io/) — Mega-Linter can handle any type of project thanks to its 70+ embedded Linters,
 its advanced reporting, runnable on any CI system or locally,
 with assisted installation and configuration, able to apply formatting and fixes

- 🌎 [Mobb](mobb.ai) :copyright: — Mobb is a trusted, automatic vulnerability fixer that secures applications, reduces security backlogs,  and frees developers to focus on innovation. Mobb is free for open-source projects.

- 🌎 [MOPSA](mopsa.lip6.fr) — A static analyzer designed to easily reuse abstract domains across widely different languages (such as C and Python).

- 🌎 [Neurolint-CLI](neurolint.dev) — Deterministic code transformation tool using AST parsing and rule-based transformations. 
Automatically fixes 50+ issues including accessibility violations, hydration errors, 
React 19/Next.js 16 migrations, and configuration updates. Features 5-step fail-safe 
orchestration to ensure zero breaking changes. Specialized for React, Next.js, and TypeScript projects.


- [oclint](http://oclint.org) — A static source code analysis tool to improve quality and reduce defects for C, C++ and Objective-C.

- 🌎 [Offensive 360](offensive360.com/) :copyright: — Commercial Static Code Analysis system doesn't require building the source code or pre-compilation.

- 🌎 [OpenRewrite](docs.openrewrite.org/) — OpenRewrite 🌎 [fixes common static analysis issues](docs.openrewrite.org/running-recipes/popular-recipe-guides/common-static-analysis-issue-remediation)  reported through Sonar and other tools using a Maven and Gradle plugin or the Moderne CLI.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [OpenStaticAnalyzer](https://github.com/sed-inf-u-szeged/OpenStaticAnalyzer)) — OpenStaticAnalyzer is a source code analyzer tool, which can perform deep static analysis of the source code of complex systems.

- <b><code>&nbsp;20226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;917🍴</code></b> [oxc](https://github.com/web-infra-dev/oxc)) — The Oxidation Compiler is creating a suite of high-performance tools for the JavaScript / TypeScript language re-written in Rust.

- 🌎 [parasoft](www.parasoft.com/) :copyright: — Automated Software Testing Solutions for unit-, API-, and web UI testing. Complies with MISRA, OWASP, and others.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [pfff](https://github.com/facebookarchive/pfff/wiki/Main)) — Facebook's tools for code analysis, visualizations, or style-preserving source transformation for many languages.

- 🌎 [Pixee](pixee.ai) :copyright: — Pixeebot finds security and code quality issues in your code and creates merge-ready pull requests with recommended fixes.

- 🌎 [PMD](pmd.github.io) — A source code analyzer for Java, Salesforce Apex, Javascript, PLSQL, XML, XSL and others.

- 🌎 [pre-commit](pre-commit.com) — A framework for managing and maintaining multi-language pre-commit hooks.

- 🌎 [Precaution](www.securesauce.dev/) — Precaution is a static analysis security tool (SAST) designed to find potentially critical vulnerabilities in source code prior to production. It is available as a CLI, GitHub Action, and GitHub App.

- 🌎 [Prettier](prettier.io) — An opinionated code formatter.

- <b><code>&nbsp;&nbsp;2662⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;249🍴</code></b> [Pronto](https://github.com/prontolabs/pronto)) — Quick automated code review of your changes. Supports more than 40 runners for various languages, including Clang, Elixir, JavaScript, PHP, Ruby and more.

- **PT.PM** :warning: — An engine for searching patterns in the source code, based on Unified AST or UST. At present time C#, Java, PHP, PL/SQL, T-SQL, and JavaScript are supported. Patterns can be described within the code or using a DSL.

- <b><code>&nbsp;&nbsp;&nbsp;781⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [Putout](https://github.com/coderaiser/putout)) — Pluggable and configurable code transformer with built-in eslint, babel plugins support for js, jsx typescript, flow, markdown, yaml and json.

- 🌎 [PVS-Studio](pvs-studio.com) :copyright: — A  🌎 [conditionally free](pvs-studio.com/en/order/open-source-license) for FOSS and individual developers) static analysis of C, C++, C# and Java code. For advertising purposes <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [you can propose a large FOSS project for analysis by PVS employees](https://github.com/viva64/pvs-studio-check-list)). Supports CWE mapping, OWASP ASVS, MISRA, AUTOSAR and SEI CERT coding standards.

- 🌎 [pylama](klen.github.io/pylama/) — Code audit tool for Python and JavaScript. Wraps pycodestyle, pydocstyle, PyFlakes, Mccabe, Pylint, and more

- 🌎 [Qwiet AI](qwiet.ai/) :copyright: — Identify vulnerabilities that are unique to your code base before they reach production. Leverages the Code Property Graph (CPG) to run its analyses concurrently in a single graph of graphs. Automatically finds business logic flaws in dev like hardcoded secrets and logic bombs

- 🌎 [Refactoring Essentials](marketplace.visualstudio.com/items?itemName=SharpDevelopTeam.RefactoringEssentialsforVisualStudio) — The free Visual Studio 2015 extension for C# and VB.NET refactorings, including code best practice analyzers.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [relint](https://github.com/codingjoe/relint)) — A static file linter that allows you to write custom rules using regular expressions (RegEx).

- 🌎 [ReSharper](www.jetbrains.com/resharper) :copyright: — Extends Visual Studio with on-the-fly code inspections for C#, VB.NET, ASP.NET, JavaScript, TypeScript and other technologies.

- <b><code>&nbsp;&nbsp;&nbsp;217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Rev-dep](https://github.com/jayu/rev-dep)) — Dependency analysis and optimization toolkit for modern JavaScript and TypeScript projects. Trace imports, identify circular dependencies, find unused code, clean node modules.

- 🌎 [RIPS](www.ripstech.com) :copyright: — A static source code analyser for vulnerabilities in PHP scripts.

- <b><code>&nbsp;&nbsp;1670⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [Roslyn Analyzers](https://github.com/dotnet/roslyn-analyzers)) — Roslyn-based implementation of FxCop analyzers.

- 🌎 [Roslyn Security Guard](security-code-scan.github.io) — Project that focuses on the identification of potential vulnerabilities such as SQL injection, cross-site scripting (XSS), CSRF, cryptography weaknesses, hardcoded passwords and many more.

- 🌎 [SafeQL](safeql.dev) — Validate and auto-generate TypeScript types from raw SQL queries in PostgreSQL. SafeQL is an ESLint plugin for writing SQL queries in a type-safe way.

- 🌎 [SAST Online](sast.online/) :copyright: — Check the Android Source code thoroughly to uncover and address potential security concerns and vulnerabilities. Static application security testing (Static Code Analysis) tool Online

- **Scrutinizer** :warning: :copyright: — A proprietary code quality checker that can be integrated with GitHub.

- 🌎 [Security Code Scan](security-code-scan.github.io) — Security code analyzer for C# and VB.NET. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc. Integrates into Visual Studio 2015 and newer. Detects various security vulnerability patterns: SQLi, XSS, CSRF, XXE, Open Redirect, etc.

- 🌎 [Semgrep](semgrep.dev) — A fast, open-source, static analysis tool for finding bugs and enforcing code standards at editor, commit, and CI time. Its rules look like the code you already write;  no abstract syntax trees or regex wrestling. Supports 17+ languages.

- 🌎 [Semgrep Supply Chain](semgrep.dev/products/semgrep-supply-chain) :copyright: — Quickly find and remediate high-priority security issues.  Semgrep Supply Chain prioritizes the 2% of vulnerabilities that are reachable from your code.

- 🌎 [Seqra](seqra.dev) — Security-focused static analyzer for Java and Kotlin web applications. Analyzes bytecode with Semgrep-style YAML rules and CodeQL-grade dataflow (with first-class Spring support) to find vulnerabilities that source-only scanners miss.

- **ShiftLeft Scan** :warning: — Scan is a free open-source DevSecOps platform for detecting security issues in source code and dependencies. It supports a broad range of languages and CI/CD pipelines. Note: ShiftLeft rebranded to Qwiet AI in 2023, which was subsequently acquired by Harness in September 2025. This open-source project is no longer maintained.

- **shipshape** :warning: — Static program analysis platform that allows custom analyzers to plug in through a common interface.

- 🌎 [Sigrid](www.softwareimprovementgroup.com/solutions/sigrid-software-assurance-platform/) :copyright: — Sigrid helps you to improve your software by measuring your system's code quality,  and then compares the results against a benchmark of thousands of industry systems to give you concrete advice on areas where you can improve.

- 🌎 [Similarity Tester](dickgrune.com/Programs/similarity_tester/) — A tool that finds similarities between or within files to support you encountering DRY principle violations.

- <b><code>&nbsp;&nbsp;&nbsp;344⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Skylos](https://github.com/duriantaco/skylos)) — Dead code detection, security scanning, secrets detection, and code quality analysis for Python, TypeScript, and Go. Framework-aware analysis with 98% recall. Includes CI/CD GitHub Action, VS Code extension, and MCP server for AI agent integration.

- 🌎 [Snyk Code](snyk.io) :copyright: — Snyk Code finds security vulnerabilities based on AI. Its speed of analysis allow us to analyse your code in real time and deliver results when you hit the save button in your IDE. Supported languages are Java, JavaScript, Python, PHP, C#, Go and TypeScript. Integrations with GitHub, BitBucket and Gitlab. It is free to try and part of the Snyk platform also covering SCA, containers and IaC.

- 🌎 [SonarQube Cloud](sonarcloud.io) :copyright: — SonarQube Cloud enables your team to deliver clean code consistently and efficiently with a code review  tool that easily integrates into the cloud DevOps platforms and extend your CI/CD workflow.  SonarQube Cloud provides a free plan.

- 🌎 [SonarQube for IDE](sonarlint.org) — SonarQube for IDE (formerly SonarLint) is a free IDE extension available for IntelliJ, VS Code, Visual Studio, and Eclipse,  to find and fix coding issues in real-time, flagging issues as you code, just like a spell-checker.  More than a linter, it also delivers rich contextual guidance to help developers understand  why there is an issue, assess the risk, and educate them on how to fix it.

- 🌎 [SonarQube Server](sonarqube.org) — SonarQube empowers development teams with a code quality and security solution that deeply integrates into your enterprise environment; enabling you to deploy clean code consistently and reliably. SonarQube provides a free and open source Community Build.

- 🌎 [Sonatype](www.sonatype.com) :copyright: — Reports known vulnerabilities in common dependencies and recommends updated packages to minimize breaking changes

- 🌎 [Soto Platform](www.hello2morrow.com/products/sotograph) :copyright: — Suite of static analysis tools consisting of the three components Sotoarc (Architecture Analysis), Sotograph (Quality Analysis), and Sotoreport (Quality report). Helps find differences between architecture and implementation, interface violations (e.g. external access of private parts of subsystems, detection of all classes, files, packages and subsystems which are strongly coupled by cyclical relationships and more. The Sotograph product family runs on Windows and Linux. 

- 🌎 [SourceMeter](www.sourcemeter.com/) :copyright: — Static Code Analysis for C/C++, Java, C#, Python, and RPG III and RPG IV versions (including free-form).

- <b><code>&nbsp;&nbsp;&nbsp;497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [sqlvet](https://github.com/houqp/sqlvet)) — Performs static analysis on raw SQL queries in your Go code base to surface potential runtime errors. It checks for SQL syntax error, identifies unsafe queries that could potentially lead to SQL injections makes sure column count matches value count in INSERT statements and validates table- and column names.

- 🌎 [StaticReviewer](securityreviewer.atlassian.net/wiki/spaces/KC/pages/196633/Static+Reviewer) :copyright: — Static Reviewer executes code checks according to the most relevant Secure Coding Standards, OWASP, CWE, CVE, CVSS, MISRA, CERT, for 40+ programming languages, using 1000+ built-in validation rules for Security, Deadcode & Best Practices Available a module for Software Composition Analysis (SCA) to find vulnerabilities in open source and third party libraries.

- **Super-Linter** :warning: — Combination of multiple linters to install as a GitHub Action.

- 🌎 [Svace](www.ispras.ru/en/technologies/svace/) :copyright: — Static code analysis tool for Java,C,C++,C#,Go.

- 🌎 [Synopsys](www.synopsys.com/software-integrity/security-testing/static-analysis-sast.html) :copyright: — A commercial static analysis platform that allows for scanning of multiple languages (C/C++, Android, C#, Java, JS, PHP, Python, Node.JS, Ruby, Fortran, and Swift).

- 🌎 [Teamscale](teamscale.com) :copyright: — Static and dynamic analysis tool supporting more than 25 languages and direct IDE integration. Free hosting for Open Source projects available on request. Free academic licenses available.

- 🌎 [TencentCodeAnalysis](tca.tencent.com/) — Tencent Cloud Code Analysis (TCA for short, code-named CodeDog inside the company early) is a comprehensive platform for code analysis and issue tracking. TCA consist of three components, server, web and client. It integrates of a number of self-developed tools, and also supports dynamic integration of code analysis tools in various programming languages.

- <b><code>&nbsp;&nbsp;5242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;642🍴</code></b> [ThreatMapper](https://github.com/deepfence/ThreatMapper)) — Vulnerability Scanner and Risk Evaluation for containers, serverless and hosts at runtime. ThreatMapper generates runtime BOMs from dependencies and operating system packages, matches against multiple threat feeds, scans for unprotected secrets, and scores issues based on severity and risk-of-exploit.

- <b><code>&nbsp;&nbsp;&nbsp;435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [todocheck](https://github.com/preslavmihaylov/todocheck)) — Linter for integrating annotated TODOs with your issue trackers

- <b><code>&nbsp;33423⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [trivy](https://github.com/aquasecurity/trivy)) — A Simple and Comprehensive Vulnerability Scanner for Containers and other Artifacts, Suitable for CI. Trivy detects vulnerabilities of OS packages (Alpine, RHEL, CentOS, etc.) and application dependencies (Bundler, Composer, npm, yarn, etc.). Checks containers and filesystems.


- 🌎 [trunk](trunk.io) :copyright: — Modern repositories include many technologies, each with its own set of linters. With 30+ linters and counting, Trunk makes it dead-simple to identify, install, configure, and run the right linters, static analyzers, and formatters for all your repos.

- <b><code>&nbsp;&nbsp;2116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;603🍴</code></b> [TscanCode](https://github.com/Tencent/TscanCode)) — A fast and accurate static analysis solution for C/C++, C#, Lua codes provided by Tencent. Using GPLv3 license.

- <b><code>&nbsp;&nbsp;1627⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Undebt](https://github.com/Yelp/undebt)) — Language-independent tool for massive, automatic, programmable refactoring based on simple pattern definitions.

- 🌎 [Understand](www.scitools.com) :copyright: — Code visualization tool that provides code analysis, standards testing, metrics, graphing, dependency analysis and more for Ada, VHDL, and others.

- 🌎 [Unibeautify](unibeautify.com) — Universal code beautifier with a GitHub app. Supports HTML, CSS, JavaScript, TypeScript, JSX, Vue, C++, Go, Objective-C, Java, Python, PHP, GraphQL, Markdown, and more.

- 🌎 [Upsource](www.jetbrains.com/upsource) :copyright: — Code review tool with static code analysis and code-aware navigation for Java, PHP, JavaScript and Kotlin.

- 🌎 [Veracode](www.veracode.com/security/static-code-analysis) :copyright: — Find flaws in binaries and bytecode without requiring source. Support all major programming languages: Java, .NET, JavaScript, Swift, Objective-C, C, C++ and more.

- <b><code>&nbsp;&nbsp;&nbsp;837⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;240🍴</code></b> [WALA](https://github.com/wala/WALA)) — Static analysis capabilities for Java bytecode and related languages and for JavaScript.

- <b><code>&nbsp;&nbsp;2483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;143🍴</code></b> [weggli](https://github.com/googleprojectzero/weggli)) — A fast and robust semantic search tool for C and C++ codebases. It is designed to help security researchers identify interesting functionality in large codebases.

- 🌎 [WhiteHat Application Security Platform](source.whitehatsec.com/help/sentinel/sast-service-detail.html) :copyright: — WhiteHat Scout (for Developers) combined with WhiteHat Sentinel Source (for Operations) supporting WhiteHat Top 40 and OWASP Top 10.

- **Wotan** :warning: — Pluggable TypeScript and JavaScript linter.

- 🌎 [XCode](developer.apple.com/xcode) :copyright: — XCode provides a pretty decent UI for 🌎 [Clang's](clang-analyzer.llvm.org/xcode.html) static code analyzer (C/C++, Obj-C).

- 🌎 [Xygeni](xygeni.io/) :copyright: — Xygeni is a comprehensive Software Supply Chain Security platform. It provides Advanced SAST with AI-powered remediation, Software Composition Analysis (SCA) with real-time malware detection, Infrastructure as Code (IaC) scanning, and Secrets detection to ensure end-to-end code security.


## Other



<a name="dotenv" />
<h2>.env</h2>


- 🌎 [GitGuardian ggshield](www.gitguardian.com/ggshield) — ggshield is a CLI application that runs in your local environment  or in a CI environment to help you detect more than 350+ types of secrets,  as well as other potential security vulnerabilities or policy breaks affecting your codebase.


<a name="ansible" />
<h2>Ansible</h2>


- 🌎 [kics](kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible

- 🌎 [Steampunk Spotter](steampunk.si/spotter/) :copyright: — Ansible Playbook Scanning Tool that analyzes and offers recommendations for your playbooks.


<a name="archive" />
<h2>Archive</h2>


- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [alquitran](https://github.com/ferivoz/alquitran)) — Inspects tar archives and tries to spot portability issues in regard  to POSIX 2017 pax specification and common tar implementations.
This project is intended to be used by maintainers of projects who want to offer portable source code archives for as many systems as possible. Checking tar archives with alquitran before publishing them should help spotting issues before they reach distributors and users.

- **packj** :warning: — Packj (pronounced package) is a command line (CLI) tool to vet open-source software packages for "risky" attributes that make them vulnerable to supply chain attacks. This is the tool behind our large-scale security analysis platform Packj.dev that continuously vets packages and provides free reports.

- **pure** :warning: — Pure is a static analysis file format checker that checks ZIP files for dangerous compression ratios, spec deviations, malicious archive signatures, mismatching local and central directory headers, ambiguous UTF-8 filenames, directory and symlink traversals, invalid MS-DOS dates, overlapping headers, overflow, underflow,  sparseness, accidental buffer bleeds etc.


<a name="arm" />
<h2>Azure Resource Manager</h2>


- 🌎 [AzSK](azsk.azurewebsites.net/) — Secure DevOps kit for Azure (AzSK) provides security IntelliSense, Security Verification Tests (SVTs), CICD scan vulnerabilities, compliance issues, and infrastructure misconfiguration in your infrastructure-as-code. Supports Azure via ARM.


<a name="binary" />
<h2>Binaries</h2>


- <b><code>&nbsp;&nbsp;8559⭐</code></b> <b><code>&nbsp;&nbsp;1155🍴</code></b> [angr](https://github.com/angr/angr)) — Binary code analysis tool that also supports symbolic execution.

- <b><code>&nbsp;&nbsp;&nbsp;571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [binbloom](https://github.com/quarkslab/binbloom)) — Analyzes a raw binary firmware and determines features like endianness or the loading address.  The tool is compatible with all architectures.
Loading address: binbloom can parse a raw binary firmware and determine its loading address. Endianness: binbloom can use heuristics to determine the endianness of a firmware. UDS Database: binbloom can parse a raw binary firmware and check if it contains an array containing UDS command IDs.

- <b><code>&nbsp;&nbsp;&nbsp;842⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [BinSkim](https://github.com/Microsoft/binskim)) — A binary static analysis tool that provides security and correctness results for Windows portable executables.

- 🌎 [Black Duck](www.blackducksoftware.com) :copyright: — Tool to analyze source code and binaries for reusable code, necessary licenses and potential security aspects.

- <b><code>&nbsp;&nbsp;5399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;375🍴</code></b> [bloaty](https://github.com/google/bloaty)) — Ever wondered what's making your binary big? Bloaty McBloatface will show you a size profile of the binary so you can understand what's taking up space inside. Bloaty performs a deep analysis of the binary. Using custom ELF, DWARF, and Mach-O parsers,  Bloaty aims to accurately attribute every byte of the binary to the symbol or compileunit that produced it.  It will even disassemble the binary looking for references to anonymous data. F

- **cargo-bloat** :warning: — Find out what takes most of the space in your executable. supports ELF (Linux, BSD), Mach-O (macOS) and PE (Windows) binaries.

- <b><code>&nbsp;&nbsp;1327⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [cwe_checker](https://github.com/fkie-cad/cwe_checker)) — cwe_checker finds vulnerable patterns in binary executables.

- 🌎 [Ghidra](ghidra-sre.org) — A software reverse engineering (SRE) suite of tools developed by NSA's Research Directorate in support of the Cybersecurity mission

- 🌎 [Hopper](www.hopperapp.com/) :copyright: — macOS and Linux reverse engineering tool that lets you disassemble, decompile and debug applications. Hopper displays the code using different representations, e.g. the Control Flow Graph, and the pseudo-code of a procedure. Supports Apple Silicon.

- 🌎 [IDA Free](www.hex-rays.com/products/ida/support/download_freeware) :copyright: — Binary code analysis tool.

- <b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Jakstab](https://github.com/jkinder/jakstab)) — Jakstab is an Abstract Interpretation-based, integrated disassembly and static analysis framework for designing analyses on executables and recovering reliable control flow graphs.

- 🌎 [JEB Decompiler](www.pnfsoftware.com/) :copyright: — Decompile and debug binary code. Break down and analyze document files. Android Dalvik, MIPS, ARM, Intel x86, Java, WebAssembly & Ethereum Decompilers.

- 🌎 [Malcat](malcat.fr/) :copyright: — Hexadecimal editor and disassembler for malware analysis and binary file inspection. Supports over 50 file formats and multiple CPU architectures (x86/x64, MIPS, .NET, Python, VB p-code). Features rapid analysis, embedded file extraction, Yara signature scanning, anomaly detection, and Python scripting. Designed for malware analysts, SOC operators, incident responders, and CTF players.

- <b><code>&nbsp;&nbsp;1112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [Manalyze](https://github.com/JusticeRage/Manalyze)) — A static analyzer, which checks portable executables for malicious content.

- **mcsema** :warning: — Framework for lifting x86, amd64, aarch64, sparc32, and sparc64 program binaries to LLVM bitcode. It translates ("lifts") executable binaries from native machine code to LLVM bitcode, which is very useful for performing program analysis methods.

- <b><code>&nbsp;&nbsp;&nbsp;569⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [Nauz File Detector](https://github.com/horsicq/Nauz-File-Detector)) — Static Linker/Compiler/Tool detector for Windows, Linux and MacOS.

- 🌎 [rhabdomancer](crates.io/crates/rhabdomancer) — IDA Pro headless plugin that locates calls to potentially insecure API functions in a binary file.

- <b><code>&nbsp;&nbsp;&nbsp;814⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [rust-audit](https://github.com/Shnatsel/rust-audit)) — Audit Rust binaries for known bugs or security vulnerabilities. This works by embedding data about the dependency tree (Cargo.lock) in JSON format into a dedicated linker section of the compiled executable.

- <b><code>&nbsp;&nbsp;1427⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Twiggy](https://github.com/rustwasm/twiggy)) — Analyzes a binary's call graph to profile code size. The goal is to slim down wasm binary size.

- <b><code>&nbsp;&nbsp;&nbsp;391⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [VMware chap](https://github.com/vmware/chap)) — chap analyzes un-instrumented ELF core files for leaks, memory growth, and corruption.  It is sufficiently reliable that it can be used in automation to catch leaks before  they are committed. As an interactive tool, it helps explain memory growth,  can identify some forms of corruption, and supplements a debugger  by giving the status of various memory locations. 

- 🌎 [zydis](zydis.re) — Fast and lightweight x86/x86-64 disassembler library


<a name="buildtool" />
<h2>Build tools</h2>


- <b><code>&nbsp;&nbsp;1178⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [checkmake](https://github.com/mrtazz/checkmake)) — Linter / Analyzer for Makefiles.

- 🌎 [portlint](www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) — A verifier for FreeBSD and DragonFlyBSD port directories.


<a name="css" />
<h2>CSS/SASS/SCSS</h2>


- 🌎 [CSS Stats](cssstats.com) — Potentially interesting stats on stylesheets.

- <b><code>&nbsp;&nbsp;3326⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;450🍴</code></b> [CSScomb](https://github.com/csscomb/csscomb.js)) — A coding style formatter for CSS. Supports own configurations to make style sheets beautiful and consistent.

- [CSSLint](http://csslint.net) — Does basic syntax checking and finds problematic patterns or signs of inefficiency.

- 🌎 [GraphMyCSS.com](graphmycss.com) — CSS Specificity Graph Generator.

- 🌎 [Nu Html Checker](validator.github.io/validator/) — Helps you catch problems in your HTML/CSS/SVG

- **Parker** :warning: — Stylesheet analysis tool.

- 🌎 [PostCSS](postcss.org) — A tool for transforming styles with JS plugins. These plugins can lint your CSS, support variables and mixins, transpile future CSS syntax, inline images, and more.

- 🌎 [Project Wallace CSS Analyzer](www.projectwallace.com) — Analytics for CSS, part of 🌎 [Project Wallace](www.projectwallace.com).

- **sass-lint** :warning: — A Node-only Sass linter for both sass and scss syntax.

- **scsslint** :warning: — Linter for SCSS files.

- <b><code>&nbsp;&nbsp;&nbsp;701⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Specificity Graph](https://github.com/pocketjoso/specificity-graph)) — CSS Specificity Graph Generator.

- [Stylelint](http://stylelint.io) — Linter for SCSS/CSS files.


<a name="configfile" />
<h2>Config Files</h2>


- 🌎 [dotenv-linter](dotenv-linter.readthedocs.io/en/latest) — Linting dotenv files like a charm.

- 🌎 [dotenv-linter (Rust)](dotenv-linter.github.io/#/) — Lightning-fast linter for .env files. Written in Rust

- <b><code>&nbsp;&nbsp;8546⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;447🍴</code></b> [gixy](https://github.com/yandex/gixy)) — A tool to analyze Nginx configuration. The main goal is to prevent misconfiguration and automate flaw detection.


<a name="configmanagement" />
<h2>Configuration Management</h2>


- 🌎 [ansible-lint](ansible.readthedocs.io/projects/lint/) — Checks playbooks for practices and behaviour that could potentially be improved.

- <b><code>&nbsp;&nbsp;1371⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;195🍴</code></b> [AWS CloudFormation Guard](https://github.com/aws-cloudformation/cloudformation-guard)) — Check local CloudFormation templates against policy-as-code rules  and generate rules from existing templates.

- 🌎 [AzSK](azsk.azurewebsites.net/) — Secure DevOps kit for Azure (AzSK) provides security IntelliSense, Security Verification Tests (SVTs), CICD scan vulnerabilities, compliance issues, and infrastructure misconfiguration in your infrastructure-as-code. Supports Azure via ARM.

- <b><code>&nbsp;&nbsp;2610⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;624🍴</code></b> [cfn-lint](https://github.com/awslabs/cfn-python-lint)) — AWS Labs CloudFormation linter.

- <b><code>&nbsp;&nbsp;1305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;208🍴</code></b> [cfn_nag](https://github.com/stelligent/cfn_nag)) — A linter for AWS CloudFormation templates.

- 🌎 [checkov](www.checkov.io) — Static analysis tool for Terraform files (tf>=v0.12), preventing cloud misconfigs at build time.

- 🌎 [cookstyle](docs.chef.io/cookstyle.html) — Cookstyle is a linting tool based on the RuboCop Ruby linting tool for Chef cookbooks.

- [foodcritic](http://www.foodcritic.io) — A lint tool that checks Chef cookbooks for common problems.

- 🌎 [kics](kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint)) — Tool to check the validity of Puppet metadata.json files.

- **Puppet Lint** :warning: — Check that your Puppet manifests conform to the style guide.

- 🌎 [Steampunk Spotter](steampunk.si/spotter/) :copyright: — Ansible Playbook Scanning Tool that analyzes and offers recommendations for your playbooks.

- 🌎 [terraform-compliance](terraform-compliance.com) — A lightweight, compliance- and security focused, BDD test framework against Terraform.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [terrascan](https://github.com/cesar-rodriguez/terrascan)) — Collection of security and best practice tests for static code analysis of Terraform templates.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [tflint](https://github.com/wata727/tflint)) — A Terraform linter for detecting errors that can not be detected by `terraform plan`.

- <b><code>&nbsp;&nbsp;6966⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;554🍴</code></b> [tfsec](https://github.com/tfsec/tfsec)) — Terraform static analysis tool that prevents potential security issues by checking cloud misconfigurations at build time and directly integrates with the HCL parser for better results. Checks for violations of AWS, Azure and GCP security best practice recommendations.


<a name="container" />
<h2>Containers</h2>


- 🌎 [anchore](anchore.io) — Discover, analyze, and certify container images. A service that analyzes Docker images and applies user-defined acceptance policies  to allow automated container image validation and certification 

- <b><code>&nbsp;10946⭐</code></b> <b><code>&nbsp;&nbsp;1197🍴</code></b> [clair](https://github.com/coreos/clair)) — Vulnerability Static Analysis for Containers.

- 🌎 [Code Pathfinder](codepathfinder.dev) — An open-source security suite aiming to combine structural code analysis with  AI-powered vulnerability detection. Built for advanced structural search, derive  insights, find vulnerabilities in code.

- **collector** :warning: — Run arbitrary scripts inside containers, and gather useful information.

- **dagda** :warning: — Perform static analysis of known vulnerabilities in docker images/containers.

- **Docker Label Inspector** :warning: — Lint and validate Dockerfile labels.

- **Dockle** :warning: — Container Image Linter for Security helping build the Best-Practice Docker Image. Scans Docker images for security vulnerabilities and CIS Benchmark compliance. Checks for secrets, credential exposure, and security best practices. Provides multiple severity levels (FATAL, WARN, INFO) and supports various output formats for CI/CD integration.

- 🌎 [GitGuardian ggshield](www.gitguardian.com/ggshield) — ggshield is a CLI application that runs in your local environment  or in a CI environment to help you detect more than 350+ types of secrets,  as well as other potential security vulnerabilities or policy breaks affecting your codebase.

- <b><code>&nbsp;11769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;757🍴</code></b> [Grype](https://github.com/anchore/grype)) — Vulnerability scanner for container images and filesystems. Developed by Anchore, it scans container images, directories, and archives for known vulnerabilities. Supports multiple image formats, SBOM integration, and VEX (Vulnerability Exploitability eXchange) for accurate vulnerability assessment. Works with various vulnerability databases and provides detailed reporting.

- <b><code>&nbsp;12011⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;488🍴</code></b> [Haskell Dockerfile Linter](https://github.com/lukasmartinelli/hadolint)) — A smarter Dockerfile linter that helps you build best practice Docker images.

- 🌎 [kics](kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible

- <b><code>&nbsp;&nbsp;&nbsp;737⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [krane](https://github.com/appvia/krane)) — Krane is a simple Kubernetes RBAC static analysis tool.
It identifies potential security risks in K8s RBAC design and makes suggestions on how to mitigate them. Krane dashboard presents current RBAC security posture and lets you navigate through its definition.

- 🌎 [OpenSCAP](www.open-scap.org/) — Suite of automated audit tools to examine the configuration and  known vulnerabilities following the NIST-certified Security  Content Automation Protocol (SCAP).

- 🌎 [Qualys Container Security](www.qualys.com/apps/container-security) :copyright: — Container native application protection to provide visibility and control of containerized applications.

- 🌎 [sysdig](sysdig.com/) :copyright: — A secure DevOps platform for cloud and container forensics. Built on an open source stack, Sysdig provides Docker image scanning and created Falco, the open standard for runtime threat detection for containers, Kubernetes and cloud. 

- 🌎 [Vuls](vuls.io/) — Agent-less Linux vulnerability scanner based on information from NVD, OVAL, etc.  It has some container image support, although is not a container specific tool.


<a name="ci" />
<h2>Continuous Integration</h2>


- 🌎 [actionlint](rhysd.github.io/actionlint) — Static checker for GitHub Actions workflow files. Provides an online version.

- 🌎 [AzSK](azsk.azurewebsites.net/) — Secure DevOps kit for Azure (AzSK) provides security IntelliSense, Security Verification Tests (SVTs), CICD scan vulnerabilities, compliance issues, and infrastructure misconfiguration in your infrastructure-as-code. Supports Azure via ARM.

- 🌎 [Code Climate](codeclimate.com) — The open and extensible static analysis platform, for everyone.

- 🌎 [Code Pathfinder](codepathfinder.dev) — An open-source security suite aiming to combine structural code analysis with  AI-powered vulnerability detection. Built for advanced structural search, derive  insights, find vulnerabilities in code.

- 🌎 [Codecov](about.codecov.io/) :copyright: — Codecov is a company that provides code coverage tools for developers and engineering leaders  to gain visibility into their code coverage.
They offer flexible and unified reporting, seamless coverage insights, and robust coverage controls. Codecov supports over 20 languages and is CI/CD agnostic. Over 29,000 organizations and 1 million developers use Codecov. Codecov has recently joined Sentry.

- 🌎 [CodeRabbit](coderabbit.ai) :copyright: — AI-powered code review tool that helps developers write better code faster.  CodeRabbit provides automated code reviews,  identifies security vulnerabilities, and suggests code improvements.  It integrates with GitHub and GitLab.

- <b><code>&nbsp;&nbsp;&nbsp;604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [composer-dependency-analyser](https://github.com/shipmonk-rnd/composer-dependency-analyser)) — Fast detection of composer dependency issues.

* 💪 Powerful: Detects unused, shadow and misplaced composer dependencies
* ⚡ Performant: Scans 15 000 files in 2s!
* ⚙️ Configurable: Fine-grained ignores via PHP config
* 🕸️ Lightweight: No composer dependencies
* 🍰 Easy-to-use: No config needed for first try
* ✨ Compatible: PHP >= 7.2


- 🌎 [Diffblue](www.diffblue.com/) :copyright: — Diffblue is a software company that provides AI-powered code analysis and testing solutions for software development teams.
Its technology helps developers automate testing, find bugs, and reduce manual labor in their software development processes. The company's main product, Diffblue Cover, uses AI to generate and run unit tests for Java code, helping to catch errors and improve code quality.

- 🌎 [exakat](www.exakat.io) — An automated code reviewing engine for PHP.

- 🌎 [GitGuardian ggshield](www.gitguardian.com/ggshield) — ggshield is a CLI application that runs in your local environment  or in a CI environment to help you detect more than 350+ types of secrets,  as well as other potential security vulnerabilities or policy breaks affecting your codebase.

- 🌎 [Goblint](goblint.in.tum.de) — A static analyzer for the analysis of multi-threaded C programs. Its primary focus is the  detection of data races, but it also reports other runtime errors, such as buffer overflows and null-pointer dereferences.

- 🌎 [PullRequest](www.hackerone.com/product/code) :copyright: — Code review as a service with built-in static analysis.  Increase velocity and reduce technical debt through quality code review by expert engineers backed by best-in-class automation.

- **quality** :warning: — Runs quality checks on your code using community tools, and makes sure your numbers don't get any worse over time.

- **QuantifiedCode** :warning: — Automated code review & repair. It helps you to keep track of issues and metrics in your software projects, and can be easily extended to support new types of analyses.

- <b><code>&nbsp;&nbsp;&nbsp;522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst)) — Identifies and prioritizes God Classes and Highly Coupled classes in Java codebases you should refactor first.

- <b><code>&nbsp;&nbsp;9155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;480🍴</code></b> [Reviewdog](https://github.com/haya14busa/reviewdog)) — A tool for posting review comments from any linter in any code hosting service.

- 🌎 [Symfony Insight](insight.symfony.com/) :copyright: — Detect security risks, find bugs and provide actionable metrics for PHP projects.

- 🌎 [TangleGuard](tangleguard.com/) :copyright: — Helps you understand and maintain a scalable software architecture. To do so, it generates a interactive, nested dependency graph out of the source code. You can choose the level of details and get the portion of your codebase that matters to you.

- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Violations Lib](https://github.com/tomasbjerre/violations-lib)) — Java library for parsing report files from static code analysis. Used by a bunch of Jenkins, Maven and Gradle plugins.


<a name="deno" />
<h2>Deno</h2>


- <b><code>&nbsp;&nbsp;1581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [deno_lint](https://github.com/denoland/deno_lint)) — Official linter for Deno.


<a name="dockerfile" />
<h2>Dockerfile</h2>


- 🌎 [Cloud (IaC) Security for JetBrains IDEs](plugins.jetbrains.com/plugin/25413-cloud-iac-security) — Cloud (IaC) Security plugin for JetBrains IDEs. Performs real-time inspections of Docker & Kubernetes IaC with 50+ rules based on Docker image/build security best practices, Kubernetes Pod Security Standards, and NSA/CISA Kubernetes Hardening Guidance.

- 🌎 [Code Pathfinder](codepathfinder.dev) — An open-source security suite aiming to combine structural code analysis with  AI-powered vulnerability detection. Built for advanced structural search, derive  insights, find vulnerabilities in code.

- **Dockle** :warning: — Container Image Linter for Security helping build the Best-Practice Docker Image. Scans Docker images for security vulnerabilities and CIS Benchmark compliance. Checks for secrets, credential exposure, and security best practices. Provides multiple severity levels (FATAL, WARN, INFO) and supports various output formats for CI/CD integration.


<a name="embedded" />
<h2>Embedded</h2>


- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [oelint-adv](https://github.com/priv-kweihmann/oelint-adv)) — Linter for bitbake recipes used in open-embedded and YOCTO


<a name="erb" />
<h2>Embedded Ruby (a.k.a. ERB, eRuby)</h2>


- <b><code>&nbsp;&nbsp;&nbsp;742⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [ERB Lint](https://github.com/Shopify/erb-lint)) — Lint your ERB or HTML files

- <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [ERB::Formatter](https://github.com/nebulab/erb-formatter)) — Format ERB files with speed and precision.

- <b><code>&nbsp;&nbsp;&nbsp;371⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)) — A normaliser/beautifier for HTML that also understands embedded Ruby. Ideal for tidying up Rails templates.


<a name="gherkin" />
<h2>Gherkin</h2>


- <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [gherkin-lint](https://github.com/vsiakka/gherkin-lint)) — A linter for the Gherkin-Syntax written in Javascript.


<a name="html" />
<h2>HTML</h2>


- <b><code>&nbsp;&nbsp;1779⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;260🍴</code></b> [Angular ESLint](https://github.com/angular-eslint/angular-eslint#readme)) — Linter for Angular projects

- 🌎 [axe-core](www.deque.com/axe/) — Accessibility engine for automated Web UI testing. Tests HTML against WCAG 2.0, 2.1, and 2.2 guidelines. Used by Google Lighthouse, Microsoft Accessibility Insights, and thousands of organizations worldwide.

- **Bootlint** :warning: — An HTML linter for Bootstrap projects.

- <b><code>&nbsp;&nbsp;&nbsp;742⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [ERB Lint](https://github.com/Shopify/erb-lint)) — Lint your ERB or HTML files

- <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [ERB::Formatter](https://github.com/nebulab/erb-formatter)) — Format ERB files with speed and precision.

- **grunt-bootlint** :warning: — A Grunt wrapper for <b><code>&nbsp;&nbsp;2389⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [Bootlint](https://github.com/twbs/bootlint)), the HTML linter for Bootstrap projects.

- **gulp-bootlint** :warning: — A gulp wrapper for <b><code>&nbsp;&nbsp;2389⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;309🍴</code></b> [Bootlint](https://github.com/twbs/bootlint)), the HTML linter for Bootstrap projects.

- **HTML Inspector** :warning: — HTML Inspector is a code quality tool to help you and your team write better markup.

- [HTML Tidy](http://www.html-tidy.org) — Corrects and cleans up HTML and XML documents by fixing markup errors and upgrading legacy code to modern standards.

- 🌎 [HTML-Validate](html-validate.org/) — Offline HTML5 validator.

- <b><code>&nbsp;&nbsp;&nbsp;371⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [htmlbeautifier](https://github.com/threedaymonk/htmlbeautifier)) — A normaliser/beautifier for HTML that also understands embedded Ruby. Ideal for tidying up Rails templates.

- 🌎 [HTMLHint](htmlhint.com) — A Static Code Analysis Tool for HTML.

- 🌎 [Nu Html Checker](validator.github.io/validator/) — Helps you catch problems in your HTML/CSS/SVG

- 🌎 [Pa11y](pa11y.org/) — Automated accessibility testing tool that runs HTML CodeSniffer or axe-core from the command line. Supports CI/CD integration, multiple reporters, and testing against WCAG 2.1 AA standards.

- <b><code>&nbsp;&nbsp;&nbsp;436⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [Polymer-analyzer](https://github.com/Polymer/tools/tree/master/packages/analyzer)) — A static analysis framework for Web Components.


<a name="json" />
<h2>JSON</h2>


- 🌎 [jsonlint](jsonlint.com/) — A JSON parser and validator with a CLI. Standalone version of jsonlint.com

- 🌎 [Spectral](stoplight.io/open-source/spectral) — A flexible JSON/YAML linter, with out-of-the-box support for OpenAPI v2/v3 and AsyncAPI v2.


<a name="kubernetes" />
<h2>Kubernetes</h2>


- <b><code>&nbsp;&nbsp;1620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;246🍴</code></b> [chart-testing](https://github.com/helm/chart-testing)) — ct is the tool for testing Helm charts.  It is meant to be used for linting and testing pull requests.  It automatically detects charts changed against the target branch.

- 🌎 [Cloud (IaC) Security for JetBrains IDEs](plugins.jetbrains.com/plugin/25413-cloud-iac-security) — Cloud (IaC) Security plugin for JetBrains IDEs. Performs real-time inspections of Docker & Kubernetes IaC with 50+ rules based on Docker image/build security best practices, Kubernetes Pod Security Standards, and NSA/CISA Kubernetes Hardening Guidance.

- <b><code>&nbsp;&nbsp;&nbsp;586⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [clusterlint](https://github.com/digitalocean/clusterlint)) — Clusterlint queries live Kubernetes clusters for resources, executes common and  platform specific checks against these resources and provides actionable feedback to cluster operators.  It is a non invasive tool that is run externally. Clusterlint does not alter the resource configurations.

- 🌎 [Datree](datree.io/) — A CLI tool to prevent Kubernetes misconfigurations by ensuring that manifests and Helm charts follow best practices as well as your organization’s policies

- 🌎 [kics](kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [klint](https://github.com/uswitch/klint)) — A tool that listens to changes in Kubernetes resources and runs linting rules against them. Identify and debug erroneous objects and nudge objects in line with the policies as both change over time. Klint helps us encode checks and proactively alert teams when they need to take action.

- <b><code>&nbsp;&nbsp;&nbsp;737⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [krane](https://github.com/appvia/krane)) — Krane is a simple Kubernetes RBAC static analysis tool.
It identifies potential security risks in K8s RBAC design and makes suggestions on how to mitigate them. Krane dashboard presents current RBAC security posture and lets you navigate through its definition.

- **kube-hunter** :warning: — Hunt for security weaknesses in Kubernetes clusters.

- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [kube-lint](https://github.com/viglesiasce/kube-lint)) — A linter for Kubernetes resources with a customizable rule set. You define a list of rules that you would like to validate against your  resources and kube-lint will evaluate those rules against them.

- <b><code>&nbsp;&nbsp;3418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;259🍴</code></b> [kube-linter](https://github.com/stackrox/kube-linter)) — KubeLinter is a static analysis tool that checks Kubernetes YAML files  and Helm charts to ensure the applications represented in them adhere to best practices.

- 🌎 [kube-score](kube-score.com) — Static code analysis of your Kubernetes object definitions.

- <b><code>&nbsp;&nbsp;2965⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;162🍴</code></b> [kubeconform](https://github.com/yannh/kubeconform)) — A fast Kubernetes manifests validator with support for custom resources.

It is inspired by, contains code from and is designed to stay close to 🌎 [Kubeval](analysis-tools.dev/tool/kubeval),
but with the following improvements:
* high performance: will validate & download manifests over multiple routines, caching downloaded files in memory
* configurable list of remote, or local schemas locations, enabling validating Kubernetes custom resources (CRDs) and offline validation capabilities
* uses by default a self-updating fork of the schemas registry maintained by the kubernetes-json-schema project - which guarantees up-to-date schemas for all recent versions of Kubernetes.


- <b><code>&nbsp;&nbsp;3418⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;259🍴</code></b> [KubeLinter](https://github.com/stackrox/kube-linter)) — KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts to ensure the applications represented in them adhere to best practices.

- **kubeval** :warning: — Validates your Kubernetes configuration files and supports multiple Kubernetes versions.


<a name="latex" />
<h2>LaTeX</h2>


- **ChkTeX** :warning: — A linter for LaTex which catches some typographic errors LaTeX oversees.

- 🌎 [lacheck](www.ctan.org/pkg/lacheck) — A tool for finding common mistakes in LaTeX documents.

- 🌎 [TeXLab](texlab.netlify.app) — A Language Server Protocol implementation for TeX/LaTeX, including lint capabilities.


<a name="laravel" />
<h2>Laravel</h2>


- **Enlightn** :warning: — A static and dynamic analysis tool for Laravel applications that provides recommendations to improve the performance, security and code reliability of Laravel apps. Contains 120 automated checks.

- <b><code>&nbsp;&nbsp;6335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;490🍴</code></b> [larastan](https://github.com/larastan/larastan)) — Adds static analysis to Laravel improving developer productivity and code quality. It is a wrapper around PHPStan.


<a name="make" />
<h2>Makefiles</h2>


- <b><code>&nbsp;&nbsp;1178⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [checkmake](https://github.com/mrtazz/checkmake)) — Linter / Analyzer for Makefiles.

- 🌎 [mbake](pypi.org/project/mbake/) — mbake is a Makefile formatter and linter. It only took 50 years!

- 🌎 [portlint](www.freebsd.org/cgi/man.cgi?query=portlint&sektion=1&manpath=FreeBSD+8.1-RELEASE+and+Ports) — A verifier for FreeBSD and DragonFlyBSD port directories.


<a name="markdown" />
<h2>Markdown</h2>


- <b><code>&nbsp;&nbsp;5947⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;886🍴</code></b> [markdownlint](https://github.com/DavidAnson/markdownlint)) — Node.js -based style checker and lint tool for Markdown/CommonMark files.

- 🌎 [mdformat](mdformat.rtfd.io) — CommonMark compliant Markdown formatter

- <b><code>&nbsp;&nbsp;2020⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;239🍴</code></b> [mdl](https://github.com/mivok/markdownlint)) — A tool to check Markdown files and flag style issues.

- <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [mdsf](https://github.com/hougesen/mdsf)) — Format markdown code blocks using your favorite code formatters.

- 🌎 [remark-lint](remark.js.org) — Pluggable Markdown code style linter written in JavaScript.

- 🌎 [textlint](textlint.github.io/) — textlint is an open source text linting utility written in JavaScript.


<a name="meta" />
<h2>Metalinter</h2>


- **ciocheck** :warning: — Linter, formatter and test suite helper. As a linter, it is a wrapper around `pep8`, `pydocstyle`, `flake8`, and `pylint`.

- <b><code>&nbsp;&nbsp;3771⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;341🍴</code></b> [flake8](https://github.com/PyCQA/flake8)) — A wrapper around `pyflakes`, `pycodestyle` and `mccabe`.

- 🌎 [flakeheaven](pypi.org/project/flakeheaven/) — flakeheaven is a python linter built around flake8 to enable inheritable and complex toml configuration.

- **Go Meta Linter** :warning: — Concurrently run Go lint tools and normalise their output. Use `golangci-lint` for new projects.

- <b><code>&nbsp;&nbsp;3130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;265🍴</code></b> [goreporter](https://github.com/360EntSecGroup-Skylar/goreporter)) — Concurrently runs many linters and normalises their output to a report.

- **multilint** :warning: — A wrapper around `flake8`, `isort` and `modernize`.

- <b><code>&nbsp;&nbsp;2073⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [prospector](https://github.com/PyCQA/prospector)) — A wrapper around `pylint`, `pep8`, `mccabe` and others.


<a name="mobile" />
<h2>Mobile</h2>


- 🌎 [Android Lint](developer.android.com/studio/write/lint) — Run static analysis on Android projects.

- **android-lint-summary** :warning: — Combines lint errors of multiple projects into one output, check lint results of multiple sub-projects at once.

- <b><code>&nbsp;&nbsp;1235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;318🍴</code></b> [FlowDroid](https://github.com/secure-software-engineering/FlowDroid)) — Static taint analysis tool for Android applications.

- **iblessing** :warning: — iblessing is an iOS security exploiting toolkit. It can be used for reverse engineering, binary analysis and vulnerability mining.

- 🌎 [Mariana Trench](mariana-tren.ch/) — Our security focused static analysis tool for Android and Java applications. Mariana Trench analyzes Dalvik bytecode and is built to run fast on large codebases (10s of millions of lines of code). It can find vulnerabilities as code changes, before it ever lands in your repository.

- 🌎 [Oversecured](oversecured.com) :copyright: — Enterprise vulnerability scanner for Android and iOS apps. It allows app owners and developers to secure each new version of a mobile app by integrating Oversecured into the development process.

- **paprika** :warning: — A toolkit to detect some code smells in analyzed Android applications.

- **qark** :warning: — Tool to look for several security related Android application vulnerabilities.

- 🌎 [redex](fbredex.com) — Redex provides a framework for reading, writing, and analyzing .dex files, and a set of optimization passes  that use this framework to improve the bytecode. An APK optimized by Redex should be smaller and faster.


<a name="nix" />
<h2>Nix</h2>


- <b><code>&nbsp;&nbsp;&nbsp;734⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [deadnix](https://github.com/astro/deadnix)) — Scan Nix files for dead code (unused variable bindings)

- <b><code>&nbsp;&nbsp;&nbsp;850⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [statix](https://github.com/nerdypepper/statix)) — Lints and suggestions for the Nix programming language. "statix check" highlights antipatterns in Nix code. "statix fix" can fix several such occurrences.


<a name="nodejs" />
<h2>Node.js</h2>


- <b><code>&nbsp;&nbsp;&nbsp;844⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [lockfile-lint](https://github.com/lirantal/lockfile-lint)) — Lint an npm or yarn lockfile to analyze and detect security issues

- **njsscan** :warning: — A static application testing (SAST) tool that can find insecure code patterns in your node.js applications using simple pattern matcher from libsast and syntax-aware semantic code pattern search tool semgrep.

- **NodeJSScan** :warning: — A static security code scanner for Node.js applications powered by libsast and semgrep that builds on the njsscan cli tool. It features a UI with various dashboards about an application's security status.

- [standard](http://standardjs.com) — An npm module that checks for Javascript Styleguide issues.


<a name="package" />
<h2>Packages</h2>


- <b><code>&nbsp;&nbsp;&nbsp;604⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [composer-dependency-analyser](https://github.com/shipmonk-rnd/composer-dependency-analyser)) — Fast detection of composer dependency issues.

* 💪 Powerful: Detects unused, shadow and misplaced composer dependencies
* ⚡ Performant: Scans 15 000 files in 2s!
* ⚙️ Configurable: Fine-grained ignores via PHP config
* 🕸️ Lightweight: No composer dependencies
* 🍰 Easy-to-use: No config needed for first try
* ✨ Compatible: PHP >= 7.2


- 🌎 [lintian](wiki.debian.org/Lintian) — Static analysis tool for Debian packages.

- <b><code>&nbsp;&nbsp;&nbsp;162⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [rpmlint](https://github.com/rpm-software-management/rpmlint)) — Tool for checking common errors in rpm packages.


<a name="prometheus" />
<h2>Prometheus</h2>


- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [promformat](https://github.com/facetoe/promformat)) — Promformat is a PromQL formatter written in Python.

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [promval](https://github.com/facetoe/promval)) — PromQL validator written in Python. It can be used to validate that PromQL expressions are written as expected.


<a name="protobuf" />
<h2>Protocol Buffers</h2>


- 🌎 [buf](buf.build) — Provides a CLI linter that enforces good API design choices and structure

- <b><code>&nbsp;&nbsp;&nbsp;678⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [protolint](https://github.com/yoheimuta/protolint)) — Pluggable linter and fixer to enforce Protocol Buffer style and conventions.


<a name="puppet" />
<h2>Puppet</h2>


- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint)) — Tool to check the validity of Puppet metadata.json files.


<a name="rails" />
<h2>Rails</h2>


- <b><code>&nbsp;&nbsp;1911⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Active Record Doctor](https://github.com/gregnavis/active_record_doctor)) — Identify database issues before they hit production.

- <b><code>&nbsp;&nbsp;7310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;452🍴</code></b> [Bullet](https://github.com/flyerhzm/bullet)) — Help to kill N+1 queries and unused eager loading.

- <b><code>&nbsp;&nbsp;1170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [DatabaseConsistency](https://github.com/djezzzl/database_consistency)) — The tool to avoid various issues due to inconsistencies and inefficiencies between a database schema and application models.

- <b><code>&nbsp;&nbsp;&nbsp;748⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [dawnscanner](https://github.com/thesp0nge/dawnscanner)) — A static analysis security scanner for ruby written web applications. It supports Sinatra, Padrino and Ruby on Rails frameworks.

- <b><code>&nbsp;&nbsp;&nbsp;194⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [ERB::Formatter](https://github.com/nebulab/erb-formatter)) — Format ERB files with speed and precision.

- <b><code>&nbsp;&nbsp;&nbsp;543⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [Skunk](https://github.com/fastruby/skunk)) — A SkunkScore Calculator for Ruby Code -- Find the most complicated code without test coverage!

- <b><code>&nbsp;&nbsp;&nbsp;904⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Traceroute](https://github.com/amatsuda/traceroute)) — A Rake task gem that helps you find the unused routes and controller actions for your Rails 3+ app.


<a name="security" />
<h2>Security/SAST</h2>


- 🌎 [AzSK](azsk.azurewebsites.net/) — Secure DevOps kit for Azure (AzSK) provides security IntelliSense, Security Verification Tests (SVTs), CICD scan vulnerabilities, compliance issues, and infrastructure misconfiguration in your infrastructure-as-code. Supports Azure via ARM.

- 🌎 [brakeman](brakemanscanner.org) — A static analysis security vulnerability scanner for Ruby on Rails applications.

- 🌎 [Cloud (IaC) Security for JetBrains IDEs](plugins.jetbrains.com/plugin/25413-cloud-iac-security) — Cloud (IaC) Security plugin for JetBrains IDEs. Performs real-time inspections of Docker & Kubernetes IaC with 50+ rules based on Docker image/build security best practices, Kubernetes Pod Security Standards, and NSA/CISA Kubernetes Hardening Guidance.

- 🌎 [Code Pathfinder](codepathfinder.dev) — An open-source security suite aiming to combine structural code analysis with  AI-powered vulnerability detection. Built for advanced structural search, derive  insights, find vulnerabilities in code.

- <b><code>&nbsp;&nbsp;&nbsp;361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [Credential Digger](https://github.com/SAP/credential-digger)) — Credential Digger is a GitHub scanning tool that identifies hardcoded credentials (Passwords, API Keys, Secret Keys, Tokens, personal information, etc),  and filtering the false positive data through a machine learning model called 🌎 [Password Model](huggingface.co/SAPOSS/password-model). This scanner is able to detect passwords and non structured tokens with a low false positive rate. 

- 🌎 [Datree](datree.io/) — A CLI tool to prevent Kubernetes misconfigurations by ensuring that manifests and Helm charts follow best practices as well as your organization’s policies

- <b><code>&nbsp;&nbsp;4448⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;540🍴</code></b> [detect-secrets](https://github.com/Yelp/detect-secrets)) — An enterprise friendly way of detecting and preventing secrets in code.
It does this by running periodic diff outputs against heuristically crafted regex statements,  to identify whether any new secret has been committed. This way, it avoids the overhead of digging  through all git history, as well as the need to scan the entire repository every time.

- **Dockle** :warning: — Container Image Linter for Security helping build the Best-Practice Docker Image. Scans Docker images for security vulnerabilities and CIS Benchmark compliance. Checks for secrets, credential exposure, and security best practices. Provides multiple severity levels (FATAL, WARN, INFO) and supports various output formats for CI/CD integration.

- **Enlightn** :warning: — A static and dynamic analysis tool for Laravel applications that provides recommendations to improve the performance, security and code reliability of Laravel apps. Contains 120 automated checks.

- 🌎 [GitGuardian ggshield](www.gitguardian.com/ggshield) — ggshield is a CLI application that runs in your local environment  or in a CI environment to help you detect more than 350+ types of secrets,  as well as other potential security vulnerabilities or policy breaks affecting your codebase.

- <b><code>&nbsp;25510⭐</code></b> <b><code>&nbsp;&nbsp;1966🍴</code></b> [Gitleaks](https://github.com/zricethezav/gitleaks)) — A SAST tool for detecting hardcoded secrets like passwords, api keys, and tokens in git repos.

- <b><code>&nbsp;&nbsp;2166⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [gokart](https://github.com/praetorian-inc/gokart)) — Golang security analysis with a focus on minimizing false positives. It is capable of tracing the source of variables and function arguments  to determine whether input sources are safe.

- <b><code>&nbsp;11769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;757🍴</code></b> [Grype](https://github.com/anchore/grype)) — Vulnerability scanner for container images and filesystems. Developed by Anchore, it scans container images, directories, and archives for known vulnerabilities. Supports multiple image formats, SBOM integration, and VEX (Vulnerability Exploitability eXchange) for accurate vulnerability assessment. Works with various vulnerability databases and provides detailed reporting.

- 🌎 [HasMySecretLeaked](gitguardian.com/hasmysecretleaked) :copyright: — HasMySecretLeaked is a project from GitGuardian that aims to help individual users and organizations search across 20 million exposed secrets to verify if their  developer secrets have leaked on public repositories, gists, and issues on GitHub projects.

- **iblessing** :warning: — iblessing is an iOS security exploiting toolkit. It can be used for reverse engineering, binary analysis and vulnerability mining.

- <b><code>&nbsp;&nbsp;2989⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;142🍴</code></b> [kani](https://github.com/model-checking/kani)) — The Kani Rust Verifier is a bit-precise model checker for Rust. 
Kani is particularly useful for verifying unsafe code blocks in Rust, 
where the "unsafe superpowers" are unchecked by the compiler.
Kani verifies:

* Memory safety (e.g., null pointer dereferences)
* User-specified assertions (i.e., assert!(...))
* The absence of panics (e.g., unwrap() on None values)
* The absence of some types of unexpected behavior (e.g., arithmetic overflows)


- 🌎 [kics](kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible

- **kube-hunter** :warning: — Hunt for security weaknesses in Kubernetes clusters.

- <b><code>&nbsp;&nbsp;&nbsp;844⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [lockfile-lint](https://github.com/lirantal/lockfile-lint)) — Lint an npm or yarn lockfile to analyze and detect security issues

- **LunaSec** :warning: — Open Source AppSec platform that automatically notifies you the next time vulnerabilities like Log4Shell or node-ipc happen. Track your dependencies and builds in a centralized service.

- 🌎 [Malcat](malcat.fr/) :copyright: — Hexadecimal editor and disassembler for malware analysis and binary file inspection. Supports over 50 file formats and multiple CPU architectures (x86/x64, MIPS, .NET, Python, VB p-code). Features rapid analysis, embedded file extraction, Yara signature scanning, anomaly detection, and Python scripting. Designed for malware analysts, SOC operators, incident responders, and CTF players.

- **njsscan** :warning: — A static application testing (SAST) tool that can find insecure code patterns in your node.js applications using simple pattern matcher from libsast and syntax-aware semantic code pattern search tool semgrep.

- **NodeJSScan** :warning: — A static security code scanner for Node.js applications powered by libsast and semgrep that builds on the njsscan cli tool. It features a UI with various dashboards about an application's security status.

- 🌎 [OSV-Scanner](osv.dev/) — Vulnerability scanner written in Go which uses the data provided by OSV.dev. Developed by Google to scan dependencies across multiple languages and package managers for known vulnerabilities. Supports container scanning, license scanning, and guided remediation. Works with lockfiles, SBOMs, and container images to identify security issues.

- 🌎 [Oversecured](oversecured.com) :copyright: — Enterprise vulnerability scanner for Android and iOS apps. It allows app owners and developers to secure each new version of a mobile app by integrating Oversecured into the development process.

- 🌎 [OWASP Noir](owasp-noir.github.io/noir/) — Attack surface detector that identifies endpoints by static analysis.

- <b><code>&nbsp;&nbsp;1217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;87🍴</code></b> [pip-audit](https://github.com/pypa/pip-audit)) — Tool for scanning Python packages for known vulnerabilities. Developed by the Python Packaging Authority (PyPA) and supported by Trail of Bits and Google. Scans Python environments and requirements files to identify vulnerable packages and suggests remediation. Supports GitHub Actions, pre-commit hooks, and multiple vulnerability service integrations.

- 🌎 [PT Application Inspector](www.ptsecurity.com) :copyright: — Identifies code flaws and detects vulnerabilities to prevent web attacks. Demonstrates remote code execution by presenting possible exploits.

- 🌎 [Qualys Container Security](www.qualys.com/apps/container-security) :copyright: — Container native application protection to provide visibility and control of containerized applications.

- **QuantifiedCode** :warning: — Automated code review & repair. It helps you to keep track of issues and metrics in your software projects, and can be easily extended to support new types of analyses.

- 🌎 [Safety](safetycli.com/) — Python dependency vulnerability scanner designed to enhance software supply chain security by detecting packages with known vulnerabilities. Checks Python dependencies against a database of known security vulnerabilities and provides detailed reports. Supports CI/CD integration and multiple output formats.

- <b><code>&nbsp;&nbsp;5316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;616🍴</code></b> [scorecard](https://github.com/ossf/scorecard)) — Security Scorecards - Security health metrics for Open Source

- 🌎 [Steampunk Spotter](steampunk.si/spotter/) :copyright: — Ansible Playbook Scanning Tool that analyzes and offers recommendations for your playbooks.

- 🌎 [Symfony Insight](insight.symfony.com/) :copyright: — Detect security risks, find bugs and provide actionable metrics for PHP projects.

- <b><code>&nbsp;&nbsp;6966⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;554🍴</code></b> [tfsec](https://github.com/tfsec/tfsec)) — Terraform static analysis tool that prevents potential security issues by checking cloud misconfigurations at build time and directly integrates with the HCL parser for better results. Checks for violations of AWS, Azure and GCP security best practice recommendations.

- 🌎 [trufflehog](trufflesecurity.com) — Find credentials all over the place
TruffleHog is an open source secret-scanning engine that resolves exposed secrets across your company’s entire tech stack. 

- <b><code>&nbsp;&nbsp;8553⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;919🍴</code></b> [Tsunami Security Scanner](https://github.com/google/tsunami-security-scanner)) — A general purpose network security scanner with an extensible plugin system for  detecting high severity RCE-like vulnerabilities with high confidence. Custom detectors for finding vulnerabilities (e.g. open APIs) can be added.


<a name="smart-contracts" />
<h2>Smart Contracts</h2>


- <b><code>&nbsp;&nbsp;4215⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;810🍴</code></b> [mythril](https://github.com/ConsenSys/mythril)) — A symbolic execution framework with batteries included, can be used to find and exploit vulnerabilities in smart contracts automatically.

- 🌎 [MythX](mythx.io) :copyright: — MythX is an easy to use analysis platform which integrates several analysis methods like fuzzing, symbolic execution and static analysis to find vulnerabilities with high precision. It can be integrated with toolchains like Remix or VSCode or called from the command-line.

- <b><code>&nbsp;&nbsp;6168⭐</code></b> <b><code>&nbsp;&nbsp;1093🍴</code></b> [slither](https://github.com/trailofbits/slither)) — Static analysis framework that runs a suite of vulnerability detectors, prints visual information about contract details, and provides an API to easily write custom analyses.

- 🌎 [solhint](protofire.github.io/solhint) — Solhint is an open source project created by https://protofire.io. Its goal is to provide a linting utility for Solidity code.

- 🌎 [solium](ethlint.readthedocs.io/en/latest) — Solium is a linter to identify and fix style and security issues in Solidity smart contracts.


<a name="support" />
<h2>Support</h2>


- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [LibVCS4j](https://github.com/uni-bremen-agst/libvcs4j)) — A Java library that allows existing tools to analyse the evolution of software systems by providing a common API for different version control systems and issue trackers.

- <b><code>&nbsp;&nbsp;&nbsp;522⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst)) — Identifies and prioritizes God Classes and Highly Coupled classes in Java codebases you should refactor first.

- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Violations Lib](https://github.com/tomasbjerre/violations-lib)) — Java library for parsing report files from static code analysis. Used by a bunch of Jenkins, Maven and Gradle plugins.


<a name="template" />
<h2>Template-Languages</h2>


- <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;234🍴</code></b> [ember-template-lint](https://github.com/ember-template-lint/ember-template-lint)) — Linter for Ember or Handlebars templates.

- <b><code>&nbsp;&nbsp;&nbsp;335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [haml-lint](https://github.com/sds/haml-lint)) — Tool for writing clean and consistent HAML.

- <b><code>&nbsp;&nbsp;&nbsp;225⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [slim-lint](https://github.com/sds/slim-lint)) — Configurable tool for analyzing Slim templates.

- 🌎 [yamllint](yamllint.readthedocs.io) — Checks YAML files for syntax validity, key repetition and cosmetic problems such as lines length, trailing spaces, and indentation.


<a name="terraform" />
<h2>Terraform</h2>


- 🌎 [GitGuardian ggshield](www.gitguardian.com/ggshield) — ggshield is a CLI application that runs in your local environment  or in a CI environment to help you detect more than 350+ types of secrets,  as well as other potential security vulnerabilities or policy breaks affecting your codebase.

- 🌎 [kics](kics.io/) — Find security vulnerabilities, compliance issues, and infrastructure misconfigurations in your infrastructure-as-code. Supports Terraform, Kubernetes, Docker, AWS CloudFormation and Ansible

- **shisho** :warning: — A lightweight static code analyzer designed for developers and security teams. It allows you to analyze and transform source code with an intuitive DSL similar to sed, but for code.


<a name="translation" />
<h2>Translation</h2>


- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [dennis](https://github.com/willkg/dennis)) — A set of utilities for working with PO files to ease development and improve quality.


<a name="vue" />
<h2>Vue.js</h2>


- 🌎 [HTML-Validate](html-validate.org/) — Offline HTML5 validator.

- **Vetur** :warning: — Vue tooling for VS Code, powered by vls (vue language server). Vetur has support for formatting embedded HTML, CSS, SCSS, JS, TypeScript, and more. Vetur only has a "whole document formatter" and cannot format arbitrary ranges.


<a name="writing" />
<h2>Writing</h2>


- **After the Deadline** :warning: — Spell, style and grammar checker.

- **alex** :warning: — Catch insensitive, inconsiderate writing

- <b><code>&nbsp;&nbsp;2337⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;507🍴</code></b> [codespell](https://github.com/codespell-project/codespell)) — Check code for common misspellings.

- 🌎 [languagetool](languagetool.org) — Style and grammar checker for 25+ languages. It finds many errors that a simple spell checker cannot detect.

- <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [misspell-fixer](https://github.com/vlajos/misspell-fixer)) — Quick tool for fixing common misspellings, typos in source code.

- 🌎 [Misspelled Words In Context](jwilk.net/software/mwic) — A spell-checker that groups possible misspellings and shows them in their contexts.

- <b><code>&nbsp;&nbsp;4520⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [proselint](https://github.com/amperser/proselint)) — A linter for English prose with a focus on writing style instead of grammar.

- 🌎 [vale](vale.sh) — A syntax-aware linter for prose built with speed and extensibility in mind.

- **write-good** :warning: — A linter with a focus on eliminating "weasel words".


<a name="yaml" />
<h2>YAML</h2>


- 🌎 [Spectral](stoplight.io/open-source/spectral) — A flexible JSON/YAML linter, with out-of-the-box support for OpenAPI v2/v3 and AsyncAPI v2.

- 🌎 [yamllint](yamllint.readthedocs.io) — Checks YAML files for syntax validity, key repetition and cosmetic problems such as lines length, trailing spaces, and indentation.


<a name="git" />
<h2>git</h2>


- 🌎 [commitlint](commitlint.js.org) — checks if your commit messages meet the conventional commit format

- 🌎 [GitGuardian ggshield](www.gitguardian.com/ggshield) — ggshield is a CLI application that runs in your local environment  or in a CI environment to help you detect more than 350+ types of secrets,  as well as other potential security vulnerabilities or policy breaks affecting your codebase.

- 🌎 [HasMySecretLeaked](gitguardian.com/hasmysecretleaked) :copyright: — HasMySecretLeaked is a project from GitGuardian that aims to help individual users and organizations search across 20 million exposed secrets to verify if their  developer secrets have leaked on public repositories, gists, and issues on GitHub projects.


## More Collections

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Clean code linters](https://github.com/collections/clean-code-linters)) — A collection of linters in github collections
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Code Quality Checker Tools For PHP Projects](https://github.com/collections/code-quality-in-php)) — A collection of PHP linters in github collections
- <b><code>&nbsp;&nbsp;6735⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;407🍴</code></b> [go-tools](https://github.com/dominikh/go-tools)) — A collection of tools and libraries for working with Go code, including linters and static analysis
- <b><code>&nbsp;&nbsp;&nbsp;349⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [linters](https://github.com/mcandre/linters)) — An introduction to static code analysis
- 🌎 [OWASP Source Code Analysis Tools](owasp.org/www-community/Source_Code_Analysis_Tools) — List of tools maintained by the Open Web Application Security Project
- <b><code>&nbsp;&nbsp;2872⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;245🍴</code></b> [php-static-analysis-tools](https://github.com/exakat/php-static-analysis-tools)) — A reviewed list of useful PHP static analysis tools
- 🌎 [AppSec Santa — SAST Tools](appsecsanta.com/sast-tools) — Independent comparison of 30+ static analysis security testing tools with features, pricing, and alternatives
- [Wikipedia](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) — A list of tools for static code analysis.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, 🌎 [Matthias Endler](endler.dev) has waived all copyright and related or neighboring rights to this work.
The underlying source code used to format and display that content is licensed under the MIT license.


Title image 🌎 [Designed by Freepik](www.freepik.com).
## Source
<b><code>&nbsp;14449⭐</code></b> <b><code>&nbsp;&nbsp;1441🍴</code></b> [analysis-tools-dev/static-analysis](https://github.com/analysis-tools-dev/static-analysis))