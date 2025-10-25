Midterm Lab Task 1

Problem 1. Use Appropriate Escape Sequence( \n, \t \b \ ..etc) for the problem below
Source Code:

      print("Database Record\n")
      print("\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\")
      print("Name:\t\tJohn Doe")
      print("Email:\t\tjohn.doe@example.com")
      print("University:\tABC University")
Output:

<img width="517" height="193" alt="image" src="https://github.com/user-attachments/assets/623d2ed3-a88a-4411-94cc-d07cabd8a7f7" />

Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f etc… for this task


Source Code:

    sender = "Jane"
    subject = "Greetings"
    version = 1.2
    discount = 10.50
    status = "A"
    code = "ABCD123"
    location = "City XYZ"
    age = 30
    company = "ABC Corporation"
    website = "www.example.com"
    phone = "+1 123-456-7890"
    job_title = "Software Engineer"
    department = "Engineering"
    
    print("Dear John, I hope this email finds you well.")
    print("I wanted to reach out and say hello.")
    print("I hope you are doing well and enjoying your day.")
    print("It's been a while since we last spoke, and I wanted to catch up with you.")
    print("Let's plan to meet up soon and have a great time together!")
    print(f"Subject: {subject}")
    print(f"Sender: {sender}")
    print(f"Version: {version}")
    print(f"Discount: {discount:.2f}%")
    print(f"Status: {status}")
    print(f"Code: {code}")
    print(f"Location: {location}")
    print(f"Age: {age}")
    print(f"Company: {company}")
    print(f"Website: {website}")
    print(f"Phone: {phone}")
    print(f"Job Title: {job_title}")
    print(f"Department: {department}")
Output:

<img width="759" height="469" alt="image" src="https://github.com/user-attachments/assets/213b0427-7d84-40e8-bc84-b08d154ce276" />


Problem 3. Book Reservation; Accept User Input


Source Code:

    title = input("Enter the book title: ")
    author = input("Enter the author: ")
    year = int(input("Enter the year of publication: "))
    genre = input("Enter the genre: ")
    library = input("Enter the library: ")
    member_id = input("Enter your member ID: ")
    return_date = input("Enter the return date: ")
    
    print(f"\nYou have successfully reserved the book '{title}' by {author}.")
    print(f"Year of Publication: {year}")
    print(f"Genre: {genre}")
    print(f"Library: {library}")
    print(f"Member ID: {member_id}")
    print(f"Return Date: {return_date}")
    Output:

<img width="757" height="422" alt="image" src="https://github.com/user-attachments/assets/6da35d63-749b-4add-ac86-48387babf33e" />

Problem 4. Day Identifier


Source Code:
    
    day = int(input("Enter day: "))
    
    if day == 1:
        print("Monday")
    elif day == 2:
        print("Tuesday")
    elif day == 3:
        print("Wednesday")
    elif day == 4:
        print("Thursday")
    elif day == 5:
        print("Friday")
    elif day == 6:
        print("Saturday")
    elif day == 7:
        print("Sunday")
    else:
        print("Invalid input")
Output:

<img width="224" height="179" alt="image" src="https://github.com/user-attachments/assets/5374039f-d048-47ce-82a7-98e9b3c4444f" />
