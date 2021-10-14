## Riscv Single Cycle Core
This is the single cycle core based on RISCV "I" Extension. RISCV is an open source instruction set architecture.

### How to use
First clone the repo:

```bash
git clone https://github.com/Anushakhalil/Riscv-Single-Cycle-Cores/tree/main/src/main/scala/Anusha_khalil
```
Then open the directory in your Scala-chisel support IDE and run the command below:

```bash
sbt
```
Then run the command below to test the built on VCD:

```bash
testOnly singleCycle.TopTest -- -DwriteVcd=1
```
 	> The vcd will be created in the directory named *test_run_dir*