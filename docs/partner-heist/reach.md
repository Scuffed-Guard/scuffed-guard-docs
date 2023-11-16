---
description: >-
  This page discusses the reach command, and how to read the reach embed
  correctly.
---

# 📊 Reach

The reach command is used to calculate the number of members who can see a specific channel or can be pinged in it.&#x20;

{% hint style="info" %}
The reach command can be invoked using the prefix and slash both i.e `/p reach` and `[prefix]p reach` both will work.
{% endhint %}

An example of the reach embed is shown below

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>each line is numbered and explained below.</p></figcaption></figure>

1.  Shows the number of members who have the _Partnership Ping_ role and the percentage of total server members who have the role i.e $$\frac{\text{role members}}{\text{total server members}} * 100$$


2. Same as `1.` but for the _Partnered Heist Ping_ role.
3. This line shows the total number of members who have ANY of these roles. This is NOT the summation (addition) of members of all roles. In short, this is the number of members who will be pinged.
4. This is the only line that matters, it shows summary of how many members will be pinged, their percentage and out of how many server members.

{% hint style="info" %}
real members or members by default indicate human members i.e non-bot members.
{% endhint %}

#### The reach command has two modes, detailed:True and detailed:False

the detailed (i.e detailed:True) is basically the same as the above example but the textual content is explained more. An example is again shown below for comparison.

{% embed url="https://guarddocs.shx.is/6jP9qXUmy" %}

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

