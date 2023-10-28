<h1>Interest Calculator</h1>


<h2>Description</h2>
This project explores the use of parallel arrays and range matching. We are creating an interest calculator for a variety of Loan types. Customers may request a loan that is one of three types and will be given a rate based on their credit score and Loan term. 
<br />
<br />


<h2>Requirements</h2>
Valid credit scores will range from 300-850.
<table border="1">
    <thead>
        <tr>
            <th>Credit Score</th>
            <th>Credit Rating</th>
            <th>Loan Interest</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>300-579</td>
            <td>Poor</td>
            <td>8.014%</td>
        </tr>
        <tr>
            <td>580-669</td>
            <td>Fair</td>
            <td>7.373%</td>
        </tr>
        <tr>
            <td>670-739</td>
            <td>Good</td>
            <td>7.063%</td>
        </tr>
        <tr>
            <td>740-799</td>
            <td>Very good</td>
            <td>6.149%</td>
        </tr>
        <tr>
            <td>800-850</td>
            <td>Excellent</td>
            <td>5.9%</td>
        </tr>
    </tbody>
</table>
<br />
<br />
Based on what type of rate is selected by the user, their loan interest will be modified accordingly. Home loans are loans given by banks or a mortgage company to purchase a home. Auto loans are loans used to purchase a car. An unsecured loan is a loan that does not require collateral. Collateral is money or an object of value used as the default payment if the loan cannot be paid back. 
<table border="1">
    <thead>
        <tr>
            <th>Loan Type</th>
            <th>Base Rate</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Home</td>
            <td>100%</td>
        </tr>
        <tr>
            <td>Auto</td>
            <td>130%</td>
        </tr>
        <tr>
            <td>Unsecured</td>
            <td>200%</td>
        </tr>
    </tbody>
</table>
<br />
<br />
We will also ask for how large the loan will be, for the purposes of a down payment. The company does not originate loans larger than $500,000. The amount must be greater than zero.
<table border="1">
    <thead>
        <tr>
            <th>Loan Amount</th>
            <th>Down Payment Percent</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>$1-499</td>
            <td>0%</td>
        </tr>
        <tr>
            <td>$500-1,999</td>
            <td>10%</td>
        </tr>
        <tr>
            <td>$2,000-9,999</td>
            <td>15%</td>
        </tr>
        <tr>
            <td>$10,000-99,999</td>
            <td>10%</td>
        </tr>
        <tr>
            <td>$100,000-500,000</td>
            <td>5%</td>
        </tr>
    </tbody>
</table>
<br />
<br />
Make sure you use TryParse to validate if a loan type was chosen, if the entered credit score is valid, and if the entered loan amount is valid. If any of the criteria is not met, have a message box display, prompting the user to enter valid inputs.

<h2>Languages and Utilities Used</h2>
- <b>Microsoft Visual Studio</b>
<br />
- <b>C#</b>

<h2>Environments Used </h2>
- <b>Windows 10 Pro</b>


<h2>Examples</h2>

Example output for a home loan of $200000, with a 837 credit score. <br/>
<img src="https://i.imgur.com/IJ6Q5F3.png" height="80%" width="80%" alt="Log into Windows"/>
<br />
<br />
Example output for an auto loan of $35000, with a 740 credit score.
<img src="https://i.imgur.com/GQ8DAkk.png" height="80%" width="80%" alt="dir /r"/>
<br />
<br />


<h2>Conclusion </h2>
The Interest Calculator project serves as a comprehensive tool designed to determine the most suitable interest rates for diverse loan types based on a customer's credit score. By integrating the use of parallel arrays, range matching, and critical validation measures such as TryParse, the application ensures accurate and user-friendly outputs. Furthermore, with its capability to handle multiple criteria like credit rating, loan type, and loan amount, the calculator becomes a pivotal solution for financial institutions and their customers. Developed using Microsoft Visual Studio with C# on a Windows 10 Pro environment, this project not only exhibits robust programming practices but also emphasizes the importance of user experience by providing intuitive and illustrative examples. It stands as a testament to effective software development that prioritizes both functionality and user-centric design.
