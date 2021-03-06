# Data-driven Campaign for the 2022 PH Elections
This is a data-driven analysis for one of may favored presidential candidates, namely, Leni Robredo, in the upcoming 2022 presidential elections in the Philippines. The data is obtained from the House of Representatives' Legislative Information System or http://www.congress.gov.ph/legis/ through web-scraping using R and analyzed using various packages such as ggplot2 package to generate charts.

Here are the variables obtained for the chosen candidate (Robredo, Leni.csv):

1) **dates_filed**: Date of filling of house bill
2) **house_bill_no**: House Bill No.
3) **full_title**: Full title of the filed/endorsed House Bill
4) **short_title**: Short/alternative title of the filed/endorsed House Bill
5) **republic_act_no**: Republic Act No. of the House Bill (if enacted into law)
6) **republic_act_title**: Republic Act Title of the House Bill (if enacted into law)
7) **significance**: Scope of the House Bill (national or local)
8) **category**: House Committee referred by the House Bill
9) **author**: Author/s of the House Bill being filed/endorsed
10) **status**: Additional side notes regarding the House Bill's progress based on the committee's or other officials' actions
11) **legislation**: Whether the filed house legislation is a bill or a resolution
12) **authorship**: Whether the congressperson was the main author of the bill (primary author) or part of the authors of the bill (co-author)
13) **enacted_into_law**: Whether the bill led to the enactment of law or Republic Act
14) **date_of_enactment**: When the Republic Act of the House Bill was enacted

Here are the variables obtained on the other hand for each of the congressperson (16th_congress_data.csv):

1) **congress_names** - name of congressperson
2) **no_of_days** - total number of unique days when bills are filed	
3) **total_bills_filed** - total number of bills filed
4) **national_bills** - total number of national bills
5) **local_bills** - total number of local bills
6) **authored_bills** - total number of bills primarily authored by the congressperson
7) **co_authored_bills** - total number of bills co-authored by the congressperson
8) **enacted_bills** - total number of bills that led to the enactment of a law/s
9) **national_bills_prop** - proportion of bills that are national
10) **local_bills_prop** - proportion of bills that are local
11) **authored_bills_prop** - proportion of bills that are primarily authored by the congressperson
12) **co_authored_bills_prop** - proportion of bills that are co-authored by the congressperson
13) **enacted_bills_prop** - proportion of bills that led to the enactment of a law/s
