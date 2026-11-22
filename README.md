# Tiny Stack VM

[![make.fun bounty](https://img.shields.io/badge/make.fun-bounty-blue)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node 22](https://img.shields.io/badge/Node-22-green.svg)](https://nodejs.org)

An exact interpreter of make.fun's tiny stack ISA. `main.ts` (Node 22) runs every
`/input/<id>/program.bin` with its `input.bin` and writes `/output/<id>/stdout.bin`
and `/output/<id>/exit.txt`. Practice set: 40/40 match the reference VM.
