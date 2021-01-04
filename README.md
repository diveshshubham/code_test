# code_test
Api to do the follwing tasks - 
  1. The list of offers only returns “visible” offers.
  2. The list of offers contains the number of returned offers and the following information:
    a. Id
    b. Complete teaser information
    c. detailUrl (a link to the webpage)
    d. Labels
    e. Price
  3. The list of offers can be limited to a number (e.g. return only 10 offers)
  4. The list of offers can be filtered by
    a. Portfolio (only one; the default portfolio should be “0001”)
    b. Make (one or more makes, e.g. BMW, Opel)
    c. Price ( from/to, e.g. from 350€ to 450€)
    5. The list of offers is ordered ascending by price.
 6. The detailed offer information is only returned for “visible” offers.
 7. The detailed offer information contains all offer information except teaser and detailUrl.


step -1 : open rot directory of project and open terminal in that directory
step -2 : enter command - npm install
step -3 : after installing enter command - node server.js   
