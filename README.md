![](https://shonharsh.github.io/curriculum-vitae/Images/Banner-UiPath-02.png)

# S07P02 State Machines

This project is my solution in **VB** to the **State Machines** practice found in section 07 practice 02 of the UiPath - RPA Developer Foundation course.

### Getting Started

After making a pull request or downloading the project, open the Main.xaml in UiPath Studio.  The robot can be run with the play button in the ribbon and the result can be seen in output panel.

![Vending](https://raw.githubusercontent.com/ShonHarsh/RPADev-S07P02-StateMachines-VB/main/Data/Images/RPADev-S07P02-StateMachines-VB-BannerVending.jpg)

### Practice Requirements

###### **The Vending Machine**

Create a workflow that simulates a vending machine. The functionality should be the following:

- The user is asked to choose the initial credit ($5, $10, $20) and to choose if he/she wants to proceed or if they changed their mind and want to get the change;
- If they want to continue: They are asked what drink they want: Coffee ($3) or Tea ($2).

Next, the vending machine should check if the user has enough credit for selected drink. If Yes, display a success message and subtract the price of the drink from the total amount.

The user is then asked if he/she wants to buy another drink or to get the change.

If they want to get the change, a message box is displayed with the value of the change to be given to the customer.

### Details

**Course:** UiPath - RPA Developer Foundation

**Section:** 07 Project Organization

**Practice:** 02 State Machines

**Project Format:** Windows, VB

**GitHub:** https://github.com/ShonHarsh/RPADev-S07P02-StateMachines-VB

### Sample Output

![Credit](https://raw.githubusercontent.com/ShonHarsh/RPADev-S07P02-StateMachines-VB/main/Data/Images/RPADev-S07P02-StateMachines-VB-Credit.png)

![Order Items](https://raw.githubusercontent.com/ShonHarsh/RPADev-S07P02-StateMachines-VB/main/Data/Images/RPADev-S07P02-StateMachines-VB-OrderItems.png)

![Item Select](https://raw.githubusercontent.com/ShonHarsh/RPADev-S07P02-StateMachines-VB/main/Data/Images/RPADev-S07P02-StateMachines-VB-ItemSelect.png)

![Cash Out](https://raw.githubusercontent.com/ShonHarsh/RPADev-S07P02-StateMachines-VB/main/Data/Images/RPADev-S07P02-StateMachines-VB-CashOut.png)

```sh
05/15/2024 15:31:45 => [Info] RPADev-S07P02-StateMachines-VB execution started
05/15/2024 15:31:45 => [Info] RPADev-S07P02-StateMachines-VB.Main.Begin;
05/15/2024 15:31:49 => [Info] RPADev-S07P02-StateMachines-VB.Dialog_CreditAccount.Credit; Account Credit: 100
05/15/2024 15:31:57 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: 7up, Cost: 2
Credit: 98
05/15/2024 15:32:03 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Barqs Root Beer, Cost: 2
Credit: 96
05/15/2024 15:32:07 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Cheerwine, Cost: 3
Credit: 93
05/15/2024 15:32:12 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Coca-Cola, Cost: 2
Credit: 91
05/15/2024 15:32:17 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Dr. Pepper, Cost: 2
Credit: 89
05/15/2024 15:32:21 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Java Monster Café Latte, Cost: 3
Credit: 86
05/15/2024 15:32:26 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Java Monster Irish Crème, Cost: 3
Credit: 83
05/15/2024 15:32:31 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Java Monster Loca Moca, Cost: 3
Credit: 80
05/15/2024 15:32:40 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Java Monster Mean Bean, Cost: 3
Credit: 77
05/15/2024 15:32:45 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Java Monster Triple Shot French Vanilla, Cost: 4
Credit: 73
05/15/2024 15:32:50 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Java Monster Triple Shot Mocha, Cost: 4
Credit: 69
05/15/2024 15:32:56 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Vernors Ginger Ale, Cost: 3
Credit: 66
05/15/2024 15:33:00 => [Info] RPADev-RPADev-S07P02-StateMachines-VB.Dialog_DispenseItems.TransactionCompleted; Transaction Complete.
Item: Water, Cost: 1
Credit: 65
05/15/2024 15:33:02 => [Info] RPADev-S07P02-StateMachines-VB.FinalState.CashOut;
Returning funds in pennies: 65
Ordered Items:
7up
Barqs Root Beer
Cheerwine
Coca-Cola
Dr. Pepper
Java Monster Café Latte
Java Monster Irish Crème
Java Monster Loca Moca
Java Monster Mean Bean
Java Monster Triple Shot French Vanilla
Java Monster Triple Shot Mocha
Vernors Ginger Ale
Water
05/15/2024 15:33:02 => [Info] RPADev-S07P02-StateMachines-VB.Main.End;
05/15/2024 15:33:02 => [Info] RPADev-S07P02-StateMachines-VB execution ended in: 00:01:17
```

### Architecture Requirements

A standard UiPath, Studio to Orchestrator cloud setup is the base of operation.  It is easy to setup and free.
1. An Orchestrator connection - Visit https://cloud.uipath.com/ and authenticate or sign up.
2. [UiPath Studio](https://www.uipath.com/product/studio) is used to run the robot.  Note that Studio Web can be used directly in Orchestrator but I recommend installing the Studio IDE application.

[![UiPath Setup Guide](https://shonharsh.github.io/curriculum-vitae/Images/Title-UiPath-Setup-Guide.png)](https://github.com/ShonHarsh/UiPath-SetupGuide)

### Git Notes

Clone the project to develop or change it.

```sh
git clone https://github.com/ShonHarsh/RPADev-S07P02-StateMachines-VB
```

### Links
- [UiPath Automation Platform](https://www.uipath.com/)
- [UiPath Studio](https://www.uipath.com/product/studio)- [Pulsar](https://pulsar-edit.dev/) (Atom Successor) - Used for all my README.md files
- [Shon Harsh Website 127.0.0.1](https://shonharsh.github.io/curriculum-vitae/index.html)
- [This.GitHub](https://github.com/shonharsh)
- [LinkedIn](https://www.linkedin.com/in/shonharsh/)

### RPS Developer Foundation Sections

1. Get Started With RPA Development

2. Variables, Data Types And Control Flow In Studio

   P01 RPADev-S02P01-ForEachIfStatement [[C#](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement)] [[VB](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement-WindowsLegacy)]

   P02 RPADev-S02P02-GenericValue [[C#](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue)] [[VB](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue-WindowsLegacy)]

   P03 RPADev-S02P03-Switch [[C#](https://github.com/ShonHarsh/RPADev-S02P03-Switch)] [[VB](https://github.com/ShonHarsh/RPADev-S02P03-Switch-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S02P03-Switch-WindowsLegacy)]

3. Data Manipulation In Studio

   P01 RPADev-S03P01-Lists [[C#](https://github.com/ShonHarsh/RPADev-S03P01-Lists)] [[VB](https://github.com/ShonHarsh/RPADev-S03P01-Lists-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P01-Lists-WindowsLegacy)]

   P02 RPADev-S03P03-Dictionaries-Integers [[C#](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers)] [[VB](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers-WindowsLegacy)]

   P03 RPADev-S03P04-Dictionaries-Doubles [[C#](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles)] [[VB](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles-WindowsLegacy)]

   P04 RPADev-S03P05-InputValidation [[C#](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation)] [[VB](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation-WindowsLegacy)]

   P05 RPADev-S03P06-ReplacingPlaceholders [[C#](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders)] [[VB](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders-WindowsLegacy)]

   P06 RPADev-S03P07-ExtractEmailAddress [[C#](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress)] [[VB](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress-WindowsLegacy)]

   P07 RPADev-S03P08-ExtractEmailAddressRegEx [[C#](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx)] [[VB](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx-WindowsLegacy)]

4. Excel And Data Tables With Studio

   P01 RPADev-S04P01-CalculatingSums [[C#](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums)] [[VB](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums-WindowsLegacy)]

   P02 RPADev-S04P02-CalculatingLossInvoices [[C#](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices)] [[VB](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices-WindowsLegacy)]

   P03 RPADev-S04P03-CalculatingPercentagesOfExpenses [[C#](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses)] [[VB](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses-WindowsLegacy)]

5. UI Automation With Studio

   P01 RPADev-S05P01-PasswordGenerator [[C#](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator)] [[VB](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator-WindowsLegacy)]

   P02 RPADev-S05P02-TheRPAChallenge [[C#](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge)] [[VB](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge-WindowsLegacy)]

   P03 RPADev-S05P03-InputActions [[C#](https://github.com/ShonHarsh/RPADev-S05P03-InputActions)] [[VB](https://github.com/ShonHarsh/RPADev-S05P03-InputActions-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P03-InputActions-WindowsLegacy)]

   P04 RPADev-S05P04-OutputActions [[C#](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions)] [[VB](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions-WindowsLegacy)]

   P05 RPADev-S05P05-DataScraping [[C#](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping)] [[VB](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping-WindowsLegacy)]

6. Selectors In Studio

   P01 RPADev-S06P01-GetAndSortData [[C#](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData)] [[VB](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData-WindowsLegacy)]

   P02 RPADev-S06P02-SetData [[C#](https://github.com/ShonHarsh/RPADev-S06P02-SetData)] [[VB](https://github.com/ShonHarsh/RPADev-S06P02-SetData-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S06P02-SetData-WindowsLegacy)]

   P03 RPADev-S06P03-Highlight-TypeItems [[C#](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems)] [[VB](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems-WindowsLegacy)]

7. Project Organization In Studio

   P02 RPADev-S07P02-StateMachines [[C#](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines)] [[VB](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines-WindowsLegacy)]

   P03 RPADev-S07P03-FixMyWorkflow [[C#](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow)] [[VB](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow-VB)] [[Windows Legacy](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow-WindowsLegacy)]

   P04 RPADev-S07P04-Libraries

8. Error And Exception Handling In Studio

9. Debugging In Studio

10. PDF Automation In Studio

11. Email Automation With Studio

12. Orchestrator For RPA Developers

13. Robotic Enterprise Framework Overview
