# interactiveLoop

def int_loop():
    total = 0
    count = 0
    moredata = "yes"
    while moredata == "yes":
        x = float(input("Enter a number  >> "))
        total += x
        count += 1
        moredata = input("Do you have more data?")
    print("Average of the numbers is", total / count)

int_loop()
