# to find F.A and S.A perfomances from each quarter
fs_Q1, ft_Q1 = float(input("F.A score: ")), float(input("F.A total: "))
ss_Q1, st_Q1 = float(input("S.A score: ")), float(input("S.A total: "))
fs_Q2, ft_Q2 = float(input("F.A score: ")), float(input("F.A total: "))
ss_Q2, st_Q2 = float(input("S.A score: ")), float(input("S.A total: "))
fs_Q3, ft_Q3 = float(input("F.A score: ")), float(input("F.A total: "))
ss_Q3, st_Q3 = float(input("S.A score: ")), float(input("S.A total: "))
fs_Q4, ft_Q4 = float(input("F.A score: ")), float(input("F.A total: "))
ss_Q4, st_Q4 = float(input("S.A score: ")), float(input("S.A total: "))

# to find tentatives for each quarter
tQ1 = ((fs_Q1 / ft_Q1) * 30) + ((ss_Q1 / st_Q1) * 70)
tQ2 = ((fs_Q2 / ft_Q2) * 30) + ((ss_Q2 / st_Q2) * 70)
tQ3 = ((fs_Q3 / ft_Q3) * 30) + ((ss_Q3 / st_Q3) * 70)
tQ4 = ((fs_Q4 / ft_Q4) * 30) + ((ss_Q4 / st_Q4) * 70)

# to find every quarters grade
# but since there is no previous quarter for first, the grade will simply be the tentative grade
Q1 = tQ1
Q2 = ((Q1 + 2) * tQ2) / 3
Q3 = ((Q2 + 2) * tQ3) / 3
Q4_Final_Grade = ((Q3 + 2) * tQ4) / 3

# to find the Adjectival Equivalent of your Final Grade
if (Q4_Final_Grade >= 96 and Q4_Final_Grade <= 100):
    print("EQUIVALENT: 1.00, ADJECTIVE: EXCELLENT")
elif (Q4_Final_Grade >= 90 and Q4_Final_Grade <= 95.99):
    print("EQUIVALENT: 1.25, ADJECTIVE: VERY GOOD")
elif (Q4_Final_Grade >= 84 and Q4_Final_Grade <= 89.99):
    print("EQUIVALENT: 1.50, ADJECTIVE: VERY GOOD")
elif (Q4_Final_Grade >= 78 and Q4_Final_Grade <= 83.99):
    print("EQUIVALENT: 1.75, ADJECTIVE: GOOD")
elif (Q4_Final_Grade >= 72 and Q4_Final_Grade <= 77.99):
    print("EQUIVALENT: 2.00, ADJECTIVE: GOOD")
elif (Q4_Final_Grade >= 66 and Q4_Final_Grade <= 71.99):
    print("EQUIVALENT: 2.25, ADJECTIVE: SATISFACTORY")
elif (Q4_Final_Grade >= 60 and Q4_Final_Grade <= 65.99):
    print("EQUIVALENT: 2.50, ADJECTIVE: SATISFACTORY")
elif (Q4_Final_Grade >= 55 and Q4_Final_Grade <= 59.99):
    print("EQUIVALENT: 2.75, ADJECTIVE: FAIR")
elif (Q4_Final_Grade >= 50 and Q4_Final_Grade <= 54.99):
    print("EQUIVALENT: 3.00, ADJECTIVE: FAIR")
elif (Q4_Final_Grade >= 40 and Q4_Final_Grade <= 49.99):
    print("EQUIVALENT: 4.00, ADJECTIVE: FAILED ON CONDITION")
else:
    print("EQUIVALENT: 5.00, ADJECTIVE: FAILED")