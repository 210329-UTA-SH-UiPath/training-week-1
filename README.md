# training week 1

## bash

- what is a shell?
- what is an emulator?
- what is a CLI?
- what is a command?
- what is a flag/option?
- flags
  - `-`
  - `--`
  - `--help`
- commands
  - `pwd`
  - `mkdir [path]`
  - `cd`, `cd .`, `cd ..`, `cd ~`
  - `ls [path]`
  - `touch [filename]`
  - `rm [path]`
  - `cat [path]`

## dotnet

- .NET Platform
  - .NET Standard
  - .NET Core, .NET Framework
  - ASP.NET
  - Languages
  - .NET SDK
- commands
  - `dotnet new [console] [classlib] [xunit]`
  - `dotnet build`
  - `dotnet run`
  - `dotnet add <project> reference <project>`
  - `dotnet sln add **/*.csproj`
  - `dotnet test`
- C#
  - strongly-typed, statically-typed language, compiled
  - value, reference types
  - primitive types: (u)int 32-bit, (u)long 64-bit, (s)byte 8-bit, (u)short 16-bit, float 32-bit, double 64-bit, decimal 128-bit, bool, char, string
  - all primitive types are value except for string
  - lifecycle of csharp: compilation -> assembly -> runtime -> bytecode
  - assembly
    - IL (MSIL) = Micosoft intermediate language
    - CLI = common language infrastructure
    - CIL = common intermediate language
  - runtime
    - CLR = common language runtime
      - portability = any system
      - interoperability = any language
      - memory management = managed code, unmanaged code, garbage collection
      - performance = consistency on any system
    - BCL = base class library
    - CTS = common type system
    - JIT = just in time compiler
    - VES = virtual execution system (runtime)
  - what is good code?
    - scalable
    - modular
    - readable
    - maintainable
    - testable
    - configurable
  - modifiers
    - access: public, private protected, internal (protected internal, private protected)
    - general: static, const, readonly, new, override, abstract, sealed, virtual
  - project files, solution files
  - scopes
    - namespace
    - class, interface, struct, enum
    - method
    - block

## git

- `git init`
- `git add `
- `git commit`
- `git status`
- `git rm` (be careful)
- `git log --depth`
- `git clone` = copy for the first time from remote to local
- `git pull` = sync from remote to local folowing first copy


##

- MS Docs: docs.microsfot.com/learn/csharp

## code challenges

### fizzbuzz

count from 0 to 100, print the number unless
if number is multiple of 3, print _fizz_
if number is multiple of 5, print _buzz_
if number is multiple of both, print _fizzbuzz_

### palindrome
