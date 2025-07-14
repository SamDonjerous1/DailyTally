Thank you for using the software.
This is a self made accounting software that handles dealers and saree list and also the import/export details and payment details.

## ✨ What It Does
The software is made under a personal request from someone i know who owns a small saree printing business and requested me to somehow transfer the accounting and data logging to the computer. Thus is the birth of this software. 

The business involes some dealers that send saree to the business owner for printing purpose. After the work is done, the sarees are shipped back and appropiate charges are allocated against the order that the dealer have to pay. 
Every 6 months, a sheet is exchanged between two parties to tally if the number of items sent and recieved matches the both sheet. So the track of items coming in and going out is kept in log and payment done and due is also kept in log. 

Here the software comes into play by reducing the workload to more than 70% by automating all the tedious hand done calculations and entries to doing everything just in a few clicks. All the calculations and checkings are automatic. No more
overhead. The software even generates clean PDFs that can be printed out easily and given to the respective dealer.

| Task | Manual | DailyTally |
|------|--------|------------|
| Track sarees sent in & out | Paper logs | One‑click entry |
| Calculate outstanding pieces | Hand math | Auto‑calculated |
| Record payments & dues | Hand math | Integrated ledger |
| Reconcile 6‑month tallies | Tedious check | PDF summary |
| Print shareable reports | Hand drawn tables | Auto‑generated PDF |

## 🚀 How to Use

1. In the first page, we can create new project or open already existing project. Quite self-explainatory.

2. After opening a project the first page that comes is the main page. Here we can see a lots of thing. Lets go one by one.
   1. At the top of the page we can see a menu strip. It has three options,
      File - It has three options, New Project, Open Project, Close.
      Edit - It has two options, Dealers, Sarees. By entering them, a new page opens where we can add/delete the dealer/saree names.
      View - It has two options, Payments, Print. It opens two separate pages about which, the details will be discussed later.
  
   2. At the upper part of the screen, we can see two drop down boxes side by side. The boxes list dealers and Sarees respectively. Selecting both will show the details of import/export accordingly.
   3. Beside the Drop down boxes, there are four buttons, New Import Bill, Edit Import Bill, New Export Bill, Edit Export Bill. These opens separate pages. Will be discussed later.
   4. The Big boxes at the centre shows the list of details for the given dealer and saree.
   5. The orange box at the bottom shows the number of saree imported, exported and reamaining.
   6. A grey box at the upper right is to enter quantity remained from the previous session.

3. The New bill pages shows a few fields. At the top, it shows, "Bill number". Here the import/export bill number has to be entered. Beside it there is a date picker where the date of import/export is to be selected. For import, we have to 
    put the quantity of saree imported. For export, we have to put quantity and the per item price.

4. Edit bill has a drop down where all the previously added bills can be seen and edited. A delete bill button is given that deletes the bill.

5. The payment page shows how much payment is due and how much is paid. The drop down is to select the dealer. It shows that dealer's amount to be paid per bill and how much is already paid and in what mode.
  In the new payment button, a new page is opened where amount, date, mode can be selected and entered.
  At the bottom there a box showing, total due, total paid, amount remaining.

6. The print page show a number of options.
     1. The radio buttons at the top is to select what detail to print.
     2. Below we have a drop down where we can select dealer/saree or we can select "ALL" if we want to print all.
     3. Beside we can select timeline or just use full session to print the whole data ever entered in that project for that particular dealer/seare.
     4. Print will generate the PDFs. Once done it will show a prompt saying "PDFs saved"
     5. The Show folder will open the folder where the PDFs are saved.
  
## ⚙️ Tech Stack

- **Frontend:** WPF (.NET /C#)  
- **Database:** SQLlite  
- **Packaging:** Stand‑alone Windows executable  
- **IDE:** Visual Studio 2022

## 📜 Disclaimer
  
_This software is made for a very neiche purpose, it is not intended for general commercial use. But everyone is welcome to come and try it._
