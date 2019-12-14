# ProcedureKit

A Swift Package for the [ProcedureKit](https://github.com/ProcedureKit/ProcedureKit) module of the ProcedureKit framework.

For information about the reasoning for breaking ProcedureKit up into individual Swift Package repos, see the discussion on the [related ProcedureKit issue](https://github.com/ProcedureKit/ProcedureKit/issues/939). 

This package unfortunately doesn't support the `swift test` command for the tests for the ProcedureKit module, as they depend on the TestingProcedureKit module, which also depends on this module. 
