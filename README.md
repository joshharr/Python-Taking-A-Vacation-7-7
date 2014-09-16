Python-Taking-A-Vacation-7-7
============================

*DISCLAIMER* I do not own anything related to the Codeacademy website/name

def hotel_cost(nights):
    # $140 per night
    return 140 * nights
def plane_ride_cost(city):
    if city == "Charlotte":
        return 183
    elif city == "Tampa":
        return 220
    elif city == "Pittsburgh":
        return 222
    elif city == "Los Angeles":
        return 475
def rental_car_cost(days):
        cost = 40 * days
        if days >= 7:
            cost -= 50
        elif days >= 3:
            cost -= 20
        return cost
def trip_cost(city, days, spendingmoney):
    a = plane_ride_cost(city)
    b = hotel_cost(days)
    c = rental_car_cost(days)
    d = spendingmoney
    sum = a + b + c + d
    return sum
print trip_cost("Los Angeles",5,600)

*PS* I don't know how to show my exact indented code, so bear with me here ;) Have a good one!

