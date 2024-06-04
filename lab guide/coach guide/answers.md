
# Exercise 1
 
  Translate the following sentence into German.
   
  Sentence: I was enjoying the sun, but then a huge cloud came and covered the sky.
  
# Exercise 2

  Negate the following sentence.
  Sentence: I was enjoying the sun, but then a huge cloud came and covered the sky.

# Exercise 3
  Not much to write about here, but it does exactly what it's supposed to. filters out the pop sounds. now my recordings are much more crisp. it is one of the lowest prices pop filters on amazon so might as well buy it, they honestly work the same despite their pricing

  Decide whether the product review's sentiment is positive, neutral or negative. Show the probability for positive, neutral and negative sentiment.

 # Exercise 4
 
  I want you to summarize the following email thread using this format:
  [Summary:]
  [Open Questions:]
  [Action Items:]

# Exercise 5

  Convert the following sentence into third person singular, assuming the person is a female.
  Sentence: I was enjoying the sun, but then a huge cloud came and covered the sky.

# Exercise 6

  Take the following sentence and perform three tasks on it:
  
  1. Translate the sentence into German
  2. Negate the sentence
  3. Convert it into third person, and assume the person is a female.
  The output should be a JSON document. Use the keys "translated", "negated" and "third_person" in the JSON. No need to include the original text.
  Sentence: I was enjoying the sun, but then a huge cloud came and covered the sky.
  

  # Exercise 7

    This is an email from a customer. Extract the following information:
  - Reason for contact
  - Classified reason for contact (can be one of "lost_card", "account_closure", "address_change")
  - Name of customer
  - SSN
  - Date of birth
  Extract it as JSON with keys reason, classified_reason, name, ssn, dob. For dob, use MM/DD/YYYY formatting.
  Email:
  Hello, my name is Mateo Gomez. I lost my Credit card on August 17th, and I would like to request its cancellation. The last purchase I made was of a Chicken parmigiana dish at Contoso Restaurant, located near the Hollywood Museum, for $40. Below is my personal information for validation:
  Profession: Accountant
  Social Security number is 123-45-6789
  Date of birth: 9-9-1989
  Phone number: 949-555-0110
  Personal address: 1234 Hollywood Boulevard Los Angeles CA
  Linked email account: mateo@contosorestaurant.com
  Swift code: CHASUS33XXX
  Result:


  # Exercise 8

    Write a two sentence tagline for this clothing article. Make it more verbose.
  Season: Winter
  Style: Sweater
  Gender: Female
  Target group: Teenager
  Material: Cotton


  # Exercise 9

  Step 1: I want you to act as a social media manager. You will be helping me to brainstorm blog post outline ideas for the topic <Topic 1>:
  Step 2: Write 3 engaging and informative paragraphs about <Idea 1 description>
  Step 3: Write 3 engaging and informative paragraphs about <Idea 2 description>
  Step 4: Tags <List of relevant #hashtags>

  # Exercise 10

    Below is a customer call transcription between customer call employee at Contoso Company and a customer. Extract the following information:

  - Classified reason for contact (can be one of "lost_package", "late_package", "address_change", "new_package_request")
  - Is the problem resolved? (can be one of "resolved", "unresolved")
  - Call summary (in max 100 characters)
  - Name of customer
  - Name of call center employee
  - Customer order number
  - Customer contact information (if not mentioned, then "N/A")
  - New customer address (if the call reason is to change address, else "N/A")
  - Customer's sentiment in the beginning of the call (can be one or more of "calm", "complaining", "angry", "frustrated", "unhappy", "neutral", "happy")
  - Customer's sentiment in the beginning of the call (can be one or more of "calm", "complaining", "angry", "frustrated", "unhappy", "neutral", "happy")
  - How satisfied is the customer in the beginning of the call, 0 being very unsatisfied and 10 being very satisfied
  - How satisfied is the customer in the end of the call, 0 being very unsatisfied and 10 being very satisfied
  - Estimated time of arrival of package
  - Action item (can be one or more of "no_action", "track_package", "inquire_package_status", "make_address_change", "cancel_order", "contact_customer)

  If customer is satisfied in the end, there is no follow up needed. Else, follow up with the relevant internal department to check the status.

  Extract it as JSON with keys classified_reason, resolve_status, call_summary, customer_name, employee_name, order_number, customer_contact_nr, new_address, sentiment_initial, sentiment_final, satisfaction_score_initial, satisfaction_score_final, eta, action_item.

  Employee: "Hello, this is Julia Schreider from Contoso Company. How can I help you today?"
  Customer: "Hi, I am Carsten Mueller. I ordered a package 10 days ago, on February 10th, and it was supposed to arrive in maximum 5 business days. I have called three times already and nobody could provide any more information. I want to know where the package is and I want the problem to be solved immediately. This is the worst service I had for a long time!"
  Employee: "I apologize for the inconvenience, Mr. Mueller. I understand your frustration and I'm here to help. Can you please provide me with your order number so I can look into this for you?"
  Customer: "Yes, it's ACZ456789."
  Employee: "Thank you. I'm looking into it now. Can you please hold for a few minutes while I check the status of your package?"
  Customer: "Okay."
  Employee: "Thank you for your patience. I am sorry to inform you that I am unable to find the status of your package. It appears to have left the sending address, but no up-to-date status on the current location. I will further investigate your case and get back to you as soon as possible via phone call. Could you please provide me your contact information?"
  Customer: "Ah not again. Anyway, my phone number is +4911112223344."
  Employee: "I apologize again for the inconvenience. Is there anything else I can help you with today?"
  Customer: "No."
  Employee: "Thank you. Have a great day!"


# Exercise 11

  Movie description: Paul Atreides, a brilliant and gifted young man born into a great destiny beyond his understanding, must travel to the most dangerous planet in the universe to ensure the future of his family and his people. As malevolent forces explode into conflict over the planet's exclusive supply of the most precious resource in existence-a commodity capable of unlocking humanity's greatest potential-only those who can conquer their fear will survive.
  Tags: ['Action', 'Adventure', 'Science Fiction’]
  ###
  Movie description: A botched store robbery places Wonder Woman in a global battle against a powerful and mysterious ancient force that puts her powers in jeopardy.
  Tags: ['Action', 'Adventure', 'Fantasy']
  ###
  Movie description: After the devastating events of Avengers: Infinity War, the universe is in ruins due to the efforts of the Mad Titan, Thanos. With the help of remaining allies, the Avengers must assemble once more in order to undo Thanos' actions and restore order to the universe once and for all, no matter what consequences may be in store.
  Tags: ['Adventure', 'Science Fiction', 'Action']
  ###
  Movie description: A widowed new dad copes with doubts, fears, heartache and dirty diapers as he sets out to raise his daughter on his own. Inspired by a true story.
  Tags: ['Drama', 'Family', 'Comedy’]
  ###
  Movie description: Harry, Ron and Hermione walk away from their last year at Hogwarts to find and destroy the remaining Horcruxes, putting an end to Voldemort's bid for immortality. But with Harry's beloved Dumbledore dead and Voldemort's unscrupulous Death Eaters on the loose, the world is more dangerous than ever.
  Tags:

  # Exercise 12

    Use SQL with `code-davinci-002` 

  ```
  """
  table customer, columns=firstname, name, customer_id, address
  table orders, columns=order_id, customer_id, product_id, product_amount
  table products, columns=product_id, price, name, description
  Write a query that returns the top 10 orders and show the customer name
  """

  query = 