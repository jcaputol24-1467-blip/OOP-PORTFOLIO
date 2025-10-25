Midterm Lab Task 2:

Source Code:

    product_name = str(input("Enter Product Name:"))
    category = str(input("Enter Category:"))
    quality = float(input("Enter Quality Rating:"))  
    price = float(input("Enter Price Rating:"))
    service = float(input("Enter Service Rating:"))  
    
    def calculate_average_rating(quality,price,service):  
      total = quality + price + service  avg = total / 3  return avg  
    
    def analyze_product():  
      print("Product Name: %s " %product_name )
      print("Category: %s" % category )
      print("Quality Rating: %.2f" % quality) 
      print("Price Rating: %.2f "% price)  
      print("Service Rating: %.2f" % service)  
      print("Overall Average Rating: %.2f" % calculate_average_rating(quality, price, service)) 
      
    analyze product()
Output:

Sample Output 1:

<img width="692" height="406" alt="image" src="https://github.com/user-attachments/assets/7eb28115-1751-4b19-9e01-c598aca3ce74" />


Sample Output 2:

<img width="561" height="389" alt="image" src="https://github.com/user-attachments/assets/8b2cc5a0-0fff-4ec6-8c42-1a7cb28c48d6" />

