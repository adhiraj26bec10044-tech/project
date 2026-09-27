    import calendar
    import datetime
    import math

    year = int(input("Enter a year: "))
    leap_years = []

    # 1. Use 'y' instead of 'year' inside the loop
    for y in range(year - 10, year + 11):
        if (y % 4==0 and y%100!= 0) or (y%400==0): 
            leap_years.append(y)

    print("Leap years between", year - 10, "and", year + 10, "are:")
    print(leap_years)
    print("Total leap years found:", len(leap_years))

    # 2. Perform time calculations AFTER the loop has counted the leap years
    days = len(leap_years) * 366
    hours = days * 24
    minutes = hours * 60
    seconds = minutes * 60

    print("Total days:", days)
    print("Total hours:", hours)
    print("Total minutes:", minutes)
    print("Total seconds:", seconds)
