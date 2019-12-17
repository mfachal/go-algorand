| Op | Description |
| --- | --- |
| `intcblock` | load block of uint64 constants |
| `intc` | push value from uint64 constants to stack by index into constants |
| `intc_0` | push constant 0 from intcblock to stack |
| `intc_1` | push constant 1 from intcblock to stack |
| `intc_2` | push constant 2 from intcblock to stack |
| `intc_3` | push constant 3 from intcblock to stack |
| `bytecblock` | load block of byte-array constants |
| `bytec` | push bytes constant to stack by index into constants |
| `bytec_0` | push constant 0 from bytecblock to stack |
| `bytec_1` | push constant 1 from bytecblock to stack |
| `bytec_2` | push constant 2 from bytecblock to stack |
| `bytec_3` | push constant 3 from bytecblock to stack |
| `arg` | push Args[N] value to stack by index |
| `arg_0` | push Args[0] to stack |
| `arg_1` | push Args[1] to stack |
| `arg_2` | push Args[2] to stack |
| `arg_3` | push Args[3] to stack |
| `txn` | push field from current transaction to stack |
| `gtxn` | push field to the stack from a transaction in the current transaction group |
| `global` | push value from globals to stack |
| `load` | copy a value from scratch space to the stack |
| `store` | pop a value from the stack and store to scratch space |
