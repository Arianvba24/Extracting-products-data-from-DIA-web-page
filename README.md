# Extracting-products-data-from-DIA-web-page
## Hi folks!

In this project we are going to extract the data from DIA online supermarket for a local supermarket who needs the prices in order to compete in a better way.

First of all we need the links of the product pages we want to extract the data in this case are delicatesses(chease, cured meat, etc).

We'll go to here and get links of the sections we want:

![image](https://github.com/user-attachments/assets/07f5a1e1-c1c3-4c39-b227-33e55dd884e1)

After that we will create a spider(not Scarapy spider) and get the links of the wrapped pages in every section.

Links are hidden to human eye so we gotta use Beautifullsoup to extract all the links belonged to every page.

After getting all the links we will do a loop throught a list created for these links we fetched.

**This is the result:**



https://github.com/user-attachments/assets/83adea7a-312d-45fa-8643-6b3eef11766f




https://github.com/user-attachments/assets/90d4d85e-133e-4b35-b3c8-76cdc84c6744

