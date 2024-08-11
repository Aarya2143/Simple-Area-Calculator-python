# Simple Area Calculator
## Code:
    print("*AREA CALCULATOR*")
      print("""Press 1 to find the area of square
      Press 2 to find the area of rectangle
      Press 3 to find the area of circle
      Press 4 to find the area of triangle""")

    choice = int(input("Enter the number between 1-4: "))

    if choice == 1:
    side = float(input("Enter the number of one side:"))
    area = side**2
    print("The area of square", area)
    elif choice == 2:
    length = float(input("Enter the length of rectangle: "))
    width = float(input("Enter the breadth of rectangle: "))
    area = length*width
    print("The area of rectangle", area)
    elif choice == 3:
    radius = float(input("Enter the radius of circle: "))
    area = 2*3.14*radius
    print("Area of circle",area)
    elif choice == 4:
    base =  float(input("Enter the base of triangle: "))
    height = float(input("Enter the height of triangle: "))
    area = 0.5*base*height
    print("Area of the triangle", area)

    else:
      print("Invalid input")
## Output :
- Actual Area calculator Scenario:
  
  ![1](https://github.com/user-attachments/assets/f0ea6262-bd54-4326-a35f-2c3257b2bc11)
- Area of Square:
  
  ![squ](https://github.com/user-attachments/assets/5bd1c165-f44f-41f5-b85a-9a3e69d34acf)
- Area of Rectangle:
  
  ![rec](https://github.com/user-attachments/assets/4a634552-e96a-4807-910d-392524b4a4eb)
-  Area of Circle:

   ![circule](https://github.com/user-attachments/assets/2ce83fb7-cced-4ad7-9498-e9eb5a7aece7)

- Area of Triangle:

  ![tri](https://github.com/user-attachments/assets/93034a65-ede5-45a7-81a7-433630e7df60)

  ## Application:
  An area calculator, which computes the area of different shapes (e.g., rectangles, circles, triangles), has numerous practical applications in everyday life. Here are some examples:

### 1. Home Improvement and Interior Design
Flooring and Carpeting: When installing flooring or carpeting, you need to calculate the area of each room to determine how much material to purchase.

### 2.Painting Walls: 
To estimate the amount of paint required for a room, you need to calculate the area of the walls. This helps in buying the right quantity of paint, avoiding waste or multiple trips to the store.
Furniture Placement: Understanding the area of a room helps in planning furniture layouts, ensuring everything fits well without overcrowding.

### 3. Gardening and Landscaping
Lawn and Garden Planning: Calculating the area of your garden or lawn is essential for determining the amount of soil, seeds, fertilizer, or sod you need.
Paving and Patios: When laying out a patio, driveway, or walkway, you need to calculate the area to estimate the quantity of paving materials required.

### 4. Construction and Real Estate
Building Plans: Architects and builders use area calculations to design building layouts, ensuring that each room or space meets the desired specifications.
Estimating Costs: In construction, the cost of materials like concrete, tiles, or roofing often depends on the area. Accurate area calculations are crucial for budgeting and cost estimation.
Real Estate Listings: When buying or selling property, the area of a house or plot is a key factor in determining its value. Buyers use this information to compare properties.

### 5. Event Planning
Venue Selection: When planning an event, such as a wedding or conference, understanding the area of a venue helps in determining whether it can accommodate the expected number of guests.
Seating Arrangements: Calculating the area of a space helps in organizing seating arrangements, ensuring comfort and compliance with safety regulations.

### 6. Travel and Outdoor Activities
Camping Sites: When setting up a campsite, you may need to calculate the area to ensure there’s enough space for tents, cooking, and other activities.
Planning Outdoor Activities: For activities like sports or picnics, understanding the area of a field or park helps in planning and organizing the space effectively.

### 7. Education
Learning Geometry: Students often use area calculators to solve geometry problems, helping them understand the concepts of shapes and spatial reasoning.
Science Projects: Area calculations are often required in various science projects, such as measuring the surface area of leaves, solar panels, or other objects.
