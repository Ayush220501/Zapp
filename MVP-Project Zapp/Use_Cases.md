Use Cases:

●	Authenticate: The user logs in or authenticates to access their account information.
Requisite: User is not authenticated.
Result: User gains access to their account.

●	Check Balance: The user can check their account balance.
Requisite: User is authenticated.
Result: Chatbot displays the account balance.

●	View Transactions: The user can view their recent transactions.
Requisite: User is authenticated.
Result: Chatbot displays recent transaction details.

●	Make a Payment: The user initiates a payment to a payee.
Requisite: User is authenticated and has a linked payment method.
Result: Chatbot facilitates the payment process and provides a confirmation.

●	Ask for Help: The user can request assistance or information from the chatbot.
Requisite: User is authenticated or not.
Result: Chatbot provides assistance or information.

●	End Session: The user can end the chatbot session.
Requisite: The user is interacting with the chatbot.
Result: The chatbot closes the session.

●	Escalate to Human: The user can escalate the conversation to a human agent.
	Requisite: User needs further assistance beyond the chatbot's capabilities.
	Result: Chatbot hands over the conversation to a human agent.

●	Provide Feedback: The user can provide feedback on their chatbot experience.
	Requisite: The user has interacted with the chatbot.
	Result: User feedback is collected for improvement.

●	Access Account Information: The user can request specific account details.
	Requisite: User is authenticated.
	Result: Chatbot provides the requested account information.

●	Set Alerts: The user can set up account alerts for specific events.
	Requisite: User is authenticated.
	Result: Chatbot assists in configuring account alerts.

●	Change Password: The user can change their account password.
	Requisite: User is authenticated.
	Result: Chatbot assists in changing the password.

●	Inquire About Services: The user can inquire about banking services.
	Requisite: User is authenticated or not.
	Result: Chatbot provides information about available services.

●	Report Lost Card: The user can report a lost or stolen card.
	Requisite: User is authenticated.
	Result: Chatbot guides the user through the card reporting process.

●	Transfer Funds: The user can transfer funds between accounts.
	Requisite: User is authenticated and has multiple accounts.
	Result: Chatbot facilitates the fund transfer and provides confirmation.

●	Apply for a Loan: The user can apply for a loan.
	Requisite: User is authenticated.
	Result: Chatbot guides the user through the loan application process.


This use case diagram with "requisite" and "result" clarifies the conditions under which each use case is initiated and the outcomes that are achieved after the interaction with the chatbot.


●	User Initiation:The user initiates the banking chatbot.

●	Greeting:The chatbot greets the user.

●	Authentication:User provides authentication details.If successfully           authenticated, proceed to the next step.

●	Main Menu:The user can choose from various banking actions.

●	Selected Action:User selects a specific action from the menu.The chatbot  processes the selected action.

●		Action Results:
●		Depending on the selected action, various results are possible:
●		Displaying Account Balance
●		Displaying Transaction Details
●		Facilitating a Payment
●		Providing Assistance or Information
●		Closing the Session
●		Handing Over to a Human Agent
●		Collecting User Feedback
●		Displaying Account Information
●		Assisting in Setting Alerts
●		Assisting in Changing Password
●		Providing Service Information
●		Guiding Through Card Reporting
●		Facilitating Fund Transfer
●		Guiding Through Loan Application

●	User Interaction Continues:Depending on the action result, the user can choose to perform additional actions or end the session.

●	Feedback:
●	User provides feedback on the chatbot experience.
●	Feedback is collected for improvement.
●	Escalation:
●	User escalates the conversation to a human agent.
●	The chatbot transfers the conversation to a human agent.
●	Human Agent Interaction:
●	User interacts with a human agent for further assistance.
●	Interaction with the human agent ends.
●	Session End:
●	User ends the chatbot session.


This flowchart outlines the sequence of events in the user's interaction with a banking chatbot, from initiation and authentication to specific actions, results, feedback, and potential escalation to human agents.
