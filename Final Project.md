# Final project for ITF Manual Testing Course

<p>For the final project for ITF Manual Testing Course, I chose to present the site: https://www.bebeprice.ro/ </p>
<p>This site is an e-shop with products for newborns and mothers. The catalog should be manageable by the site menu and the user account should manage the personal data of the user (Name, Phone, Email, billing address and the delivery address), protected by a password. </p>

<h2>Tools used to test the functionality of the site </h2>
<p>Tools used: Jira Zephyr Squad.The general presentation of the site, made by the Epic of the Jira project, the next step is to divide the two main modules into 2 stories: “Menus and buttons” and “My Account”. Those two functional specifications created in JIRA should be tested by specific test cases. </p>

<h2>Test Planning </h2>
<p>The Test Plan is designed to describe as much details as possible for the test procesing of those 2 modules of the e-shop project. The plan identifies the items to be tested, the features to be tested, the types of testing to be performed and the risks associated with the plan. </p>
<p>The testing criteria are defined especially by the main scope of the site, thus, to have a catalog with specific products for an e-shop and a personal account for each user of the site. The catalog should be manageable with the menus and buttons used in the site, and the personal account with personal data (Name, phone, email, delivery address, and a history of orders), protected by a password. </p>

<h2>Exit criteria defined </h2>
<p>The menus should have all functional buttons that should facilitate the use of the catalog. The menus and buttons should be the same regardless of the page of the site you are visiting. The name of the page should correspond to the name of the buttons from menus. The personal account should be protected by a password because in here it should be personal data for each user such as: Name, phone, email, delivery address, order history and the payment (the status of the payment and method used to pay). </p>

<h2>Test scope </h2>
<p>tests should reveal all the functionality problems of these two main modules that are tested. </p>

<h2>Risks detected </h2>

<h2>Project risks: </h2>
<p>If the module “My account” does not save personal data correctly or the order history present issues like the status of the payment, the site can become unreliable in the future for users. </p>

<h2>Product risks: </h2>
<p>In order to make it user-friendly, there is the risk of repeating the same menus but with different names for the buttons in the catalog or the name of the pages did not correspond to the name of the pages. Thus, the site can become more confusing than attractive for the user. </p>

<h2>Evaluating entry criteria </h2>
<p>The entry criteria’s defined in the Test Planning phase have been achieved and the test process can continue. </p>

<h2>Test Monitoring and Control </h2>
<p>It will be done by generating periodic reports that reflect the current status of the test. </p>

<h2>Test Analysis </h2>
<p>The testing process will be executed based on the above requirements for the two main modules. The following test conditions were found: </p>

<h2>Test Design </h2>
<p>Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are:</p>
<p>Test cases: </p>
<ol>
  <li>Verify Logout button</li>
  <li>Verify Modifica parola</li>
  <li>Verify Date personale</li>
  <li>Verify Firme</li>
  <li>Verify Adrese</li>
  <li>Verify Livrare & Facturare</li>
  <li>Verify module Buna Fabiola</li>
  <li>Verify Produse favorite</li>
  <li>Verify Status comanda</li>
  <li>Verify Istoric comenzi</li>
  <li>Verify left menu for  Cum Cumpar button in the Top menu</li>
  <li>Verify left menu for Promotiile Lunii button from Top menu</li>
  <li>Verify Comenzi</li>
</ol>

<p>The test cases with steps can be viewed here: test_cases.pdf </p>

<h2>Test Implementation </h2>
<p>The following elements are needed to be ready before the test execution phase begins: </p>
<ol>
  <li>Navigate the site to observe the functionalities of the menus</li>
  <li>create an user accoun</li>
</ol>
  
<h2>Bugs </h2>
<p>Bugs have been created based on the failed tests. The complete list of bugs: </p>
<ol>
  <li>When using the % Oferte speciale button, I can`t find the link to the Promotiile Lunii button from top meniu
  <li>The %Oferte speciale seems to duble the name of the button Promotiile lunii</li>
  <li>The buttons from left menu of the button Promotiile lunii should be the same as those from left menu of the button Home</li>
  <li>The name of the page is: Promotii  and the name of the button in top menu is Promotiile lunii</li>
  <li>In the page Cum cumpar / Politica de retur I should find a link with Formlar De Retur, which can be find in tope meniu</li>
  <li>In left meniu the name of the button Metode de Plata is different from that in top menu; Metode De Plata</li>
  <li>If same buttons have the same name in the left menu as those in top menu, it should have the same order in meniu.</li>
  <li>I can find some buttons from left menu in top meniu</li>
  <li>I can`t find a method to anull an order.</li>
  <li>In the Status comanda page, the search doesn`t find the the order by using the order number of the order</li>
  <li>If the order has been canceled, the message Plata in asteptare still remains</li>
  <li>By using the button Vezi status, the response is Comanda nu a fost gasita</li>
  <li>The product size is added randomly</li>
  <li>The name of the button Adrese from left menu, should be the same as the one of the page.</li>
  <li>The name of the page is DATE PERSONALE...</li>
  <li>I can save data even the fields are maked as mandatory</li>
  <li>The name page is Buna Fabiola, not Stergere cont.</li>
</ol>
<p>And can be found here: https://github.com/FabiolaPop/Final_Project/blob/main/bugs.xlsx</p>
<p>Same exemples can be found here: https://github.com/FabiolaPop/Final_Project/blob/main/bugs.pdf.pdf</p>

<h2>Test Completion </h2>
<p>Exit criteria was evaluated and passed and can be seen here: </p>

<h2>The traceability matrix </h2>
<p>was generated and can be found here:  </p>

<h2>Test Execution </h2>
<p>Test cases are executed on the created test Cycle summary: </p>

<h2>Test Execution chart </h2>
-> enter here test execution report/chart

# The final report shows:
<ol>
  <li>Within this project, all 15 TCs planned for execution were tested.</li>
  <li>From the 15 TCs, a total number of 17 bugs were discovered, whose priorities are 5 (low), 3 (medium) and 9 (high)</li>
  <li>The reported defects have been reduced by upgrading the site.</li>
  <li>In the new version, retesting and regression testing will be performed.</li>
</ol>



