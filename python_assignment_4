A = [["Flight ID","From","To","Price"],["Al161E90","BLR","BOM",5600],
    ["BR161F91","BOM","BBI",6750],
["Al161F91","BBI","BLR",8210],
["VS171E20","JLR","BBI",5500],
["AS171G30","HYD","JLR",4400],
["AI131F49","HYD","BOM",3499]]
print(A)
p = input("Select an option: 1. Flights for a particular City, 2. Flights From a city, 3. Flights between two given cities")
def flight_city(A,p):
    if p=="1":
        q = input("Select the city")
        for i in A:
            for j in i:
                if j == q:
                    if i[1]==q:
                        print(i)
    if p=="2":
        q = input("Select the city")
        for i in A:
            for j in i:
                if j == q:
                    if i[2]==q:
                        print(i)
    if p=="3":
        q = input("Select the from city")
        r = input("Select the to city")
        for i in A:
            for j in i:
                if j == q:
                    if i[1]==q:
                        if i[2]==r:
                            print(i)

flight_city(A,p)