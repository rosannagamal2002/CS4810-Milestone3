# Part 1 - Initial Class Definitions

---------------------------------------------------------------------------------------------------------------------------

## Class: User

**Attributes:**
+ private String username
+ private String password
+ private Account account

**Methods:** 
+ public void login()
+ logout()
+ createAccount()
+ deleteAccount()
+ changePassword()

**Association:** Associated with Account class.

---------------------------------------------------------------------------------------------------------------------------

## Class: Account

**Attributes:**
+ private List<Subscription> subscriptions
+ private List<Bills> bills
+ private SavingFeature savingFeatures
+ private ExpenseTracker expenseTracker

**Methods:** 
+ public void addSubscription(Subscription)
+ removeSubscription(Subscription)
+ addBill(Bills)
+ removeBill(Bills)

**Association:**
+ Subscription
+ Bills
+ SavingFeature
+ ExpenseTracker

---------------------------------------------------------------------------------------------------------------------------

## Interface: IDueDateNotifier
**Methods:** public void notifyDueDate()

**Association:** Implemented by Subscription and Bills classes.

---------------------------------------------------------------------------------------------------------------------------

## Class: Subscription (extends Feature, implements IDueDateNotifier)

**Attributes:**
+ private String name
+ private Float amount
+ private Date dueDate

**Methods:** 
+ public void notifyDueDate()

**Association:** Associated with Account class.

---------------------------------------------------------------------------------------------------------------------------

## Class: Bills (extends Feature, implements IDueDateNotifier)

**Attributes:**
+ private String name
+ private Float amount
+ private Date dueDate

**Methods:** public void notifyDueDate()

**Association:** Associated with Account class.

---------------------------------------------------------------------------------------------------------------------------

## Class: SavingFeature (extends Feature)

**Attributes:**
+ private Float autoSaveAmount
+ private Float currentBalance

**Methods:** public void autoSave()

**Association:** Associated with Account class.

---------------------------------------------------------------------------------------------------------------------------

## Class: ExpenseTracker (extends Feature)

**Attributes:**
+ private List<Expense> expenses

**Methods:** public void trackExpense(Expense)

**Association:** Associated with Expense and Account classes.

---------------------------------------------------------------------------------------------------------------------------

## Class: Expense

**Attributes:**
+ private String name
+ private Float amount
+ private Date date

**Methods:** None

**Association:** Associated with ExpenseTracker class.

---------------------------------------------------------------------------------------------------------------------------

## Class: SavingEnvelope

**Attributes:**
+ private Float balance
+ private Float savingsGoal

**Methods:** public void deposit(Float), withdraw(Float)

---------------------------------------------------------------------------------------------------------------------------

## Class: GamifiedSaving (extends Feature)

**Attributes:**
+ private Integer userScore
+ private List<SavingGoal> savingGoals

**Methods:** public void updateScore(), checkGoalStatus()

---------------------------------------------------------------------------------------------------------------------------

## Class: ExpenseSplitting (extends Feature)

**Attributes:**
+ private Float totalExpense
+ private List<User> userList

**Methods:** public void splitExpense()

**Association:** Associated with User class.

---------------------------------------------------------------------------------------------------------------------------

## Class: CalendarView (extends Feature)

**Attributes:**
+ private List<Date> dates
+ private List<Event> events

**Methods:** public void addEvent(Event), removeEvent(Event)

---------------------------------------------------------------------------------------------------------------------------

## Class: UnitTest

**Attributes:**
+ private String testName
+ private Boolean testResult

**Methods:** public void runTest()

---------------------------------------------------------------------------------------------------------------------------
