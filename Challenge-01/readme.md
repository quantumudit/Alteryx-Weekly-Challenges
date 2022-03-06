## Challenge - 01 : Join To Range

### Problem Statement:

A company in Australia has source data which is made up of a series of postal codes (eg. 2000, 2001, 2002 etc.) amongst some other data fields.

They have a separate reference table which contains postcode ranges (eg. 2000 to 2002) which they would like to use to match/filter their main data.

Each Customer Record needs to be joined to the Lookup table based on a Postal Area Ranged region.

Then finally summarize the customer data by Region, Sales Rep, and Responder, then a count of customers.

> Here is the weekly challenge link in the Alteryx community: [Challenge #1: Join to Range][community_link]

### Concept & Highlights Covered

This challenge covers the following concepts:

- Data Preparation

The Alteryx tools and techniques that can be used to solve this challenge are as follows:

- Prepare
- Join
- Parse
- Transform

### Solution:

Here is the snippet of the workflow that achieves the required result:

![Workflow Snippet][wf_snp]

<!-- Links -->

[wf_snp]: ../RESOURCES/c01_wf.png
[community_link]: https://community.alteryx.com/t5/Weekly-Challenge/Challenge-1-Join-to-Range/td-p/36621
