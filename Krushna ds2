import matplotlib.pyplot as plt

<>

# Age group data (based on the sample data)

df = pd.read_csv("/content/API_SP.POP.TOTL_DS2_en_csv_v2_539841[1].csv", skiprows=4)

plt.figure(figsize=(6,4))

plt.bar(age_groups, population millions, color=["gold", "dodgerblue", "red"], edgecolor="black")

plt.title("India's Population Distribution by Age (2022)")

plt.xlabel("Age Groups")

plt.ylabel("Population (millions)")

# Annotating values on top of bars

for i, val in enumerate (population millions):

plt.text(i, val + 10, f" (percentages[i])%", ha="center", fontsize=10)

plt.show()
