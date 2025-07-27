# dose calculator
Dose=int(input("Dose in mg per kg body weight: "))
weight=float(input("enter bodyweight in kg: "))
adult_dose_in_mg = Dose * weight
print("adult_dose_in_mg: ",adult_dose_in_mg)
if adult_dose_in_mg>2000:
    print("shouldn't be taken without physician consent")
elif adult_dose_in_mg>1000:
    print("Should be taken twice daily in two doses of 500mg")
else:
    print("should be taken when there is symptoms of fever and cold") # bug-free-octo-fiesta
