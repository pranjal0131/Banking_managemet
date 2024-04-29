# Banking_managemet
# Bank (DSA Counrse Project)
# Bank (DSA Course Project)

**Objective:**Assume that you own a Bank having 10 ATMs in a city. Design a Banking solution in
**Objective:** Assume that you own a Bank having 10 ATMs in a city. Design a Banking solution in


## Table of contents
@@ -13,44 +13,65 @@ C++ using all the features including STLs to mimic a real life bank.

Bank works in one modes:

1. BANKING MODE
   to swich use command **Z**

<details><summary>BANKING MODE</summary>
<p>
| Command | Description |
| --- | --- |

| O | open an account |
| B | balance enquiry |
| W | withdrawal |
| D | deposit |
| C | close account |




| E | exit and close all accounts |
</p>
</details>

<p>
| Command | Description |
| --- | --- |
| X | PIN change |
| F | fund transfer |
| B | balance enquiry |
| W | withdrawal |
| M | mini statement |
</p>
</details>

It saves data from preveous execution and can load all info on the next execution.
1. [BANKING Mode](#banking-mode)
2. [ATM Mode](#ATM-mode)

to switch between the modes **_use command Z_**

### BANKING Mode

| Command | Description                    |
| ------- | ------------------------------ |
| S       | open bank                      |
| O       | open an account                |
| B       | balance enquiry                |
| W       | withdrawal                     |
| D       | deposit                        |
| C       | close account                  |                                  |
| P       | print all accounts             |
| I       | apply interest to all accounts |
| E       | exit and close all accounts    |

### ATM Mode
# not specific ATM but you can use like ATM Machine
| Command | Description     |
| ------- | --------------- |
| X       | PIN change      |
| F       | fund transfer   |
| B       | balance enquiry |
| W       | withdrawal      |
| M       | mini statement  |

**_It also saves data from preveous execution and can load all info on the next execution_**

## Technologies

Project uses:

- C language


## Setup

- clone project

```

```

- to run project

```make
cd src
make run
```

> > or
```
cd src
make
./a.out
```
