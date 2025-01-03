---
description: Welcome to the Queue Payout Guide!
---

# Queue Payout

This guide will show you how to use the [<mark style="color:blue;">/payout create</mark>](#user-content-fn-1)[^1] command, which helps event and giveaway & event managers set up a queue for prizes that members can claim in a specific time frame.

Using this command can save time and reduce misunderstandings, making it easier for you to run your events and giveaways smoothly. In this guide, we'll review the steps to use the command properly.

We hope this guide helps you organize your events and giveaways more efficiently. Let's get started!

**Before using the **<mark style="color:blue;">**/payout create**</mark>** command, make sure to gather the following information:**

* Event/Giveaway Name
* Message ID where the winners are mentioned or the event winner announcement message ID
* Winners (you can use both mentions and id but they need to add at least one space between each)
* Prize quantity
* Item (if needed)

Ensure all of this information is ready before using the <mark style="color:blue;">/payout create</mark> command. This will help make the payout process smoother and more efficient.

#### Command Examples With Items

* /payout create event:Mega Giveaway message\_id:1116560977580797992 winners: @jay2404 816699167824281621 quantity:10 item:Pink Plastic Bits

#### Command Examples Without Items

* /payout create event:Mega Giveaway message\_id:1116560977580797992 winners: @jay2404 816699167824281621 quantity:10m

#### When entering the arguments, make sure to follow these guidelines:

* Don't enter the item and quantity in the `quantity` argument.
* Use the command in the same channel as the event/giveaway channel or the command will fail.
* When entering the prize quantity, use one of the following formats: 1m, 1e6, or 1.5m. These formats represent million (m), exponent (e6), and million and a half (1.5m), respectively. If you have any questions or issues, feel free to ask your server admin.

## Video Example:

{% embed url="https://youtu.be/0bePT-38uXs" %}

[^1]: \</payout create:1151590528463405149>
