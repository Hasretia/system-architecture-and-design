<div dir="rtl">

# טבלת מחלקות - מספור מלא

| # | שם מחלקה | תפקיד המחלקה | Traceability Backward |
|---|-----------|--------------|---------------------|
| 1 | ABS_Purchase | מחלקה אבסטרקטית שמייצגת רכישה כללית מהרשת | **SUC-1:** Reviewing the movie list |
| 2 | MovieTicket | כרטיס להקרנה של סרט, יורשת ממחלקה ABS_Purchase | **SUC-2**: Purchase a movie ticket<br>**SUC-5**: Tickets Return<br>**SUC-14**: View the ticket purchase report at a movie theater<br>**SUC-15**: View a sales report for tickets and viewing packages |
| 3 | HomeViewingPackage_instance | חבילת צפייה שנרכשה על ידי לקוח | **SUC-3**: Purchase a link for home viewing<br>**SUC-6**: Return a home viewing package<br>**SUC-15**: View a sales report for tickets and viewing packages<br>**SUC-23**: Send a reminder for home viewing |
| 4 | MovieInstance | הקרנה של סרט בבית קולנוע | **SUC-1**: Reviewing the movie list<br>**SUC-2**: Purchase a movie ticket<br>**SUC-10**: Change content<br>**SUC-25**: delete movie that time is over |
| 5 | Movie | סרט שנמצא בתוך המאגר סרטים של הרשת | **SUC-1**: Reviewing the movie list<br>**SUC-10**: Change content<br>**SUC-24**: Notify multiple entry ticket owners about new movies |
| 6 | Theater | בית קולנוע | **SUC-12**: View a movie theater report<br>**SUC-14**: View the ticket purchase report at a movie theater<br>**SUC-16**: View the complaint status report at a movie theater |
| 7 | Hall | אולם בתוך בית קולנוע | **SUC-2**: Purchase a movie ticket |
| 8 | Seat | מושב בתוך אולם | **SUC-2**: Purchase a movie ticket |
| 9 | Company | הרשת | **SUC-13**: View reports for the whole network<br>**SUC-15**: View a sales report for tickets and viewing packages<br>**SUC-17**: View a network-wide complaint status report |
| 10 | PriceRequest | בקשה לשינוי מחיר | **SUC-9**: Price change |
| 11 | Complaint | תלונה של לקוח | **SUC-7**: Submitting a complaint<br>**SUC-8**: Handling a complaint<br>**SUC-16**: View the complaint status report at a movie theater<br>**SUC-17**: View a network-wide complaint status report<br>**SUC-22**: Check complaint status |
| 12 | ABS_Person | מחלקה אבסטרקטית המייצגת אדם כללי | **SUC-1**: Reviewing the movie list |
| 13 | RegisteredUser | לקוח רשום בתוך הרשת | **SUC-1**: Reviewing the movie list<br>**SUC-2**: Purchase a movie ticket<br>**SUC-3**: Purchase a link for home viewing<br>**SUC-4**: Purchase a multiple-entry ticket<br>**SUC-5**: Tickets Return<br>**SUC-6**: Return a home viewing package<br>**SUC-7**: Submitting a complaint<br>**SUC-19**: User log-in<br>**SUC-21**: View customer purchases<br>**SUC-22**: Check complaint status |
| 14 | ABS_Employee | מחלקה אבסטרקטית המייצגת עובד כללי | **SUC-1**: Reviewing the movie list<br>**SUC-20**: Employee log-in |
| 15 | CustomerService | עובד שירות לקוחות | **SUC-1**: Reviewing the movie list<br>**SUC-20**: Employee log-in<br>**SUC-8**: Handling a complaint |
| 16 | ContentManager | מנהל התוכן של הרשת | **SUC-1**: Reviewing the movie list<br>**SUC-20**: Employee log-in<br>**SUC-9**: Price change<br>**SUC-10**: Change content |
| 17 | TheaterManager | מנהל בית קולנוע | **SUC-1**: Reviewing the movie list<br>**SUC-20**: Employee log-in<br>**SUC-12**: View a movie theater report<br>**SUC-14**: View the ticket purchase report at a movie theater<br>**SUC-16**: View the complaint status report at a movie theater |
| 18 | CompanyManager | מנהל הרשת | **SUC-1**: Reviewing the movie list<br>**SUC-20**: Employee log-in<br>**SUC-12**: View a movie theater report<br>**SUC-13**: View reports for the whole network<br>**SUC-14**: View the ticket purchase report at a movie theater<br>**SUC-15**: View a sales report for tickets and viewing packages<br>**SUC-16**: View the complaint status report at a movie theater<br>**SUC-17**: View a network-wide complaint status report<br>**SUC-18**: Request additional reports |
| 19 | UserMainPage | הדף הראשי של הרשת | **SUC-1**: Reviewing the movie list |
| 20 | UserMainPageCont | מחלקת השליטה של הדף הראשי | **SUC-1**: Reviewing the movie list |
| 21 | CancelPurchasePage | דף ביטול רכישה כלשהי של לקוח רשום | **SUC-21**: View customer purchases<br>**SUC-5**: Tickets Return<br>**SUC-6**: Return a home viewing package |
| 22 | CancelPurchasePageCont | מחלקת השליטה של דף ביטול רכישה כלשהי של לקוח רשום | **SUC-21**: View customer purchases<br>**SUC-5**: Tickets Return<br>**SUC-6**: Return a home viewing package |
| 23 | home_viewing_purchase_page | דף רכישת קישור לצפייה ביתית | **SUC-3**: Purchase a link for home viewing<br>**SUC-21**: View customer purchases<br>**SUC-23**: Send a reminder for home viewing |
| 24 | home_viewing_purchase_page_cont | מחלקת השליטה של דף רכישת קישור לצפייה ביתית | **SUC-3**: Purchase a link for home viewing<br>**SUC-21**: View customer purchases<br>**SUC-23**: Send a reminder for home viewing |
| 25 | multi_entry_ticket_purchase_page | דף רכישת כרטיסיה | **SUC-4**: Purchase a multiple-entry ticket |
| 26 | viewUserComplaints_page | דף צפייה בתלונות | **SUC-22**: Check complaint status |
| 27 | viewUserComplaints_cont | מחלקת השליטה של דף צפייה בתלונות | **SUC-22**: Check complaint status |
| 28 | multi_entry_ticket_purchase_page_cont | מחלקת השליטה של דף רכישת כרטיסיה | **SUC-4**: Purchase a multiple-entry ticket |
| 29 | movie_page | דף צפייה בפרטי הסרט | **SUC-1**: Reviewing the movie list<br>**SUC-2**: Purchase a movie ticket<br>**SUC-3**: Purchase a link for home viewing |
| 30 | movie_page_cont | מחלקת השליטה של דף צפייה בפרטי הסרט | **SUC-1**: Reviewing the movie list<br>**SUC-2**: Purchase a movie ticket<br>**SUC-3**: Purchase a link for home viewing |
| 31 | login_page | דף כניסה לאזור האישי של לקוח רשום | **SUC-19**: User log-in |
| 32 | login_page_cont | מחלקת השליטה של דף כניסה לאזור האישי של לקוח רשום | **SUC-19**: User log-in |
| 33 | employee_login_page | דף ההתחברות של עובד | **SUC-20**: Employee log-in |
| 34 | employee_login_page_cont | מחלקת השליטה של דף ההתחברות של עובד | **SUC-20**: Employee log-in |
| 35 | compliant_handling_page | דף יצירת תלונה | **SUC-8**: Handling a complaint |
| 36 | compliant_handling_page_cont | מחלקת השליטה של דף יצירת תלונה | **SUC-8**: Handling a complaint |
| 37 | movie_ticket_purchase_page | דף רכישת כרטיס לסרט | **SUC-2**: Purchase a movie ticket |
| 38 | movie_ticket_purchase_page_cont | מחלקת השליטה דף רכישת כרטיס לסרט | **SUC-2**: Purchase a movie ticket |
| 39 | seat_selection_bound | דף בחירת מושב באולם | **SUC-2**: Purchase a movie ticket |
| 40 | seat_selection_bound_cont | מחלקת השליטה דף בחירת מושב באולם | **SUC-2**: Purchase a movie ticket |
| 41 | movie_list_and_viewing_packages_update_page | דף עדכון רשימת הסרטים וחבילות צפייה | **SUC-9**: Price change<br>**SUC-10**: Change content |
| 42 | movie_list_and_viewing_packages_update_page_cont | מחלקת השליטה דף עדכון רשימת הסרטים וחבילות צפייה | **SUC-9**: Price change<br>**SUC-10**: Change content |
| 43 | Price_Change_Confirmation_Page | דף אישור שינוי מחירים | **SUC-9**: Price change |
| 44 | Price_Change_Confirmation_Page_cont | מחלקת השליטה של דף אישור שינוי מחירים | **SUC-9**: Price change |
| 45 | reports_page_bound | דף הדוחות | **SUC-11**: Generate monthly reports<br>**SUC-12**: View a movie theater report<br>**SUC-13**: View reports for the whole network<br>**SUC-14**: View the ticket purchase report at a movie theater<br>**SUC-15**: View a sales report for tickets and viewing packages<br>**SUC-16**: View the complaint status report at a movie theater<br>**SUC-17**: View a network-wide complaint status report<br>**SUC-18**: Request additional reports |
| 46 | reports_page_cont | מחלקת השליטה של דף הדוחות | **SUC-11**: Generate monthly reports<br>**SUC-12**: View a movie theater report<br>**SUC-13**: View reports for the whole network<br>**SUC-14**: View the ticket purchase report at a movie theater<br>**SUC-15**: View a sales report for tickets and viewing packages<br>**SUC-16**: View the complaint status report at a movie theater<br>**SUC-17**: View a network-wide complaint status report<br>**SUC-18**: Request additional reports |
| 47 | EmployeeToolBar | תפריט בחירה לבחירת דפים שונים של עובד | **SUC-20**: Employee log-in |
| 48 | UserToolBar | תפריט בחירה לבחירת דפים של לקוח | **SUC-19**: User log-in |
| 49 | Message | מחלקת מסוג הודעה שתישלח מclient לserver ולהפך כל מחלקות ההודעות האחרות יורשות ממנה | - |
| 50 | PriceChangeConfermationMessage | יורשת ממחלקה Message, תפקידה היא שכאשר עושים שינוי מחיר תשלח הודעה לשרת ובתוכה כל הישויות הנחוצות | **SUC-9**: Price change |
| 51 | ComplaintListMessage | יורשת ממחלקת Message, תפקידה היא שכאשר יהיה שימוש בתלונות מרובות תשלח הודעה לשרת ובתוכה כל הישויות הנחוצות | **SUC-8**: Handling a complaint<br>**SUC-16**: View the complaint status report at a movie theater<br>**SUC-17**: View a network-wide complaint status report |
| 52 | ReportMessage | יורשת ממחלקה Message, תפקידה היא שכאשר עושים פעולה עם דוח תשלח הודעה לשרת ובתוכה כל הישויות הנחוצות | **SUC-11**: Generate monthly reports<br>**SUC-12**: View a movie theater report<br>**SUC-13**: View reports for the whole network<br>**SUC-14**: View the ticket purchase report at a movie theater<br>**SUC-15**: View a sales report for tickets and viewing packages<br>**SUC-18**: Request additional reports |
| 53 | MoviesListMessage | יורשת ממחלקה Message, תפקידה היא שכאשר נרצה להשתמש ברשימת הסרטים תשלח הודעה לשרת ובתוכה כל הישויות הנחוצות | - |
| 54 | MoviesInstanceListMessage | יורשת ממחלקה Message, תפקידה היא שכאשר נרצה להשתמש בהקרנות תשלח הודעה לשרת ובתוכה כל הישויות הנחוצות | - |
| 55 | TheaterMessage | יורשת ממחלקה Message, תפקידה היא שכאשר נשתמש בבתי קולנוע תשלח הודעה לשרת ובתוכה כל הישויות הנחוצות | - |
| 56 | PurchaseMessage | יורשת ממחלקה Message, תפקידה היא שכאשר נשתמש בתלונה תשלח הודעה לשרת ובתוכה כל הישויות הנח


</div>
