# Course Preparation

## A. What do you need

-   A computer running macOS or Windows 10 and above.

-   Access to public internet

---

## B. Environment Setup

**Purpose:**

We will be using Ubuntu 22.04 LTS for this course. Follow the instructions below to install Ubuntu 22.04 LTS on Windows Subsystem for Linux (WSL). This is to enable you to setup and use multichain in a Linux environment. Multichain, like most other blockchain clients, have better compatibility with Linux.

**Instructions:**

**For Windows Users**

**Step 1:** Install Windows Subsystem for Linux (WSL) by following Microsoft's instructions here (https://learn.microsoft.com/en-us/windows/wsl/install).

**Step 2:** Install Windows Terminal by following Microsoft's instructions here (https://learn.microsoft.com/en-us/windows/terminal/install)

**Step 3:** To open a terminal, launch Windows Terminal and click on the "V" icon to open the dropdown menu and select **Ubuntu**.

**For MacOS Users**

**Step 1:** Click on Launcherpad

**Step 2:** Type Terminal into the Search box.

---

## C. Ngrok Setup (15 min)

**Purpose:**

The blockchain service on your computer will be connected to the blockchain service to other computers in a peer-to-peer fashion. To avoid the requirement of setting up port forwarding on your router for connecting from school or home, we utilize **ngrok** for this purpose.

**Instructions:**

**Step 1:** Sign Up for a free ngrok account here (https://ngrok.com/)

**Step 2:** Login to ngrok.com and copy the **Authtoken** as shown below.

![Alt text](./img/ngrok.png)

**Step 3:** Open the terminal.

**Step 4:** Install ngrok for Linux/macOS by following the instructions here (https://ngrok.com/docs/getting-started/). You only need to complete up to step 4 to prove that it is working and see a screen like this.

![Alt text](./img/ngrok-2.png)

In this example, the public link is "https://e3ba-116-88-166-133.ngrok-free.app"

---

## D. Documentation Convention

The documentation will contain code snippets and instructions for terminal commands shown as code boxes. We will adopt the following convention when explaining the instructions.

### 1. Terminal Input

-   The code box for terminal input will begin each line with a `$` character denoting the command prompt. When reading the instructions, enter the commands that comes after the `$` but do not include the `$` character in your input.
-   We will use `#` to denote the example output that will be returned from running the command. Do not enter anything from the line starting with `#`.

    ```sh
    $ this is a command
    $
    # this is the output returned from your command
    ```

### 2. Commandline Console

-   Sometimes, we will be issuing command into a commandline tool, for instance, the MultiChain CLI.
-   Similar to terminal commands, we will precede any instructions with the `>` which denotes the command prompt in a commandline console. Enter the commands that comes after the `>` but do not include the `>` in your input.
-   We will use // to denote the example output that will be returned from running the command.

    ```js
    > getinfo
    //{
    //    "version" : "2.2",
    //    "nodeversion" : 20200901,
    //    "edition" : "Community",
    //    "protocolversion" : 20013,
    //    "chainname" : "chain1",
    //    "description" : "chain1",
    //    "protocol" : "multichain",
    //    "port" : 12010,
    //    "setupblocks" : 60,
    //    "nodeaddress" : "chain1@172.18.0.2:12010",
    //    "burnaddress" : "1XXXXXXWVPXXXXXXLDXXXXXXY6XXXXXXVEESBX",
    //    "incomingpaused" : false,
    //    "miningpaused" : false,
    //    "offchainpaused" : false,
    //    "walletversion" : 10500,
    //    "balance" : 9.9997e+13,
    //    "walletdbversion" : 3,
    //    "reindex" : false,
    //    "blocks" : 60,
    //    "chainrewards" : 1e+14,
    //    "assets" : 2,
    //    "streams" : 2,
    //    "addresses" : 6,
    //    "transactions" : 77,
    //    "peers" : 2,
    //    "timeoffset" : 0,
    //    "connections" : 2,
    //    "proxy" : "",
    //    "difficulty" : 5.96046447753906e-8,
    //    "testnet" : false,
    //    "keypoololdest" : 1688367295,
    //    "keypoolsize" : 2,
    //    "paytxfee" : 0,
    //    "relayfee" : 0,
    //    "errors" : ""
    //}
    ```
