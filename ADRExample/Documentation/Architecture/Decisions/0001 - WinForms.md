# 0001 - WinForms

## Status

Accepted 

## Context

We need to choose the proper UI type for this project.

## Decision

We made the following observations:

- The project needs to run client-side only on windows desktops
- The input is relatively simple, but we need to be able to manipulate the output

Based on these criteria we opted for a Winforms application. Alternatives could have 
been a web app or a command line interface.

## Consequences

We will need to define which UI pattern to use: MVC/MVVM/...
